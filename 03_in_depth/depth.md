# Depth Python

Python does not require you to declare the data type of a variable when creating it.
However, when you assign a value, Python automatically infers the data type based on the value assigned inside memory.
This feature is called dynamic typing

```python
x = 10        # Python automatically sets type as int
y = "Hello"   # type is str
z = 3.14      # type is float
```

```python
print(type(x))  # <class 'int'>
print(type(y))  # <class 'str'>
print(type(z))  # <class 'float'>
```

```python
a = 10        # 'a' refers to an integer object with value 10
a = "string"  # now 'a' refers to a string object, and the integer 10 is no longer referenced
```

# 🧠 Explanation:

- In Python, variables are just names (references) that point to objects in memory.

- When you reassign a to "string", the previous object (10) becomes unreferenced.

- The garbage collector will eventually remove that unreferenced object, but not immediately — only when Python decides it’s time to free memory.

- This behavior is the same for all data types (numbers, strings, lists, etc.),
  not just for numbers or strings.

---
In Python, variables are references to objects. When a new value is assigned, the old object becomes unreferenced and is later removed by the garbage collector—not immediately, but when Python’s memory management decides it’s needed.
---
