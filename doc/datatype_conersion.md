# Data type conversions:

Sometimes, you may need to perform conversions between the built-in types. To convert between types, you simply use the type-names as a function.

There are several built-in functions to perform conversion from one data type to another. These functions return a new object representing the converted value.

1. Converts x to an integer. The base specifies the base if x is a string.
```python
int(x [,base])
```
2. Converts x to a floating-point number.
```python
float(x)
```
3. Creates a complex number.
```python
complex(real [,imag])
```
4. Converts object x to a string representation.
``` python
str(x)
```
5. Converts object x to an expression string.
```python
repr(x)
```
6. Evaluates a string and returns an object.
```python
eval(str)
```
7. Converts s to a tuple.
```python
tuple(s)
```
8. Converts s to a list.
```python
list(s)
```
9. Converts s to a set.
```python
set(s)
```
10. Creates a dictionary. d must be a sequence of (key,value) tuples.
```python
dict(d)
```
11. Converts s to a frozen set.
```python
frozenset(s)
```
12. Converts an integer to a character.
```python
chr(x)
```
