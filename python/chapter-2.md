# variables, expressions, and statements

## constants
fixed values
numbers (numbers), strings (use single or double quotes)

## reserved words
special words you cannot use as variables/identifiers

## variables
allocate memory for data under a variable name
change variable with an assignment statement
```python
hours = 35.0
rate = 12.5
pay = hours * rate
print(pay)
```
case sensitive
can contain letters, numbers, and underscores
variables should be short, descriptive, and convenient

## operators
| Operator | Operation      |
| -------- | -------------- |
| x        | addition       |
| -        | subtraction    |
| *        | multiplication |
| /        | division       |
| **       | power          |
| %        | remainder      |

## numeric expressions
```python
x = 2
x = x + 2
print(x) # => 4
```

## order of operations
operator precedence
parenthesis -> power -> multiplication or division -> addition or subtraction
```python
x = 1 + 2 ** 3 / 4 * 5
print(x) # => 11
```

## type
variables, literals, and constants have a type
python can differentiate integers and strings (and other data types)
allows you to add numbers and concatenate strings
you can retrieve a type with the `type` function
```python
print(1 + 4) # => 5
print("hello " + "world") # => hello world
print(type(1)) # => <class 'int'>
```

## type conversions
directly convert variables with `int`, `float`, `str`, etc.
```python
print(float(99) + 100) # => 199.0
```

## integer division
always creates a floating point result (in python 3, big improvement)
```python
print(10 / 2) # => 5.0
print(99/ 100) # => 0.99
```

## user input
python will pause execution to take data from the user with `input`
`input` always returns a string
`print` can have infinitely many parameters
```python
name = input("What is your name? ")
print("Welcome", name)
```

## elevator floor conversion
people around the world start their elevators at "0", but america starts with "1"
```python
floor = int(input("Europe floor? "))
print("American floor", floor + 1)
```

## comments
text that will be ignored
starts with `#`, everything after will be ignored
can be used to describe code and documentation