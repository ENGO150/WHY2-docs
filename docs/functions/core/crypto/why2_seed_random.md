---
title: why2_seed_random function
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

# why2_seed_random

## Parameters

| Identifier | Data type        |
| ---------- | ---------------- |
| `seed`     | `unsigned long`  |

## Attributes

|                     |                                  |
| ------------------  | -------------------------------- |
| **Return type**     | `void`                           |
| **Header comment**  | `SEED why2_seeded_random OUTPUT` |
| **Added in commit** | [`25113dc0b3c97178c85ac02c082164a6d36d3c1e`](https://github.com/ENGO150/WHY2/commit/25113dc0b3c97178c85ac02c082164a6d36d3c1e) |

## Description

Function inits pseudo random number generator `struct` with `seed`. Seeded numbers can be used with [`why2_seeded_random`](../why2_seeded_random). Also, there is no need to deallocate the PRNG.