# Little Assembler Games for 8086 processor.
The source code use Intel syntax and must be assembled with FASM (Flat Assembler).
FASM is an open source assembly language compiler for 8086, 80x86 and 80x86 processores and can be found here: https://flatassembler.net/
---
## Game List
| # | Game                   |File       | Format     | Platform  | Build command |
|---|------------------------|-----------|------------|-----------|---------------
| 1 | Tic Tac Toe            | ttt.asm   | 16bits exe |DOS        | `make ttt`    |
| 2 | Pong                   | pong.asm  | 16bits com |DOS        | `make pong`   |

## Running
Since those games are 16bits programs, and use special DOS interrupts, you will need a DOS machine to run them. Games are tested within [DosBox](http://www.dosbox.com/) and the makefile has an entry to run it fom command line. Once you have DosBox and a make util, just type `make run`.

## Assembly
The complete instruction set for 8086 microprocessor can be found [here]( http://www.electronics.dit.ie/staff/tscarff/8086_instruction_set/8086_instruction_set.html).
