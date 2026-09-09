# Conditional Execution 

Ex :

Program:
x = 5
if x < 10:
 print('Smaller')
if x > 20:
 print('Bigger')
print('Finis')

Output :
Smaller Finis

## Comparison Operators :

< , <= , == , >= , > , !=

Boolean operators : ask a question and produce a yes or no result.

Comparison operators look at variables but do not change them.

## Indentation :

Increase indent after an if statement or for statement (after : )

Maintain indent to indicate the scope of the block (which lines are affected
by the if/for)

Reduce indent back to the level of the if statement or for statement to
indicate the end of the block

Blank lines are ignored ; they do not affect indentation

Comments on a line by themselves are ignored with regard to indentation.

## Try/Except Structure :

You surround a dangerous section of code with try and except

If the code in the try works - the except is skipped

If the code in the try fails - it jumps to the except section.

