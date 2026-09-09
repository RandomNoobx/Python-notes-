# Variables :

A variable is a named place in the memory where a programmer can store
data and later retrieve the data using the variable name.
You can change the contents of a variable in a later statement. 
Ex :
x = 10
y = 15
x = 20

A variable name must start with a letter or underscore.
A variable name can only contain letters, numbers and underscores.
Variable names are case sensitive.

# Expressions :

## Numerical Expressions :

Addition = +

Subtraction = -

Multiplication = *

Division = /

Power = **

Floor Division = //

Remainder = %

## Operator Precedence Rules { When multiple operators are used } :

Highest precedence rule to lowest precedence rule:

Parentheses are always respected

Exponentiation (raise to a power)

Multiplication, Division, Floor Division, and Remainder

Addition and Subtraction

Left to right

Ex : x = 1 + 2 ** 3 / 4 * 5
print (x) 
11.0

## Type :

In Python variables, literals, and constants have a “type”.
Python knows the difference between an integer number and a string.

 Ex :

>>> ddd = 1 + 4
>>> print(ddd)
5
>>> eee = 'hello ' + 'there'
>>> print(eee)
hello there

We can find out what type something is by using the type() function.

## Types of Numbers :

Whole numbers : No decimal point { 0 , 1 , 100 }.

Floating point numbers : Have a decimal point { 0.0 , 14.0 , 25.6 }.

Other number types are variations of whole and floating point numbers.

## Type Conversions :

When we put an integer and a floating point number in the same expression, the integer is implicitly converted to a float.

Ex :

>>> print(float(99) + 100)
199.0
>>> i = 42
>>> type(i)
<class'int'>
>>> f = float(i)
>>> print(f)
42.0
>>> type(f)
<class'float'>
>>>

## Division :

Dividing integers and floating point numbers using the / operator always gives a float as a result. { even if both numbers are integers }

## Floor Division :

Division using the // operator gives the result rounded down to the nearest integer as a float.

Ex :

>>> print(10 // 2)
5.0
>>> print(9 // 2)
4
>>> print(99 // 100)
0
>>> print(-7.0 // 2.0)
-4.0
>>> print(7.0 // 2.0)
3.0
>>> print(5 // 2)
2

## String Conversions :

You can also use int() and float() to convert between strings and integers

Ex :

>>> sval = '123'
>>> type(sval)
<class 'str'>
>>> print(sval + 1)
Traceback (most recent call last):
 File "<stdin>", line 1, in <module>
TypeError: can only concatenate str
(not "int") to str
>>> ival = int(sval)
>>> type(ival)
<class 'int'>
>>> print(ival + 1)
124

## User Input :

We can instruct Python to pause and read data from the user using the input() function.
The input() function returns a string.

Ex :

name = input('Who are you? ')
print('Welcome', name)
Who are you? Chuck
Welcome Chuck

## Reading User Input :

If we want to read a number from the user, we must convert it from a string to a number using a type conversion function.

Ex :

floor = input('Europe floor?')
us_floor = int(floor) + 1
print('US floor', us_floor)

## Comments in Python :

Anything after a ' # ' is ignored in python. { Like // in c }
