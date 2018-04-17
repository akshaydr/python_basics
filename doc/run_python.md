# First Python Program

As mentioned in part 2 of Section 1, We would be using python 3.5.2 throughout this chapter.

## Interactive Mode Programming
Invoking the interpreter without passing a script file as a parameter brings up the following prompt:
'
Python 3.5.2 (default, Nov 23 2017, 16:37:01)
[GCC 5.4.0 20160609] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
'

Type the following text at the Python prompt and press the Enter,
'python3
>>> print ("Hello World!")
'

However in python 2, parenthesis is not necessary in the print statement. Parenthesis is compulsory in python 3. Python version 3.5.2 will produce the following result −
`Hello World!`


## Script mode programming

Invoking the interpreter with a script parameter begins execution of the script and continues until the script is finished. When the script is finished, the interpreter is no longer active.

Let us write a simple Python program in a script. Python files have extension .py. Type the following source code in a hello.py file −
'
print ("Hello World!")
'

Now open a terminal and run the program as follows,
`$ python3 hello.py`
This produces the same result as shown above.
