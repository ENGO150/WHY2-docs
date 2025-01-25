---
title: why2_clean_memory function
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

# why2_clean_memory

## Parameters

| Identifier   | Data type |
| ------------ | --------- |
| `identifier` | `char *`  |

## Attributes

|                     |                                                |
| ------------------  | ---------------------------------------------- |
| **Return type**     | `void`                                         |
| **Header comment**  | `identifier SPECIFIES WHICH NODES TO DEALLOCATE | THIS IS BASICALLY GARBAGE COLLECTOR | PASS why2_get_default_memory_identifier() FOR DEALLOCATING EVERYTHING` |
| **Added in commit** | [`abbd82077821c3b06720212ca89f5d9438500a48`](https://github.com/ENGO150/WHY2/commit/abbd82077821c3b06720212ca89f5d9438500a48) |

## Description

This is basically a garbage collector.

Function [deallocates](../why2_deallocate) all memory allocated with WHY2-memory, with ID `identifier`. You can pass `why2_get_default_memory_identifier()` as `identifier` to deallocate all memory.