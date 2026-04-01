# ParrotJRCompiler
Implementation of a simple Java-based language that performs simple arithmetic and logical operations. WARNING: The language compiler contains bugs and errors that may prevent some operations from being performed or may perform them incorrectly. The project was originally conceived as a one-time project and is not subject to further development.

Language commands:
VARIABLE DECLARATION

Cookie = new name(number) – declares an integer variable

Cookie* = new name(number) – declares a real variable

Word of Parrot = new name("text") – declares a string variable

ASSIGNMENT OF VALUES

Cookie = name = expression – changes the value of a numeric variable (supports +, -, *, /)

DATA INPUT

Parrot ask = new name – input an integer from the keyboard

Parrot ask* = new name – input a real number from the keyboard

Parrot ask text = new name – input text from the keyboard

OUTPUT DATA

Parrot do: expression – output the value of a variable or the result of an expression

Parrot say: "text" – output text

Parrot say: "text", id:0 – output text in color (0-green, 1-blue, 2-red, 3-yellow, 4-light blue)

 CONDITIONAL OPERATOR

if condition { ... } – conditional execution of a code block (supports >, <, >=, <=, ==)

LOOP

while condition { ... } – loop with precondition

for variable from start to end { ... } – loop with a counter

GRAPHICAL INTERFACE

Parrot web: create Pane = name – create a graphical window

Parrot webUp name = "title" – set the window title

Parrot web: start name – start displaying the window

NOTES

All commands are written in separate lines

Condition and loop bodies are enclosed in curly brackets {}

Strings are enclosed in double quotes ""

Arithmetic expressions support +, -, *, and / operations
