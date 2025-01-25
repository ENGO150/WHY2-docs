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

# Functions

You can find documentation for every *public* function of WHY2 below.

## Core

### Crypto.h

| Function                                                | Description                                      |
| ------------------------------------------------------- | ------------------------------------------------ |
| [`why2_sum_segment`](./core/crypto/why2_sum_segment) | Calculate SUM++ for input; Used for padding seed |
| [`why2_random`](./core/crypto/why2_random)           | Write crypto-secure random number into dest      |
| [`why2_seed_random`](./core/crypto/why2_seed_random) | Seed why2_seeded_random output                   |
| [`why2_seeded_random`](./core/crypto/why2_seeded_random) | GENERATE RANDOM NUMBER BASED ON SEED PASSED IN why2_seed_random |

## Logger

## Chat