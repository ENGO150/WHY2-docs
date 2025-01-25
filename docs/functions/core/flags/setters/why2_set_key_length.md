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

# why2_set_key_length

## Parameters

| Identifier     | Data type |
| -------------- | --------- |
| `keyLengthNew` | `int`     |

## Attributes

|                     |                                                |
| ------------------  | ---------------------------------------------- |
| **Return type**     | `void`                                |
| **Header comment**  | *This functions doesn't have any description.* |
| **Added in commit** | [`2156aff370d8a223ff41882467d55ceb41d4f877`](https://github.com/ENGO150/WHY2/commit/2156aff370d8a223ff41882467d55ceb41d4f877) |

## Description

Sets `key_length`, which is used in `key` generation. Also works as minimal length of `key` passed in [`why2_encrypt_text`](../../../encrypter/why2_encrypt_text).