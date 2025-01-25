---
title: why2_get_encryption_operation function
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

# why2_get_encryption_operation

## Parameters

*This functions doesn't take any parameters.*

## Attributes

|                     |                                                                                             |
| ------------------  | ------------------------------------------------------------------------------------------- |
| **Return type**     | [`why2_encryption_operation_cb`](../../../../types/core/flags/why2_encryption_operation_cb) |
| **Header comment**  | `RETURNS FUNCTION WHICH IS USED FOR ENCRYPTION & DECRYPTION`                                |
| **Added in commit** | [`2a09a38acf48f0e57beb5135ab7f1fdb18e088fa`](https://github.com/ENGO150/WHY2/commit/2a09a38acf48f0e57beb5135ab7f1fdb18e088fa) |

## Description

Returns callback to `encryption_operation`, which is used during encryption/decryption for final string manipulation.