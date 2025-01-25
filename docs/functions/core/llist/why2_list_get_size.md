---
title: why2_list_get_size function
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

# why2_list_get_size

## Parameters

| Identifier | Data type                                                   |
| ---------- | ----------------------------------------------------------- |
| `list`     | [`why2_list_t *`](../../../../types/core/llist/why2_list_t) |

## Attributes

|                     |                                                                       |
| ------------------  | --------------------------------------------------------------------- |
| **Return type**     | `unsigned long`                                                       |
| **Header comment**  | `GET SIZE`                                                            |
| **Added in commit** | [`c4ddb6888afd807abc3c60576475c170e306a5ba`](https://github.com/ENGO150/WHY2/commit/c4ddb6888afd807abc3c60576475c170e306a5ba) |

## Description

Calculates size of linked-list (`list`) (how many nodes are present) and returns it.