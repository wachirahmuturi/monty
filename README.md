## Interpreter for Monty ByteCode files
> Monty ByteCode contains opcodes specific to Monty. This is an interpreter for
> these special opcodes: `push`, `pall`, `pint`, `pop`, `swap`, `swap`, `add`, `nop`

### Description of repo contents:
* bytecode folder ----- holds Monty ByteCode files
* monty.h ------------- holds all function prototypes for interpreter
* main.c -------------- entry into program

### How to Compile
Usage: ./monty [filename]
```
$ git clone https://github.com/wachirahmuturi/monty
$ cd monty
$ gcc -Wall -Werror -Wextra -pedantic *.c -o monty
$ ./monty bytecodes/000.m
```

### Environment
* Language: C (version C89)
* OS: Ubuntu 20.04 LTS
* Compiler: gcc (Ubuntu 9.4.0-1ubuntu1~20.04.1) 9.4.0
* Style guidelines: [Betty style](https://github.com/holbertonschool/Betty/wiki)
---
### Authors
Wachira James
