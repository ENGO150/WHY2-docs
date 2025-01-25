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

# why2_malloc

## Parameters

| Identifier | Data type       |
| ---------- | --------------- |
| `size`     | `unsigned long` |

## Attributes

|                     |                                                |
| ------------------  | ---------------------------------------------- |
| **Return type**     | `void *`                                       |
| **Header comment**  | *This functions doesn't have any description.* |
| **Added in commit** | [`9c7f40a82528846b6585294b12c5a30e5f1e4533`](https://github.com/ENGO150/WHY2/commit/9c7f40a82528846b6585294b12c5a30e5f1e4533) |

## Description

Function passes `size` into [`malloc`](https://linux.die.net/man/3/malloc) function and returns the output value. The value is also pushed to [`linked-list`](../../../../types/core/llist/why2_list_t) for garbage collector.