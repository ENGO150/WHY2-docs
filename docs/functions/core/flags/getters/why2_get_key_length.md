---
title: why2_get_key_length function
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

# why2_get_key_length

## Parameters

*This functions doesn't take any parameters.*

## Attributes

|                     |                                                |
| ------------------  | ---------------------------------------------- |
| **Return type**     | `unsigned long`                                |
| **Header comment**  | *This functions doesn't have any description.* |
| **Added in commit** | [`e85a14b2530d6c8a39be946f691a0f9047d38f73`](https://github.com/ENGO150/WHY2/commit/e85a14b2530d6c8a39be946f691a0f9047d38f73) |

## Description

Returns `key_length`, which is used in `key` generation. Also works as minimal length of `key` passed in [`why2_encrypt_text`](../../../encrypter/why2_encrypt_text).