## Print hello world

```
print("Hello World!") # Prints Hello World
```
## Find `type` of variable

```
some_variable = 1.6 # float
print(type(some_variable)) # prints <class 'float'>
```
Output would look like this
```
hello world
<class 'int'>
<class 'float'>
```

## String Operations (built-in functions)

```
some_string = "hello world, This is A test"
print(some_string.capitalize())  # Capitalizes the first character
print(some_string.count("a")) # Counts the number of times the character "a" occurs in the string
print(some_string.endswith("test")) # Returns True if the string ends with the substring "test"
print(some_string.find("gem")) # Returns the index of the first occurrence of the substring "gem" and -1 if it does not exist.
print(some_string.index("test")) # Returns the index of the first occurrence of the substring "test" and raises an exception if it does not exist.
print(some_string.upper()) # Returns a copy of the string in uppercase
print(some_string.title()) # Returns a copy of the string in title case
print(some_string.swapcase()) # Returns a copy of the string in swapcase
```

to know all the functions available for a string

```
some_string = "hello world, This is a string"
print(dir(some_string)) # prints all the functions available with strings
```

Output looks like this

```
['__add__', '__class__', '__contains__', '__delattr__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__getitem__', '__getnewargs__', '__gt__', '__hash__', '__init__', '__init_subclass__', '__iter__', '__le__', '__len__', '__lt__', '__mod__', '__mul__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__rmod__', '__rmul__', '__setattr__', '__sizeof__', '__str__', '__subclasshook__', 'capitalize', 'casefold', 'center', 'count', 'encode', 'endswith', 'expandtabs', 'find', 'format', 'format_map', 'index', 'isalnum', 'isalpha', 'isascii', 'isdecimal', 'isdigit', 'isidentifier', 'islower', 'isnumeric', 'isprintable', 'isspace', 'istitle', 'isupper', 'join', 'ljust', 'lower', 'lstrip', 'maketrans', 'partition', 'removeprefix', 'removesuffix', 'replace', 'rfind', 'rindex', 'rjust', 'rpartition', 'rsplit', 'rstrip', 'split', 'splitlines', 'startswith', 'strip', 'swapcase', 'title', 'translate', 'upper', 'zfill']
```

## F strings (Formatter)

```
some_variable = "john"
print(f"hello {some_variable}") # prints hello john
print(f"{some_variable.upper()}") # prints JOHN
print(f"{1+2-3}") # prints 0
```
