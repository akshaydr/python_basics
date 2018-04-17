# Variable Types
Variables are nothing but reserved memory locations to store values. It means that when you create a variable, you reserve some space in the memory.

Based on the data type of a variable, the interpreter allocates memory and decides what can be stored in the reserved memory. Therefore, by assigning different data types to the variables, you can store integers, decimals or characters in these variables.

## Standard Data Types
The data stored in memory can be of many types. For example, name of a person is stored as a string or characters while age is stored as ainteger.
Python has various standard data types that are used to define the operations possible on them and the storage method for each of them.

### Python has five standard data types:
* Numbers
* String
* List
* Tuple
* Dictionary

## Assigning values to Variables:
Python variables do not need explicit declaration to reserve memory space. The declaration happens automatically when you assign a value to a variable. The equal sign (=) is used to assign values to variables.
As in almost all programming languages, the operand to the left of the = operator is the name of the variable and the operand to the right of the = operator is the value stored in the variable.
For example:
```python
#!/usr/bin/python3

index = 100          # An integer assignment
percentage   = 88.0       # A floating point
name    = "annonymous"       # A string

print (counter)
print (miles)
print (name)
```

Here, 100, 88.0 and "annonymous" are the values assigned to counter, miles, and name variables, respectively. This produces the following result,
```
100
1000.0
John
```

### Multiple Assignment
Python allows you to assign a single value to several variables simultaneously. An integer object is created with the value 1, and all the three variables are assigned to the same memory location.
`a = b = c = 1`

And two integer objects with values 1 and 2 are assigned to the variables a and b respectively, and one string object with the value "john" is assigned to the variable c.
`a, b, c = 1, 2, "john"`

## Python Numbers:
Number data types store numeric values. Number objects are created when you assign a value to them.
For example,
```python3
value1 = 10
value2 = 250
```

## Types in Number datatype:
* int (single integer)
* float (real values)
* complex (complex numbers)

Note: All integers in Python3 are represented as long integers. Hence, there is no separate number type as long.

## Python Strings:
Strings in Python are identified as a contiguous set of characters represented in the quotation marks. Python allows either pair of single or double quotes. Subsets of strings can be taken using the slice operator ([ ] and [:] ) with indexes starting at 0 in the beginning of the string and working their way from -1 to the end.

Adding of two strings is made very simple in python. The plus (+) sign is the string concatenation operator and the asterisk ( * ) is the repetition operator.

For example,
```python
#!/usr/bin/python3

str = 'Hello World!'

print (str)          # Prints complete string
print (str[0])       # Prints first character of the string
print (str[2:5])     # Prints characters starting from 3rd to 5th
print (str[2:])      # Prints string starting from 3rd character
print (str * 2)      # Prints string two times
print (str + "TEST") # Prints concatenated string
```
This will produce the following result,
```
Hello World!
H
llo
llo World!
Hello World!Hello World!
Hello World!TEST
```

## Python lists:
Lists are the most versatile of Python's compound data types. A list contains items separated by commas and enclosed within square brackets ([]). To some extent, lists are similar to arrays in C. One of the differences between them is that all the items belonging to a list can be of different data type.

The values stored in a list can be accessed using the slice operator ([ ] and [:]) with indexes starting at 0 in the beginning of the list and working their way to end -1. The plus (+) sign is the list concatenation operator, and the asterisk ( * ) is the repetition operator.
For example,
```python
#!/usr/bin/python3

list1 = [ 'abcd', 786 , 2.23, 'john', 70.2 ]
list2 = [123, 'john']

print (list1)          # Prints complete list
print (list1[0])       # Prints first element of the list
print (list1[1:3])     # Prints elements starting from 2nd till 3rd
print (list1[2:])      # Prints elements starting from 3rd element
print (list2 * 2)      # Prints list two times
print (list1 + list2)  # Prints concatenated lists
```
This will produce the following result,
```
['abcd', 786, 2.23, 'john', 70.200000000000003]
abcd
[786, 2.23]
[2.23, 'john', 70.200000000000003]
[123, 'john', 123, 'john']
['abcd', 786, 2.23, 'john', 70.200000000000003, 123, 'john']
```

## Python tuples:
A tuple is another sequence data type that is similar to the list. A tuple consists of a number of values separated by commas. Unlike lists, however, tuples are enclosed within parenthesis.

The main difference between lists and tuples are − Lists are enclosed in brackets ( [ ] ) and their elements and size can be changed, while tuples are enclosed in parentheses ( ( ) ) and cannot be updated. Tuples can be thought of as read-only lists.
For example,
```python
#!/usr/bin/python3

tuple1 = ( 'abcd', 786 , 2.23, 'john', 70.2  )
tuple2 = (123, 'john')

print (tuple1)           # Prints complete tuple
print (tuple1[0])        # Prints first element of the tuple
print (tuple1[1:3])      # Prints elements starting from 2nd till 3rd
print (tuple1[2:])       # Prints elements starting from 3rd element
print (tuple2 * 2)       # Prints tuple two times
print (tuple1 + tuple2)  # Prints concatenated tuple
```
This will produce the following result,
```
('abcd', 786, 2.23, 'john', 70.200000000000003)
abcd
(786, 2.23)
(2.23, 'john', 70.200000000000003)
(123, 'john', 123, 'john')
('abcd', 786, 2.23, 'john', 70.200000000000003, 123, 'john')
```

## Python Dictionary:
Python's dictionaries are kind of hash-table type. They work like associative arrays or hashes found in Perl and consist of key-value pairs. A dictionary key can be almost any Python type, but are usually numbers or strings. Values, on the other hand, can be any arbitrary Python object.

Dictionaries are enclosed by curly braces ({ }) and values can be assigned and accessed using square braces ([])
For example,
```python
#!/usr/bin/python3

dict = {}
dict['one'] = "This is one"
dict[2]     = "This is two"

dict2 = {'name': 'john','code':6734, 'dept': 'sales'}

print (dict['one'])       # Prints value for 'one' key
print (dict[2])           # Prints value for 2 key
print (dict2)             # Prints complete dictionary
print (dict2.keys())      # Prints all the keys
print (dict2.values())    # Prints all the values
```
This will produces the following result,
```
This is one
This is two
{'name': 'john', 'dept': 'sales', 'code': 6734}
dict_keys(['name', 'dept', 'code'])
dict_values(['john', 'sales', 6734])
```

Note: Dictionaries have no concept of order among the elements. It is incorrect to say that the elements are "out of order"; they are simply unordered.
