---
title: why2_reset_memory_identifier function
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

# why2_reset_memory_identifier

## Parameters

*This functions doesn't take any parameters.*

## Attributes

|                     |                                                |
| ------------------  | ---------------------------------------------- |
| **Return type**     | `void`                                         |
| **Header comment**  | *This functions doesn't have any description.* |
| **Added in commit** | [`70335e67ad3e7ef3bc693741a03cb91962b91863`](https://github.com/ENGO150/WHY2/commit/70335e67ad3e7ef3bc693741a03cb91962b91863) |

## Description

Resets string, used in garbage collector for identifying (separating) nodes, to default.

Every allocation has its own ID, which is set to lastly used `memory_identifier`. This separates allocations in code to blocks and you can run GC with the `memory_identifier` to deallocate those blocks.