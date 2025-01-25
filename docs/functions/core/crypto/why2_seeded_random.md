---
title: why2_seeded_random function
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

# why2_seeded_random

## Parameters

*This functions doesn't take any parameters.*

## Attributes

|                     |                                                                   |
| ------------------  | ----------------------------------------------------------------- |
| **Return type**     | `int`                                                             |
| **Header comment**  | `GENERATE RANDOM NUMBER BASED ON SEED PASSED IN why2_seed_random` |
| **Added in commit** | [`25113dc0b3c97178c85ac02c082164a6d36d3c1e`](https://github.com/ENGO150/WHY2/commit/25113dc0b3c97178c85ac02c082164a6d36d3c1e) |

## Description

Function generates pseudo random `int` with PRNG created in [`why2_seed_random`](../why2_seed_random). The function uses OpenSSL's [`HMAC`](https://docs.openssl.org/1.1.1/man3/HMAC).