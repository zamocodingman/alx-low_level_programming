# README Document

This README document provides a description of functions implemented in the project. The project includes functions for memory allocation, string concatenation, array creation, reallocation, and a multiplication program.

## Functions

- `malloc_checked`: Allocates memory using `malloc`. Returns pointer to allocated memory. If allocation fails, terminates process with status 98.

- `string_nconcat`: Concatenates two strings (`s1` and `s2`) and returns pointer to newly allocated space. Appends first `n` bytes of `s2` to `s1`. Returns `NULL` on failure. Treats `NULL` as empty string. 

- `calloc`: Allocates memory for an array using `malloc`. Initializes memory to zero. Returns pointer to allocated memory. Returns `NULL` if `nmemb` or `size` is 0 or if allocation fails.

- `array_range`: Creates an array of integers from `min` to `max`, inclusive. Returns pointer to newly created array. Returns `NULL` if `min > max` or if allocation fails.

- `realloc`: Reallocates memory block using `malloc` and `free`. Copies contents to newly allocated space. Returns pointer to reallocated memory. If `new_size > old_size`, added memory is uninitialized. Returns `ptr` without reallocation if `new_size == old_size`. If `ptr` is `NULL`, behaves like `malloc(new_size)`. If `new_size == 0` and `ptr` is not `NULL`, behaves like `free(ptr)` and returns `NULL`.

- Multiplication Program: Multiplies two positive numbers (`num1` and `num2`). Usage: `mul num1 num2`. Prints the result. Prints "Error" and exits with status 98 for incorrect arguments or non-digit characters. More than 5 functions can be used.

Refer to the individual function descriptions for more details.

## Conclusion

This README provides an overview of the functions implemented in the project, including their purpose and usage instructions. The project covers memory allocation, string manipulation, array creation, reallocation, and a multiplication program.
