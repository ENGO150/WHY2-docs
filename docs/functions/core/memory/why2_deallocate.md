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

# why2_deallocate

## Parameters

| Identifier | Data type |
| ---------- | --------- |
| `pointer`  | `void *`  |

## Attributes

|                     |                                                |
| ------------------  | ---------------------------------------------- |
| **Return type**     | `void`                                         |
| **Header comment**  | *This functions doesn't have any description.* |
| **Added in commit** | [`3491d89a86eba805c3f42543a431cae33bae146b`](https://github.com/ENGO150/WHY2/commit/3491d89a86eba805c3f42543a431cae33bae146b) |

## Description

Function passes `pointer` into corresponding deallocation function ([`free`](https://linux.die.net/man/3/free), [`fclose`](https://linux.die.net/man/3/fclose) or [`closedir`](https://linux.die.net/man/3/closedir)). The value is also removed from [`linked-list`](../../../../types/core/llist/why2_list_t).