# PythonResources

PYTHON CHEAT SHEET
> B A S I C S
## Print
Prints a string into the console. 
```Python
print("Hello World")
```
## Input
Prints a string into the console,
and asks the user for a string input.
```Python
input("What's your name")
```
## Comments
Adding a # symbol in font of text
lets you make comments on a line of code.
The computer will ignore your comments.
```Python
#This is a comment
print("This is code")
```
## Variables
A variable give a name to a piece of data.
Like a box with a label, it tells you what's
inside the box.
```Python
my_name = "Beta-23"
my_age = 12
```
## The += Operator
This is a convient way of saying: "take the
previous value and add to it.
```Python
my_age = 12
my_age += 4
#my_age is now 16
```
> D A T A  T Y P E S
## Integers 
Integers are whole numbers. 
```Python
my_number = 354
```
## Floating Point Numbers 
Floats are numbers with decimal places. When you do a calculation that results in a fraction e.g. 4 ÷ 3 the result will always be a floating point number. 
```Python
my_float = 3.14159
```
## Strings 
A string is just a string of characters. It should be surrounded by double quotes. 
```Python
my_string = "Hello"
```
## String Concatenation 
You can add strings to string to create a new string. This is called concatenation. It results in a new string. 
```Python
"Hello" + "Angela" 
#becomes "HelloAngela" 
```
## Escaping a String 
Because the double quote is special, it denotes a string, if you want to use it in a string, you need to escape it with a -> \ 
```Python
speech = "She said: \"Hi\"" 
print(speech) 
#prints: She said: "Hi"
```
## F-Strings
You can insert a variable into a string
using f-strings.
The syntax is simple, just insert the variable
in-between a set of curly braces {}.
```Python
days = 365
print(f"There are {days}
in a year")
```
## Converting Data Types
You can convert a variable from 1 data
type to another.
Converting to float:
float()
Converting to int:
int()
Converting to string:
str()
```Python
n = 354
new_n = float(n)
print(new_n) #result 354.0
```

## Checking Data Types
You can use the type() function
to check what is the data type of a
particular variable.
```Python
n = 3.14159
type(n) #result float
```
> M A T H S

## Arithmetic Operators
You can do mathematical calculations with
Python as long as you know the right
operators.
```Python
3+2 #Addition
4-1 #Subtract
2*3 #Multiply
5/2 #Divide
5**2 #Exponent
```

## The += Operator
This is a convenient way to modify a variable.
It takes the existing value in a variable
and adds to it.
You can also use any of the other
mathematical operators e.g. -= or *=
```Python
my_number = 4
my_number += 2
#result is 6
```

## The Modulo Operator
Often you'll want to know what is the
remainder after a division.
e.g. 4 ÷ 2 = 2 with no remainder
but 5 ÷ 2 = 2 with 1 remainder
The modulo does not give you the result
of the division, just the remainder.
It can be really helpful in certain situations,
e.g. figuring out if a number is odd or even.
```Python
5 % 2
#result is 1
```

> E R R O R S

## Syntax Error
Syntax errors happen when your code
does not make any sense to the computer.
This can happen because you've misspelt
something or there's too many brackets or
a missing comma.
```Python
print(12 + 4))
File "<stdin>", line 1
 print(12 + 4))
              ^
SyntaxError: unmatched ')'
```

## Name Error
This happens when there is a variable
with a name that the computer
does not recognise. It's usually because
you've misspelt the name of a variable
you created earlier.
Note: variable names are case sensitive!
```Python
my_number = 4
my_Number + 2
Traceback (most recent call
last): File "<stdin>", line 1,
NameError: name 'my_Number'
is not defined
```

## Zero Division Error
This happens when you try to divide by zero,
This is something that is mathematically
impossible so Python will also complain.
```Python
5 % 0
Traceback (most recent call
last): File "<stdin>", line 1,
ZeroDivisionError: integer
division or modulo by zero
```

> F U N C T I O N S
## Creating Functions
This is the basic syntax for a function in
Python. It allows you to give a set of
instructions a name, so you can trigger it
multiple times without having to re-write
or copy-paste it. The contents of the function
must be indented to signal that it's inside.
```Python
def my_function():
print("Hello")
name = input("Your name:")
print("Hello")
```

## Calling Functions
You activate the function by calling it.
This is simply done by writing the name of
the function followed by a set of round
brackets. This allows you to determine
when to trigger the function and how
many times.
```Python
my_function()
my_function()
#The function my_function
#will run twice.
```

