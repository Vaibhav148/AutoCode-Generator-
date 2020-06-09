# AutoCode-Generator-
It converts input Pseudo-code (Algorithm) into C Source code using flex and bison.

### Sample input and output :

<img src= "/screenshots/output.png" >

### How to run :
- Clone this repo
```
$ git clone https://github.com/Vaibhav148/AutoCode-Generator-
$ cd AutoCode-Generator-
```
- Install dependencies
```
$ sudo apt-get install flex
$ sudo apt-get install bison
```
- provide algorithm input in input.txt as per predefined format (Refer to sample-inputs to know the format for providing inputs)
- Finally run lex and yacc files.
```
$ lex codegen_lex.l
$ yacc -d codegen_yacc.y
$ cc lex.yy.c y.tab.c -ll -ly
$ ./a.out
```
