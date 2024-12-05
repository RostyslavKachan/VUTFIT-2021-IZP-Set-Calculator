# Set Calculator (setcal)

## Project Overview
The **Set Calculator (setcal)** is a C-based application designed to perform fundamental mathematical operations on sets and binary relations. The program takes a text file as input, interprets the definitions of sets, relations, and commands, and outputs the results of operations directly to the console.

### Key Features
- **Set Operations**: Includes union, intersection, complement, subset verification, and more.
- **Relation Operations**: Supports checks for reflexivity, symmetry, transitivity, and additional relation properties.
- **Command-Based Processing**: Commands are executed sequentially from the input file, and results are printed in the same order.
- **Error Handling**: Provides robust checks for input validity, argument correctness, and command formatting.



## Building the Project
### Compilation
The program should be compiled with the following command:
```bash
gcc -std=c99 -Wall -Wextra -Werror setcal.c -o setcal
```
### Running the Program
Syntax
```bash
./setcal FILE
```


## Example Usage
### Input File (example.txt)
```bash
U Apple Banana Orange Peach
S Apple Banana
S Orange Peach
C union 2 3
C card 2
C subseteq 2 3
```
### Execution Command
```bash
./setcal example.txt
```
### Output
```bash
S Apple Banana Orange Peach
2
false
```
