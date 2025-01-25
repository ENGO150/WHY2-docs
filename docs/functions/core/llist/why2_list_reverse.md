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

# why2_list_reverse

## Parameters

| Identifier | Data type                                                   |
| ---------- | ----------------------------------------------------------- |
| `list`     | [`why2_list_t *`](../../../../types/core/llist/why2_list_t) |
| `size`     | `unsigned long`                                             |

## Attributes

|                     |                                                                       |
| ------------------  | --------------------------------------------------------------------- |
| **Return type**     | `void`                                                                |
| **Header comment**  | `REVERSES list`                                                       |
| **Added in commit** | [`7dcbd4fc80fa13e5f9d0d4fe90a742c0f8dfab3d`](https://github.com/ENGO150/WHY2/commit/7dcbd4fc80fa13e5f9d0d4fe90a742c0f8dfab3d) |

## Description

Reverses node order in linked-list (`list`). `size` is size of nodes in `list`, because of the reallocations.