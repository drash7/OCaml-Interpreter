# OCaml-Interpreter

As part of Boston University's functional programming class, CS320, I developed a stack-based interpreter in OCaml, capable of simple arithmetic operations, boolean operations, relational operations, string manipulation, independent statement block execution, conditional execution, error handling, and functions.

## Commands

Pop: pop off the topmost value in the stack

Push: push a value onto the stack

Swap: swap the two topmost values in the stack

Add, Sub, Mul, Div, Rem: self-explanatory commands for arithmetic operations

Neg: negate the topmost value in the stack

And, Or, Not: self-explanatory commands for boolean operations

Lt, Lte, Gt, Gte, Eq: self-explanatory commands for relational operations

Cat: concatenate the top two values in the stack

Bnd: bind the topmost value to a name

Begin...End: marks an independent block of statements

If...Then...Else: conditional execution

Try...With: error handling; first, the try block is executed; if no error is found, the with block is skipped; otherwise, the partial output from the try block is let go, and 
then the with block is executed

Fun...EndFun: marks a function

Call: calls a function

Return: returns the topmost value from the stack generated from a function

Quit: quits the interpreter, and immediately outputs a file

## Values

Values in this interpreter can be integers, booleans (True/False), strings (alphanumeric characters within double quotes), or names (strings without quotes).

## Running

In order to run this interpreter, your system will need to have OCaml installed. More details about this can be found here: https://ocaml.org/docs/install.html
Once installed, you may either specify which input file to read from (from among the ones included in this repository), or you may create your own input file (in accordance with the acceptable grammar), and then specify where the output file will be stored.

## Contact
 
Daniel Sharvaaya Dash - daniel.s.dash@gmail.com
 
Project Link: https://github.com/drash7/OCaml-Interpreter
 
## Contributing
 
I greatly appreciate any contribitions.
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/CoolFeature`)
3. Commit your Changes (`git commit -m 'Add some CoolFeature'`)
4. Push to the Branch (`git push origin feature/CoolFeature`)
5. Open a Pull Request
