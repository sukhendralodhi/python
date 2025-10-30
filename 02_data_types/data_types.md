# Object Types / Data Types

- Number: 1234, 3.14, 3+4j, 0b111, Decimal(), Fraction()
- String: 'Spam', "Bob's", b'a\x01c'
- List: [1, [2, 'three], 4.5] list(range(10))

- Tuple: (1, 'spam', 4, 'U'), tuple('spam'), namedtuple

- Dictionary: {
    'food': 'spam',
    'taste': 'yummy'
},dict(hours=10)

- Set: set('abc'), {'a', 'b', 'c'}
- Boolean: true, false
- None: None
- Funxtion, modules, classes

# File Mechanism

- file: open(eg.txt)

---

# Advance 
- Decorators
- Generators
- Iterators
- MetaProgramming

---
# Braces Types

- [] = brackets
- () = paranthesas
- {} = curly braces

---

# Python Code Exmaple of print hello
```python
print('hello world')
```

# Some python Sell Example

```python
>>> 12+12
24
>>> 2*5
10
>>> 2.5*10
25.0
>>> 2**2
4
>>> 2 ** 100
1267650600228229401496703205376
>>>
>>> import math
>>> math.pi
3.141592653589793
>>> import random
>>> random.random()
0.8395476815903544
>>>
>>> random.random()
0.5152807271939768
>>> random.random()
0.8797302542666245
>>>
```

# Mutable and Immutable in Python

In Python, **data types are classified into two categories** based on whether their values can be changed after creation.

---

## ✅ Mutable Objects
Mutable objects **can be changed** after they are created.

Examples:
- `list`
- `dict`
- `set`
- `bytearray`
- `user-defined objects`

### Example:
```python
my_list = [1, 2, 3]
my_list[0] = 10       # Value changed
print(my_list)        # Output: [10, 2, 3]
```


## ❌ Immutable Objects
Immutable objects **cannot be changed** once created.

- `int`
- `float`
- `string (str)`
- `tuple`
- `bool`
- `frozenset`
- `bytes`

# Example:

```python
x = 5
x = 10   # This creates a new object, does NOT change the old one

text = "Hello"
# text[0] = "J"  # ❌ Not allowed, strings are immutable

```

# 🧠 Key Difference

| Feature                  | Mutable         | Immutable                |
| ------------------------ | --------------- | ------------------------ |
| Can value change?        | ✅ Yes           | ❌ No                     |
| Memory location changes? | No              | Yes (new object created) |
| Examples                 | list, dict, set | int, float, str, tuple   |

# Memory Proof Example:


```python
a = "hello"
print(id(a))   # memory address

a = "world"    # new value assigned
print(id(a))   # different memory address → new object created

```