# First Python Program

As mentioned in part 2 of Section 1, We would be using python 3.5.2 throughout this chapter.

## Interactive Mode Programming
Invoking the interpreter without passing a script file as a parameter brings up the following prompt:

`Python 3.5.2 (default, Nov 23 2017, 16:37:01)
[GCC 5.4.0 20160609] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
`

Type the following text at the Python prompt and press the Enter,
`python3
>>> print ("Hello World!")
`

However in python 2, parenthesis is not necessary in the print statement. Parenthesis is compulsory in python 3. Python version 3.5.2 will produce the following result −
`Hello World!`


## Script mode programming

Invoking the interpreter with a script parameter begins execution of the script and continues until the script is finished. When the script is finished, the interpreter is no longer active.

Let us write a simple Python program in a script. Python files have extension .py. Type the following source code in a hello.py file −
`python3
print ("Hello World!")
`

Now open a terminal and run the program as follows,
`$ python3 hello.py`
This produces the same result as shown above.

# Python Identifiers
Python indentifiers are almost similar to all other languages. A Python identifier is a name used to identify a variable, function, class, module or other object. An identifier starts with a letter A to Z or a to z or an underscore ( _ ) followed by zero or more letters, underscores and digits (0 to 9).

Python does not allow punctuation characters such as @, $, and % within identifiers. Python is a case sensitive programming language. Thus, Green and green are two different identifiers in Python.

Here are naming conventions for Python identifiers −
* Class names start with an uppercase letter. All other identifiers start with a lowercase letter.
* Starting an identifier with a single leading underscore indicates that the identifier is private.
* Starting an identifier with two leading underscores indicates a strongly private identifier.
* If the identifier also ends with two trailing underscores, the identifier is a language-defined special name.

# Reserved Workds
The following list shows the Python keywords. These are reserved words and you cannot use them as constant or variable or any other identifier names. All the Python keywords contain lowercase letters only.
`python3
and	            exec    	   not
assert	        finally      or
break         	for          pass
class         	from         print
continue        global       raise
def         	  if           return
del         	  import       try
elif          	in           while
else          	is           with
except          lambda       yield
`

# Lines and Indentation
Python provides no braces to indicate blocks of code for class and function definitions or flow control. Blocks of code are denoted by line indentation, which is rigidly enforced.

The number of spaces in the indentation is variable, but all statements within the block must be indented the same amount. For example,
`python3
if True:
   print ("True")
else:
   print ("False")
`
In Python all the continuous lines indented with same number of spaces would form a block.

# Comments in Python
A hash sign (#) that is not inside a string literal begins a comment. All characters after the # and up to the end of the physical line are part of the comment and the Python interpreter ignores them.
`python3
# First comment
print "Hello!" # second comment
`
This produces the following result,
`Hello!`
