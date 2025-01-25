---
title: why2_set_encryption_separator function
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

# why2_set_encryption_separator

## Parameters

| Identifier                    | Data type |
| ----------------------------- | --------- |
| `encryption_separator_new`    | `char`    |

## Attributes

|                     |                                                |
| ------------------  | ---------------------------------------------- |
| **Return type**     | `void`                                         |
| **Header comment**  | *This functions doesn't have any description.* |
| **Added in commit** | [`1a5b58edf99547ba32fb047e80fb179f315182b9`](https://github.com/ENGO150/WHY2/commit/1a5b58edf99547ba32fb047e80fb179f315182b9) |

## Description

Sets `encryption_separator`, which is used in encryption/decryption for separating chars.

---

```
104'-100'10306'-110'87
```

Example above uses `'` as `encryption_separator`.