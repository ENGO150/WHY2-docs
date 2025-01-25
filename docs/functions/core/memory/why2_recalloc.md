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

# why2_recalloc

## Parameters

| Identifier   | Data type       |
| ------------ | --------------- |
| `pointer`    | `void *`        |
| `size`       | `unsigned long` |
| `block_size` | `unsigned long` |

## Attributes

|                     |                                                              |
| ------------------  | ------------------------------------------------------------ |
| **Return type**     | `void *`                                                     |
| **Header comment**  | `SAME AS why2_realloc BUT FILLS THE pointer WITH NULL-TERMS` |
| **Added in commit** | [`c5394e63e50e7c2e018a4323d33821c4f4e14884`](https://github.com/ENGO150/WHY2/commit/c5394e63e50e7c2e018a4323d33821c4f4e14884) |

## Description

Function deallocates `pointer` (only applicable if `pointer` was allocated using WHY2-memory), passes `size` and `block_size` into [`calloc`](https://linux.die.net/man/3/calloc) function and returns the output value. The value is also pushed to [`linked-list`](../../../../types/core/llist/why2_list_t) for garbage collector.