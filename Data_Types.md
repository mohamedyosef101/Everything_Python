# **Integers**

Integers are numbers without any fractional part and can be positive (`1`, `2`, `3`, ...), negative (`-1`, `-2`, `-3`, ...), or zero (`0`).

```python
x = 14
print(x)
print(type(x))
```

> 14
<class 'int'>
> 

*In the output above, `<class 'int'>` refers to the **int**eger data type.*

# **Floats**

Floats are numbers with fractional parts. They can have many numbers after decimal.

```python
nearly_pi = 3.141592653589793238462643383279502884197169399375105820974944
print(nearly_pi)
print(type(nearly_pi))
```

> 3.141592653589793
<class 'float'>
> 

# **Booleans**

Booleans represent one of two values: `True` or `False`. In the code cell below, `z_one` is set to a boolean with value `True`.

```python
z_one = Trueprint(z_one)
print(type(z_one))
```

> True
<class 'bool'>
> 

# **Strings**

The string data type is a collection of characters (like alphabet letters, punctuation, numerical digits, or symbols) contained in quotation marks. Strings are commonly used to represent text.

```python
w = "Hello, Python!"
print(w)
print(type(w))
```

> Hello, Python!
<class 'str'>
> 

You can get the length of a string with `len()`. `"Hello, Python!"` has length 14, because it has 14 characters, including the space, comma, and exclamation mark. Note that the quotation marks are not included when calculating the length.

```python
print(len(w))
```

> 14
>
