# Python Loops:

## While Loops:
A while loop statement in Python programming language repeatedly executes a target statement as long as a given condition is true.
Syntax:
```python
while expression:
   statement(s)
```
Example:
```python
count = 0
while (count < 9):
   print ('The count is:', count)
   count = count + 1

print ("Good bye!")
```
Output:
```
The count is: 0
The count is: 1
The count is: 2
The count is: 3
The count is: 4
The count is: 5
The count is: 6
The count is: 7
The count is: 8
Good bye!
```

## For Loops:
It has the ability to iterate over the items of any sequence, such as a list or a string. If a sequence contains an expression list, it is evaluated first. Then, the first item in the sequence is assigned to the iterating variable iterating_var. Next, the statements block is executed. Each item in the list is assigned to iterating_var, and the statement(s) block is executed until the entire sequence is exhausted.
Syntax:
```python
for iterating_var in sequence:
   statements(s)
```
Example:
```python
for letter in 'Python':     # traversal of a string sequence
   print ('Current Letter :', letter)
print()
fruits = ['banana', 'apple',  'mango']
for fruit in fruits:        # traversal of List sequence
   print ('Current fruit :', fruit)

print ("Good bye!")
```
Output:
```
Current Letter : P
Current Letter : y
Current Letter : t
Current Letter : h
Current Letter : o
Current Letter : n

Current fruit : banana
Current fruit : apple
Current fruit : mango
Good bye!
```

## Nested Loops:
Python programming language allows to use one loop inside another loop. Following section shows few examples to illustrate the concept.
```python
for iterating_var in sequence:
   for iterating_var in sequence:
      statements(s)
   statements(s)
# Or
while expression:
   while expression:
      statement(s)
   statement(s)
```
Example:
```python
import sys
for i in range(1,11):
   for j in range(1,11):
      k=i*j
      print (k, end=' ')
   print()
```
Output:
```
1 2 3 4 5 6 7 8 9 10
2 4 6 8 10 12 14 16 18 20
3 6 9 12 15 18 21 24 27 30
4 8 12 16 20 24 28 32 36 40
5 10 15 20 25 30 35 40 45 50
6 12 18 24 30 36 42 48 54 60
7 14 21 28 35 42 49 56 63 70
8 16 24 32 40 48 56 64 72 80
9 18 27 36 45 54 63 72 81 90
10 20 30 40 50 60 70 80 90 100
```
