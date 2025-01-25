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

### Crypto

| Function                                             | Description                                      |
| ---------------------------------------------------- | ------------------------------------------------ |
| [`why2_sum_segment`](./core/crypto/why2_sum_segment) | Calculate SUM++ for input; Used for padding seed |
| [`why2_random`](./core/crypto/why2_random)           | Write crypto-secure random number into dest      |
| [`why2_seed_random`](./core/crypto/why2_seed_random) | Seed why2_seeded_random output                   |
| [`why2_seeded_random`](./core/crypto/why2_seeded_random) | GENERATE RANDOM NUMBER BASED ON SEED PASSED IN why2_seed_random |

### Decrypter

| Function                                                  | Description                                       |
| --------------------------------------------------------- | ------------------------------------------------- |
| [`why2_decrypt_text`](./core/decrypter/why2_decrypt_text) | Text from will be decrypted with key and returned |

### Encrypter

| Function                                                  | Description                                       |
| --------------------------------------------------------- | ------------------------------------------------- |
| [`why2_encrypt_text`](./core/encrypter/why2_encrypt_text) | Text from will be encrypted with key and returned |

### Flags

#### Getters

| Function                                                                      | Description                             |
| ----------------------------------------------------------------------------- | --------------------------------------- |
| [`why2_get_encryption_separator`](./core/flags/getters/why2_get_encryption_separator) | *This functions doesn't have any description.* |
| [`why2_get_key_length`](./core/flags/getters/why2_get_key_length) | *This functions doesn't have any description.*      |
| [`why2_get_default_flags`](./core/flags/getters/why2_get_default_flags) | This generates why2_input_flags with default values |

## Logger

## Chat