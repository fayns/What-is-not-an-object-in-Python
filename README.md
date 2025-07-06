#In Python, almost everything is treated as an object: numbers, strings, functions, classes, and modules are all objects. However, there are some elements that are not objects:

## Operators and syntax:
Operators (such as +, -, *, and, or, not, and others) are parts of the language that are not represented as objects in memory.

## Type annotations:
Type annotations, such as list[str], do not create objects at runtime, but are used only for static code analysis.

```python 
def func(x: int) -> str:
 return str(x)
```
## Variable names:
Variable names are just references to objects, not objects themselves. A variable points to an object in memory, but is not an object itself.

```python
x = 42 # 'x' is a name, not an object
print(type(x))  # The object is the number 42, not the name 'x'
```
## Keywords:
Python keywords (if, else, while, for, def, class, return, etc.) are reserved words used to control the logic of a program, and they are not objects.

```python
print(type(if))  # Error: keyword is not an object
```
