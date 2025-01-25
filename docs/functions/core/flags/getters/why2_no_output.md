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

# why2_no_output

## Parameters

| Identifier  | Data type                                                              |
| ----------- | ---------------------------------------------------------------------- |
| `exit_code` | [`enum WHY2_EXIT_CODES`](../../../../enums/core/flags/why2_exit_codes) |

## Attributes

|                     |                                                                       |
| ------------------  | --------------------------------------------------------------------- |
| **Return type**     | [`why2_output_flags`](../../../../types/core/flags/why2_output_flags) |
| **Header comment**  | `SAME AS why2_get_default_flags() BUT FOR why2_output_flags`          |
| **Added in commit** | [`c5de589fff870bbd8cf428465ea4e73caa3e8b38`](https://github.com/ENGO150/WHY2/commit/c5de589fff870bbd8cf428465ea4e73caa3e8b38) |

## Description

Returns empty `output_flags` with `exit_code`.