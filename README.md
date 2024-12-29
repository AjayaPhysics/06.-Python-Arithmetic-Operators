# 06.-Python-Arithmetic-Operators
Let's go through Python Arithmetic Operators one by one, with clear explanations and examples.
### Arithmetic Operators in Python

Arithmetic operators in Python are used to perform mathematical operations like addition, subtraction, multiplication, division, etc.

| Operator | Name                 | Description                                                                 | Example Code                         | Output  |
|----------|----------------------|-----------------------------------------------------------------------------|---------------------------------------|---------|
| `+`      | Addition             | Adds two operands.                                                         | `a = 5; b = 3; print(a + b)`          | `8`     |
| `-`      | Subtraction          | Subtracts the right operand from the left operand.                         | `a = 5; b = 3; print(a - b)`          | `2`     |
| `*`      | Multiplication       | Multiplies two operands.                                                   | `a = 5; b = 3; print(a * b)`          | `15`    |
| `/`      | Division             | Divides the left operand by the right operand and returns a float result.  | `a = 5; b = 3; print(a / b)`          | `1.6667`|
| `//`     | Floor Division       | Divides the operands and returns the largest integer less than or equal.   | `a = 5; b = 3; print(a // b)`         | `1`     |
| `%`      | Modulus              | Returns the remainder when the left operand is divided by the right.       | `a = 5; b = 3; print(a % b)`          | `2`     |
| `**`     | Exponentiation       | Raises the left operand to the power of the right operand.                 | `a = 5; b = 3; print(a ** b)`         | `125`   |

---
### Explanations

1. **Addition (`+`):**
   - Adds two numbers together.
   - Example: `5 + 3` results in `8`.

2. **Subtraction (`-`):**
   - Subtracts the second number from the first.
   - Example: `5 - 3` results in `2`.

3. **Multiplication (`*`):**
   - Multiplies two numbers.
   - Example: `5 * 3` results in `15`.

4. **Division (`/`):**
   - Divides the first number by the second and returns a float.
   - Example: `5 / 3` results in `1.6667`.

5. **Floor Division (`//`):**
   - Divides the first number by the second and returns the largest integer less than or equal to the division result.
   - Example: `5 // 3` results in `1`.

6. **Modulus (`%`):**
   - Returns the remainder of dividing the first number by the second.
   - Example: `5 % 3` results in `2`.

7. **Exponentiation (`**`):**
   - Raises the first number to the power of the second.
   - Example: `5 ** 3` results in `125`.

---
### Example Code
```python
# Arithmetic Operators Examples

# Addition
a = 5
b = 3
print("Addition:", a + b)  # Output: 8

# Subtraction
print("Subtraction:", a - b)  # Output: 2

# Multiplication
print("Multiplication:", a * b)  # Output: 15

# Division
print("Division:", a / b)  # Output: 1.6667

# Floor Division
print("Floor Division:", a // b)  # Output: 1

# Modulus
print("Modulus:", a % b)  # Output: 2

# Exponentiation
print("Exponentiation:", a ** b)  # Output: 125



### Arithmetic Operators in Python

Arithmetic operators in Python are used to perform fundamental mathematical operations such as addition, subtraction, multiplication, division, and more. They are straightforward and essential for any computational tasks.

| Operator | Name                 | Description                                                                 | Example Code                         | Output  |
|----------|----------------------|-----------------------------------------------------------------------------|---------------------------------------|---------|
| `+`      | Addition             | Combines two values by summing them up.                                     | `a = 5; b = 3; print(a + b)`          | `8`     |
| `-`      | Subtraction          | Finds the difference between two values by subtracting the second from the first. | `a = 5; b = 3; print(a - b)`          | `2`     |
| `*`      | Multiplication       | Multiplies two values to compute the product.                               | `a = 5; b = 3; print(a * b)`          | `15`    |
| `/`      | Division             | Divides the first value by the second, yielding a floating-point result.    | `a = 5; b = 3; print(a / b)`          | `1.6667`|
| `//`     | Floor Division       | Performs division and returns the largest integer value less than or equal to the result. | `a = 5; b = 3; print(a // b)`         | `1`     |
| `%`      | Modulus              | Returns the remainder of dividing the first value by the second.            | `a = 5; b = 3; print(a % b)`          | `2`     |
| `**`     | Exponentiation       | Raises the first value to the power of the second.                          | `a = 5; b = 3; print(a ** b)`         | `125`   |

---
### Detailed Explanations with Examples

1. **Addition (`+`):**
   - Adds two numbers together. Commonly used in summing up values.
   - Example:
     ```python
     a = 5
     b = 3
     print(a + b)  # Output: 8
     ```

2. **Subtraction (`-`):**
   - Subtracts the second number from the first. Useful for finding differences.
   - Example:
     ```python
     a = 5
     b = 3
     print(a - b)  # Output: 2
     ```

3. **Multiplication (`*`):**
   - Multiplies two numbers. Frequently used in area and volume calculations.
   - Example:
     ```python
     a = 5
     b = 3
     print(a * b)  # Output: 15
     ```

4. **Division (`/`):**
   - Divides the first number by the second, returning a precise floating-point value.
   - Example:
     ```python
     a = 5
     b = 3
     print(a / b)  # Output: 1.6667
     ```

5. **Floor Division (`//`):**
   - Performs division but truncates the decimal, giving an integer result.
   - Example:
     ```python
     a = 5
     b = 3
     print(a // b)  # Output: 1
     ```

6. **Modulus (`%`):**
   - Calculates the remainder when the first number is divided by the second. Often used in finding even/odd numbers.
   - Example:
     ```python
     a = 5
     b = 3
     print(a % b)  # Output: 2
     ```

7. **Exponentiation (`**`):**
   - Raises the first number to the power of the second, useful in scientific computations.
   - Example:
     ```python
     a = 5
     b = 3
     print(a ** b)  # Output: 125
     ```

---
### Comprehensive Example Code
```python
# Arithmetic Operators Examples

a = 5
b = 3

# Addition
print("Addition:", a + b)  # Output: 8

# Subtraction
print("Subtraction:", a - b)  # Output: 2

# Multiplication
print("Multiplication:", a * b)  # Output: 15

# Division
print("Division:", a / b)  # Output: 1.6667

# Floor Division
print("Floor Division:", a // b)  # Output: 1

# Modulus
print("Modulus:", a % b)  # Output: 2

# Exponentiation
print("Exponentiation:", a ** b)  # Output: 125
```
