# Monty Interpreter


## *INTRODUCTION*

Monty 0.98 is a scripting language that is first compiled into Monty byte codes.
It relies on a unique stack with specific instructions to manipulate it.
By convention, the files containing Monty bytecodes have the *.m* extension. There is no more than one instruction per line  and there can be any number of spaces before or after the opcode and its argument.

## Monty byte code file

Monty byte code files can contain blank lines (empty or made of spaces only and any additional text after the opcode or its required argument is not taken into account:

