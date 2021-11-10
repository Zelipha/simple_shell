# 0x16. C - Simple Shell
A simple UNIX command line interpreter. It gathers input from userand executes programs based on that input. When the program finishes executing, it displays that programs output.

## Invocation
To invoke hsh, compile all `.c` files in the repository and run the resulting executable:
`gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
./hsh`
**hsh** can be invoked both interactively and non-interactively. If **hsh** is invoked with standard input not connected to a terminal, it reads and executes received commands in order.