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

# why2_list_push_at

## Parameters

| Identifier | Data type                                                   |
| ---------- | ----------------------------------------------------------- |
| `list`     | [`why2_list_t *`](../../../../types/core/llist/why2_list_t) |
| `index`    | `unsigned long`                                             |
| `value`    | `void *`                                                    |
| `size`     | `unsigned long`                                             |

## Attributes

|                     |                                                                       |
| ------------------  | --------------------------------------------------------------------- |
| **Return type**     | `void`                                                                |
| **Header comment**  | `PUSH ELEMENT TO INDEX index of LIST`                                 |
| **Added in commit** | [`0e246be627c33f33d82a0fb2e5b43dd3fa024e0c`](https://github.com/ENGO150/WHY2/commit/0e246be627c33f33d82a0fb2e5b43dd3fa024e0c) |

## Description

Function appends new node containing `value` of `size` to the `index` position of linked-list (`list`).

`index` starts with 0.