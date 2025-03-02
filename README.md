# ft_printf

## 📌 Project Description
The `ft_printf` project aims to replicate the behavior of the standard `printf` function from the C standard library. The project consists of creating a custom version, `ft_printf`, which handles formatted output.

The function prototype is:
```c
int ft_printf(const char *, ...);
```

## 🚀 Compilation
To compile the project, run:
```sh
make
```
This will create the `libftprintf.a` library.

To clean object files:
```sh
make clean
```
To remove compiled files:
```sh
make fclean
```
To recompile from scratch:
```sh
make re
```

## ⚙️ Supported Format Specifiers
The `ft_printf` function supports the following format specifiers:

| Specifier | Description |
|-----------|-------------|
| `%c` | Prints a single character |
| `%s` | Prints a string |
| `%p` | Prints a pointer address in hexadecimal format |
| `%d` | Prints a decimal (base 10) number |
| `%i` | Prints an integer (base 10) |
| `%u` | Prints an unsigned decimal number |
| `%x` | Prints a hexadecimal number (lowercase) |
| `%X` | Prints a hexadecimal number (uppercase) |
| `%%` | Prints a percent sign |

## 🔍 Features
- Mimics the behavior of the real `printf`.
- Handles variable argument lists using `va_start`, `va_arg`, `va_copy`, and `va_end`.
- Does not use buffer management.
- Built as a static library (`libftprintf.a`).
- Can be linked with other projects.

## 🛠️ Usage
You can test `ft_printf` by using it instead of the original printf.

## 📜 License
This project follows the [42 School](https://42.fr/) project requirements and is meant for educational purposes.
