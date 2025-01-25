---
title: why2_list_remove function
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

# why2_list_remove

## Parameters

| Identifier | Data type                                                   |
| ---------- | ----------------------------------------------------------- |
| `list`     | [`why2_list_t *`](../../../../types/core/llist/why2_list_t) |
| `node`     | [`why2_node_t *`](../../../../types/core/llist/why2_node_t) |

## Attributes

|                     |                                                                       |
| ------------------  | --------------------------------------------------------------------- |
| **Return type**     | `void`                                                                |
| **Header comment**  | `REMOVE ELEMENT`                                                      |
| **Added in commit** | [`10632e00703f0935d963c1e2133940c061eb8ed3`](https://github.com/ENGO150/WHY2/commit/10632e00703f0935d963c1e2133940c061eb8ed3) |

## Description

Removes `node` from linked-list (`list`).