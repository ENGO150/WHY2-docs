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
| [`why2_seeded_random`](./core/crypto/why2_seeded_random) | Generate random number based on seed passed in why2_seed_random |

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
| [`why2_get_flags`](./core/flags/getters/why2_get_flags) | Returns used flags                                            |
| [`why2_no_output`](./core/flags/getters/why2_no_output) | Same as why2_get_default_flags() but for why2_output_flags    |
| [`why2_get_encryption_operation`](./core/flags/getters/why2_get_encryption_operation) | Returns functions which is used for encryption & decryption |
| [`why2_get_flags_changed`](./core/flags/getters/why2_get_flags_changed) | *This functions doesn't have any description.* |
| [`why2_get_padding_changed`](./core/flags/getters/why2_get_padding_changed) | *This functions doesn't have any description.* |
| [`why2_get_memory_identifier`](./core/flags/getters/why2_get_memory_identifier) | Returns string used in linked list (in memory.c) for identifying nodes when running garbage collector |
| [`why2_get_default_memory_identifier`](./core/flags/getters/why2_get_default_memory_identifier) | *This functions doesn't have any description.* |

#### Setters

| Function                                                              | Description                                       |
| --------------------------------------------------------------------- | ------------------------------------------------- |
| [`why2_set_encryption_separator`](./core/flags/setters/why2_set_encryption_separator) | *This functions doesn't have any description.* |
| [`why2_set_key_length`](./core/flags/setters/why2_set_key_length) | *This functions doesn't have any description.* |
| [`why2_set_flags`](./core/flags/setters/why2_set_flags) | *This functions doesn't have any description.* |
| [`why2_set_encryption_operation`](./core/flags/setters/why2_set_encryption_operation) | *This functions doesn't have any description.* |
| [`why2_set_memory_identifier`](./core/flags/setters/why2_set_memory_identifier) | *This functions doesn't have any description.* |
| [`why2_set_padding`](./core/flags/setters/why2_set_padding) | Set padding rate without rewriting input flags |
| [`why2_reset_memory_identifier`](./core/flags/setters/why2_reset_memory_identifier) | *This functions doesn't have any description.* |

### Linked-list

| Function                                                      | Description                         |
| ------------------------------------------------------------- | ----------------------------------- |
| [`why2_list_push`](./core/llist/why2_list_push)               | Push element to list back           |
| [`why2_list_push_at`](./core/llist/why2_list_push_at)         | Push element to index index of list |
| [`why2_list_remove`](./core/llist/why2_list_remove)           | Remove element                      |
| [`why2_list_remove_at`](./core/llist/why2_list_remove_at)     | Remove element with index index     |
| [`why2_list_remove_back`](./core/llist/why2_list_remove_back) | Remove last element                 |
| [`why2_list_find`](./core/llist/why2_list_find)               | Find element in list                |
| [`why2_list_get_size`](./core/llist/why2_list_get_size)       | Get size                            |
| [`why2_list_reverse`](./core/llist/why2_list_reverse)         | Reverses list                       |

### Memory

| Function                                               | Description                                                |
| ------------------------------------------------------ | ---------------------------------------------------------- |
| [`why2_malloc`](./core/memory/why2_malloc)             | *This functions doesn't have any description.*             |
| [`why2_calloc`](./core/memory/why2_calloc)             | *This functions doesn't have any description.*             |
| [`why2_realloc`](./core/memory/why2_realloc)           | This doesn't preserve content of pointer!                  |
| [`why2_recalloc`](./core/memory/why2_recalloc)         | Same as why2_realloc but fills the pointer with null-terms |
| [`why2_strdup`](./core/memory/why2_strdup)             | *This functions doesn't have any description.*             |
| [`why2_fopen`](./core/memory/why2_fopen)               | *This functions doesn't have any description.*             |
| [`why2_fdopen`](./core/memory/why2_fdopen)             | *This functions doesn't have any description.*             |
| [`why2_opendir`](./core/memory/why2_opendir)           | *This functions doesn't have any description.*             |
| [`why2_deallocate`](./core/memory/why2_deallocate)     | *This functions doesn't have any description.*             |
| [`why2_clean_memory`](./core/memory/why2_clean_memory) | identifier specifies which nodes to deallocate \| this is basically garbage collector \| pass why2_get_default_memory_identifier() for deallocating everything |
| [`why2_allocated`](./core/memory/why2_allocated)       | Checks if pointer was allocated using why2-mem             |

## Logger

## Chat