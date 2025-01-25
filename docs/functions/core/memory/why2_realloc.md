---
title: why2_realloc function
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

# why2_realloc

## Parameters

| Identifier | Data type       |
| ---------- | --------------- |
| `pointer`  | `void *`        |
| `size`     | `unsigned long` |

## Attributes

|                     |                                                |
| ------------------  | ---------------------------------------------- |
| **Return type**     | `void *`                                       |
| **Header comment**  | `THIS DOESN'T PRESERVE CONTENT OF pointer!`    |
| **Added in commit** | [`8af6bd45c38e780bb14d99aee0a572b028c186b6`](https://github.com/ENGO150/WHY2/commit/8af6bd45c38e780bb14d99aee0a572b028c186b6) |

## Description

Function deallocates `pointer` (only applicable if `pointer` was allocated using WHY2-memory), passes `size` into [`malloc`](https://linux.die.net/man/3/malloc) function and returns the output value. The value is also pushed to [`linked-list`](../../../../types/core/llist/why2_list_t) for garbage collector.