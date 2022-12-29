## Overview

Python has several operators for performing different types of operations on variables. Some common operators include:

```
+: addition
-: subtraction
*: multiplication
/: division
%: modulus (remainder after division)
**: exponentiation
```

```
x = 10
y = 5

# Addition
z = x + y  # 15

# Subtraction
z = x - y  # 5

# Multiplication
z = x * y  # 50

# Division
z = x / y  # 2

# Modulus
z = x % y  # 0

# Exponentiation
z = x ** y  # 100000
```

## What to know

Here are some things to know about operators in Python:

1. Operators are symbols that perform specific operations on variables.
1. Python has several types of operators, including arithmetic operators, assignment operators, comparison operators, logical operators, and bitwise operators.
1. Arithmetic operators are used to perform mathematical operations, such as addition, subtraction, multiplication, and division.
1. Assignment operators are used to assign values to variables.
1. Comparison operators are used to compare two values and return a boolean value (True or False).
1. Logical operators are used to perform logical operations, such as and, or, and not.
1. Bitwise operators are used to perform operations on the binary representation of numbers.

Here is an example of using operators in Python:

```
# Arithmetic operators
x = 10
y = 5
z = x + y  # 15
z = x - y  # 5
z = x * y  # 50
z = x / y  # 2
z = x % y  # 0
z = x ** y  # 100000

# Assignment operators
x = 10
x += 5  # x is now 15
x -= 5  # x is now 10
x *= 2  # x is now 20
x /= 2  # x is now 10

# Comparison operators
x = 10
y = 5
print(x == y)  # False
print(x != y)  # True
print(x > y)   # True
print(x < y)   # False
print(x >= y)  # True
print(x <= y)  # False

# Logical operators
x = True
y = False
print(x and y)  # False
print(x or y)   # True
print(not x)    # False

# Bitwise operators
x = 10  # binary representation: 1010
y = 5   # binary representation: 0101
z = x & y  # binary representation: 0000; decimal representation: 0
z = x | y  # binary representation: 1111; decimal representation: 15
z = x ^ y  # binary representation: 1111; decimal representation: 15
z = ~x     # binary representation: 0101; decimal representation: -11
```

You can find more information about operators in the Python documentation: https://docs.python.org/3/library/stdtypes.html#numeric-types-int-float-complex

