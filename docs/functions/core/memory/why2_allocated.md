---
title: why2_allocated function
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

# why2_allocated

## Parameters

| Identifier | Data type |
| ---------- | --------- |
| `pointer`  | `void *`  |

## Attributes

|                     |                                                       |
| ------------------  | ----------------------------------------------------- |
| **Return type**     | [`why2_bool`](../../../../types/core/flags/why2_bool) |
| **Header comment**  | `CHECKS IF pointer WAS ALLOCATED USING WHY2-MEM`      |
| **Added in commit** | [`65135ac96161eaa236b37ca2f3ace64345bbba66`](https://github.com/ENGO150/WHY2/commit/65135ac96161eaa236b37ca2f3ace64345bbba66) |

## Description

Function searches [`linked-list`](../../../../types/core/llist/why2_list_t) for `pointer`. If found, `false` is returned, otherwise `true` is returned.