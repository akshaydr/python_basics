# Operators
Operators are the constructs, which can manipulate the value of operands. Consider the expression 4 + 5 = 9. Here, 4 and 5 are called the operands and + is called the operator.

## Types of operators
Python language supports the following types of operators −

1. Arithmetic Operators
2. Comparison (Relational) Operators
3. Assignment Operators
4. Logical Operators
5. Bitwise Operators
6. Membership Operators
7. Identity Operators

### Arithmetic operators
Assume variable a holds the value 10 and variable b holds the value 21, then -
* Addition ( + ): a + b = 31
* Subtraction ( - ):a – b = -11
* Multiplication ( * ): a * b = 210
* Division ( / ): b / a = 2.1
* Modulus ( % ): b % a = 1
* Exponent ( ** ): a**b =10 to the power 20

### Comparison operators
These operators compare the values on either side of them and decide the relation among them. They are also called Relational operators.

Assume variable a holds the value 10 and variable b holds the value 20.
* ( == ): If the values of two operands are equal, then the condition becomes true.
`Ex: (a == b) is not true.`
* ( != ): If values of two operands are not equal, then condition becomes true.
`Ex: (a != b) is true.`
* ( > ): If the value of left operand is greater than the value of right operand, then condition becomes true.
`Ex: (a > b) is not true.`
* ( < ): If the value of left operand is less than the value of right operand, then condition becomes true.
`Ex: (a < b) is true.`
* ( >= ): If the value of left operand is greater than or equal to the value of right operand, then condition becomes true.
`Ex: (a >= b) is not true.`
* ( <= ): If the value of left operand is less than or equal to the value of right operand, then condition becomes true.
`Ex: (a <= b) is true.`

### Assignment operators
Assume variable a holds the value 10 and variable b holds the value 20.
* ( = ): Assigns values from right side operands to left side operand
`Ex: c = a + b assigns value of a + b into c`
* ( += ): It adds right operand to the left operand and assign the result to left operand
`Ex: c += a is equivalent to c = c + a`
* ( -= ): It subtracts right operand from the left operand and assign the result to left operand
`Ex: c -= a is equivalent to c = c - a`

### Logical Operators
The following logical operators are supported by Python language. Assume variable a holds True and variable b holds False.
* and Logical AND: If both the operands are true then condition becomes true.
`Ex: (a and b) is False.`
* or Logical OR: If any of the two operands are non-zero then condition becomes true.
`Ex: (a or b) is True.`
* not Logical NOT: Used to reverse the logical state of its operand.
`Ex: Not(a and b) is True.`

### Bitwise Operators
Bitwise operator works on bits and performs bit-by-bit operation. Assume if a = 60; and b = 13; Now in binary format they will be as follows −
a = 0011 1100
b = 0000 1101
then,
a&b = 0000 1100
a|b = 0011 1101
a^b = 0011 0001
~a = 1100 0011

### Membership Operators
Python’s membership operators test for membership in a sequence, such as strings, lists, or tuples. There are two membership operators as explained below −
* in: Evaluates to true if it finds a variable in the specified sequence and false otherwise.
`Ex: x in y, here in results in a 1 if x is a member of sequence y.`
* not in: Evaluates to true if it does not finds a variable in the specified sequence and false otherwise.
`Ex: x not in y, here not in results in a 1 if x is not a member of sequence y.`

###  Identity Operators
Identity operators compare the memory locations of two objects. There are two Identity operators as explained below −
* is: Evaluates to true if the variables on either side of the operator point to the same object and false otherwise.
`Ex: x is y, here is results in 1 if id(x) equals id(y).`
* is not: Evaluates to false if the variables on either side of the operator point to the same object and true otherwise.
`x is not y, here is not results in 1 if id(x) is not equal to id(y).`
