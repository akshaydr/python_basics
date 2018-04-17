# Decision making statements (if else)
Decision-making is the anticipation of conditions occurring during the execution of a program and specified actions taken according to the conditions.

Decision structures evaluate multiple expressions, which produce TRUE or FALSE as the outcome. You need to determine which action to take and which statements to execute if the outcome is TRUE or FALSE otherwise.

Note: Python programming language assumes any non-zero and non-null values as TRUE, and any zero or null values as FALSE value.

## if statement:
The if statement contains a logical expression using which data is compared and a decision is made based on the result of the comparison.
Syntax:
```python
if expression:
   statement(s)
```
Example:
```python
if True:
  print ("Statement is true")
```
Output:
```
Statement is True
```

## if else statement:
An else statement can be combined with an if statement. An else statement contains the block of code that executes if the conditional expression in the if statement resolves to 0 or a FALSE value.
Syntax:
```python
if expression1:
   statement(s)
elif expression2:
   statement(s)
elif expression3:
   statement(s)
else:
   statement(s)
```
Example:
```python
a = 10

if a == 10:
   print ("A is 10")
elif a == 15:
  print ("A is 15")
```
Output:
`A is 10`


## nested if statement:
There may be a situation when you want to check for another condition after a condition resolves to true. In such a situation, you can use the nested if construct. In a nested if construct, you can have an if...elif...else construct inside another if...elif...else construct.
Syntax:
```python
if expression1:
   statement(s)
   if expression2:
      statement(s)
   elif expression3:
      statement(s)
   else:
      statement(s)
   elif expression4:
      statement(s)
else:
   statement(s)
```
Example:
```python
a = 10
b = 20

if a == 10:
  print ("A is 10 ")
  if (b == 20):
    print ("and B is 20")
elif a === 15:
  print ("A is not 10")
```
Output:
`A is 10 and B is 20`
