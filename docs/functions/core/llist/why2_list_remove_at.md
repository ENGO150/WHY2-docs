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

# why2_list_remove_at

## Parameters

| Identifier | Data type                                                   |
| ---------- | ----------------------------------------------------------- |
| `list`     | [`why2_list_t *`](../../../../types/core/llist/why2_list_t) |
| `index`    | `unsigned long`                                             |

## Attributes

|                     |                                                                       |
| ------------------  | --------------------------------------------------------------------- |
| **Return type**     | `void`                                                                |
| **Header comment**  | `REMOVE ELEMENT WITH INDEX index`                                     |
| **Added in commit** | [`90643d82470dba0c5aaf884a231a55894b8dd39f`](https://github.com/ENGO150/WHY2/commit/90643d82470dba0c5aaf884a231a55894b8dd39f) |

## Description

Removes node on `index` from linked-list (`list`).