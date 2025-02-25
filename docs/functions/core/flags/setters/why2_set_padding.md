---
title: why2_set_padding function
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

# why2_set_padding

## Parameters

| Identifier              | Data type        |
| ----------------------- | ---------------- |
| `new_memory_identifier` | `unsigned long`  |

## Attributes

|                     |                                                  |
| ------------------  | ------------------------------------------------ |
| **Return type**     | `void`                                           |
| **Header comment**  | `SET PADDING RATE WITHOUT REWRITING INPUT FLAGS` |
| **Added in commit** | [`0fe3f47752c574c317da8dbb9db53af9a101212a`](https://github.com/ENGO150/WHY2/commit/0fe3f47752c574c317da8dbb9db53af9a101212a) |

## Description

Sets `padding` without messing with [`input_flags`](../../../../types/core/flags/why2_input_flags).