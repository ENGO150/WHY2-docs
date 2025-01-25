---
title: why2_sum_segment function
---

<!--
This is part of WHY2
Copyright (C) 2022 Václav Šmejkal

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
-->

# why2_sum_segment

## Parameters

| Identifier | Data type |
| ---------- | --------- |
| `input`    | `char *`  |

## Attributes

|                     |                                                    |
| ------------------  | -------------------------------------------------- |
| **Return type**     | `unsigned long long`                               |
| **Header comment**  | `CALCULATE SUM++ FOR input; USED FOR PADDING SEED` |
| **Added in commit** | [`fb2ac1a7bbcb6f7291f4e89576e1b7f5c1d6fd06`](https://github.com/ENGO150/WHY2/commit/fb2ac1a7bbcb6f7291f4e89576e1b7f5c1d6fd06) |

## Description

Function takes `input` parameter and divides it into segments of [`WHY2_SUM_SEGMENT_SIZE`](../../../../macros/core/crypto/why2_sum_segment_size). Each segment does some xoring, math using [`WHY2_SUM_BASE_PRIME`](../../../../macros/core/crypto/why2_sum_base_prime) and modulates each segment with [`WHY2_SUM_MOD_PRIME`](../../../../macros/core/crypto/why2_sum_mod_prime). The result is then added together and returned.

Output value grows rapidly with increasing `input` length, but unless you are using enormously large keys, nothing should overflow. Function was tested with lengths up to 4096 chars and output was only about 0,0000014 % of the `ULL` range.

This function isn't designed to be completely cryptographically secure! It is meant only for converting string of key into `ULL` with as few collisions as possible.