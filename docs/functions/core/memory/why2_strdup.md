---
title: why2_strdup function
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

# why2_strdup

## Parameters

| Identifier | Data type |
| ---------- | --------- |
| `string`   | `char *`  |

## Attributes

|                     |                                                |
| ------------------  | ---------------------------------------------- |
| **Return type**     | `void *`                                       |
| **Header comment**  | *This functions doesn't have any description.* |
| **Added in commit** | [`d5ae68c621b61823dc18cf7fe2d93dfb036cbbc1`](https://github.com/ENGO150/WHY2/commit/d5ae68c621b61823dc18cf7fe2d93dfb036cbbc1) |

## Description

Function passes `string` into [`strdup`](https://linux.die.net/man/3/strdup) function and returns the output value. The value is also pushed to [`linked-list`](../../../../types/core/llist/why2_list_t) for garbage collector.