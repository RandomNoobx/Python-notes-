# Functions :
A reusable piece of code is called a function.

## Types of Functions :

i. Pre-built functions such as print(), input(), int(), float(), etc.
ii. Functions that we ourselves design.
The names of the functions we create are considered new reserved words.

In Python a function is some reusable code that takes arguments as input, does some computation, and then returns a result.

We define a function using the def reserved word

We call/invoke the function by using the function name, parentheses, and arguments in an expression .

## Creating a Function :

We create a new function using the def keyword followed by optional parameters in parentheses

We indent the body of the function

This defines the function but does not execute the body of the function.

Once we create a function, we can invoke it as many times as we wish.

Ex :

x = 5

print('Hello')

def print_lyrics():

   print("I'm a lumberjack, and I'm okay.")

   print('I sleep all night and I work all day.')

print('Yo')

print_lyrics()

x = x + 2

print(x)

Hello
Yo
I'm a lumberjack, and I'm okay.
I sleep all night and I work all day.
7

## Arguments :

An argument is a value passed into a function, serving as its input

We use arguments so we can direct the function to do different kinds of work when we call it at different times

We put the arguments in parentheses after the name of the function.

Ex :

big = max('Hello world')
Name of function = max
Argument = Hello World

## Parameters :

A parameter is a variable used in the same statement in which we define a function.

It is a “handle” that allows the code in the function to access the arguments for a particular function invocation.

Ex :

def greet(lang): # function = greet ; parameter = lang ; es, fr = arguments.

if lang == 'es':
print('Hola')

elif lang == 'fr':
print('Bonjour')

else:
print('Hello')

greet('en')

Hello

greet('es')

Hola

greet('fr')

Bonjour

Often a function will take its arguments, do some computation, and return a value to be used as the value of the function call in the calling expression. The return keyword is used for this.

Ex :

def greet():
 return "Hello"

print(greet(), "Glenn")
print(greet(), "Sally")

Hello Glenn
Hello Sally

A fruitful function is one that produces a result (or return value)
A void function is one that doesn't produce a result (or return value).

The return statement ends the function execution and “sends back” the result of the function.
