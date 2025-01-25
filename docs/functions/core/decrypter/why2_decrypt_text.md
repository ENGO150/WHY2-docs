---
title: why2_decrypt_text function
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

# why2_decrypt_text

## Parameters

| Identifier | Data type |
| ---------- | --------- |
| `text`     | `char *`  |
| `key`      | `char *`  |

## Attributes

|                     |                                                                       |
| ------------------  | --------------------------------------------------------------------- |
| **Return type**     | [`why2_output_flags`](../../../../types/core/flags/why2_output_flags) |
| **Header comment**  | `TEXT from WILL BE DECRYPTED WITH KEY AND RETURNED`                   |
| **Added in commit** | [`d9a99b985105b99b3ef237597f8ea91a751b89f1`](https://github.com/ENGO150/WHY2/commit/d9a99b985105b99b3ef237597f8ea91a751b89f1) |

## Description

Function removes padding (if present) from `text` using `key`, decrypts and returns output in [`why2_output_flags`](../../../../types/core/flags/why2_output_flags) among with some run data.

Encryption/Decryption functions are using settings from [`why2_input_flags`](../../../../types/core/flags/why2_input_flags). You can set those using [`why2_set_flags`](../../../../functions/core/flags/why2_set_flags).