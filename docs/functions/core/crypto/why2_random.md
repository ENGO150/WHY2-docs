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

# why2_random

## Parameters

| Identifier | Data type |
| ---------- | --------- |
| `dest`     | `void *`  |
| `size`     | `size_t`  |

## Attributes

|                     |                                                          |
| ------------------  | -------------------------------------------------------- |
| **Return type**     | [`why2_bool`](../../../../types/core/flags/why2_bool.md) |
| **Header comment**  | `WRITE CRYPTO-SECURE RANDOM NUMBER INTO dest`            |
| **Added in commit** | [`f95608f52a0a82b3a8c005c7f8dad0b9cf93202a`](https://github.com/ENGO150/WHY2/commit/f95608f52a0a82b3a8c005c7f8dad0b9cf93202a) |

## Description

Function passes `dest` and `size` into [`RAND_bytes`](https://docs.openssl.org/1.1.1/man3/RAND_bytes) function and gets the output value. If output value is equal to `1`, returns `true`, otherwise `false`.

`dest` is where the output value should be stored, `size` sets the allowed size to write. Should be `sizeof(dest_datatype)`.