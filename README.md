# Introduction to Python:

## What is it...??
Its a general-purpose interactive, object-oriented and high-level programming language. It was created by Guido van Rossum during 1985- 1990. Like Perl, Python source code is also available under the GNU General Public License (GPL). It is a very simple language, and has a very straightforward syntax. 

First thing we do while learning any language is try “Hello World..!”
## Python Interpreter:
```python
Python 2.7.12 (default, Dec  4 2017, 14:50:18) 
[GCC 5.4.0 20160609] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

Type the below code to get output as **Hello World**

```python
print “Hello World”
```

## Python Features:
* Easy to learn
* Easy to read
* Easy to maintain 
* A broad standard library
* Interactive mode
* Portable
* Extendable
* Easily integrated

## Python Syntax and rules:
### Indentation:
Python provides no braces to indicate blocks of code for class and function definitions or flow control. Blocks of code are denoted by line indentation, which is rigidly enforced. The number of spaces in the indentation is variable, but all statements within the block must be indented the same amount.
Example:

```python
if True:
    print "Inside if statement...!!"
else:
    print "Inside else statement...!!"
```

### Comments:
A hash sign (#) begins a comment.
```python
# Comment 
print "Hello" #Comment which is not printed on output screen after Hello
```

### Variable declaration:
Not necessary to mention datatype during declaration of a variable.
```python
x = 10 #integer type
y = 10.0 #Floating type
name = "Python" #String type
```
##### Output:
```python
10
10.0
Python
```

### Standard Datatypes:
* Numbers
* String
* Lists
* Tuple
* Dictionary

#### Numbers:
Four Different type of numerical types:
* int (Signed integer)
* long (long integers)
* float (Floating point real values)
* complex (complex numbers)

#### Strings:
Python allows for either pairs of single or double quotes. Subsets of strings can be taken using the slice operator ([ ] and [:] ) with indexes starting at 0 in the beginning of the string and working their way from -1 at the end.
String concatenation is very easy. Its just with (+) sign. 
Example:
```Python
str = 'Hello World!'

print str          # Prints complete string
print str[0]       # Prints first character of the string
print str[2:5]     # Prints characters starting from 3rd to 5th
print str[2:]      # Prints string starting from 3rd character
print str * 2      # Prints string two times
print str + "TEST" # Prints concatenated string
```
##### Output:
```
Hello World!
H
llo
llo World!
Hello World!Hello World!
Hello World!TEST
```
#### Lists:
Lists are the most versatile of Python's compound data types. A list contains items separated by commas and enclosed within square brackets ([]). To some extent, lists are similar to arrays in C. One difference between them is that all the items belonging to a list can be of different data type.
Example:
```python
list = [ 'abcd', 786 , 2.23, 'john', 70.2 ]
tinylist = [123, 'john']

print list          # Prints complete list
print list[0]       # Prints first element of the list
print list[1:3]     # Prints elements starting from 2nd till 4th 
print list[2:]      # Prints elements starting from 3rd element
```
##### Output:
```
['abcd', 786, 2.23, 'john', 70.200000000000003]
abcd
[786, 2.23]
[2.23, 'john', 70.200000000000003]
```
#### Tuples:
A tuple is another sequence data type that is similar to the list. A tuple consists of a number of values separated by commas. Unlike lists, however, tuples are enclosed within parentheses. The main differences between lists and tuples are: Lists are enclosed in brackets ( [ ] ) and their elements and size can be changed, while tuples are enclosed in parentheses ( ( ) ) and cannot be updated. 
```python
tuple = ( 'abcd', 786 , 2.23, 'john', 70.2  )
tinytuple = (123, 'john')

print tuple           # Prints complete list
print tuple[0]        # Prints first element of the list
print tuple[1:3]      # Prints elements starting from 2nd till 3rd 
print tuple[2:]       # Prints elements starting from 3rd element
print tinytuple * 2   # Prints list two times
```
##### Output:
```
('abcd', 786, 2.23, 'john', 70.200000000000003)
abcd
(786, 2.23)
(2.23, 'john', 70.200000000000003)
(123, 'john', 123, 'john')
```

#### Dictionary:
Python's dictionaries are kind of hash table type. They work like associative arrays or hashes found in Perl and consist of key-value pairs. A dictionary key can be almost any Python type, but are usually numbers or strings. Values, on the other hand, can be any arbitrary Python object. Dictionaries are enclosed by curly braces ({ }) and values can be assigned and accessed using square braces ([]).
Example:
```python
dict = {}
dict['one'] = "This is one"
dict[2]     = "This is two"

tinydict = {'name': 'john','code':6734, 'dept': 'sales'}


print dict['one']       # Prints value for 'one' key
print dict[2]           # Prints value for 2 key
print tinydict          # Prints complete dictionary
print tinydict.keys()   # Prints all the keys
print tinydict.values() # Prints all the values
```

##### Output:
```
This is two
{'dept': 'sales', 'code': 6734, 'name': 'john'}
['dept', 'code', 'name']
['sales', 6734, 'john']
```
### Python Ladders:
#### if statement:
The if statement contains a logical expression using which data is compared and a decision is made based on the result of the comparison.
Syntax:
```python
if expression:
   statement(s)
```

#### if else statement:
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

#### nested if statement:
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

### Python Loops:
#### While Loops:
A while loop statement in Python programming language repeatedly executes a target statement as long as a given condition is true.
Syntax:
```python
while expression:
   statement(s)
```
#### For Loops:
It has the ability to iterate over the items of any sequence, such as a list or a string. If a sequence contains an expression list, it is evaluated first. Then, the first item in the sequence is assigned to the iterating variable iterating_var. Next, the statements block is executed. Each item in the list is assigned to iterating_var, and the statement(s) block is executed until the entire sequence is exhausted.
Syntax:
```python
for iterating_var in sequence:
   statements(s)
```

#### Nested Loops:
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

## Conclusion:
The above are the very basics of python language. It is just to show the difference between other languages and python in its syntax simplicity. It is a platform independent scripted language with full access to operating system API's. Compared to other programming languages, it allows more run-time flexibility. It supports interactive mode that allows interacting Testing and debugging of snippets of code. In Python, since there is no compilation step, editing, debugging and testing is fast.

