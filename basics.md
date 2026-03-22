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

## Functions

```
def greet(name): # this defines a function called greet with one parameter called name
    salutation = "Good Morning " + name # Note that the function body is indented, this marks the start of the code block
    return salutation # The return keyword returns the value of the function to the caller

print(greet("John")) # prints "Good Morning John"
print(greet("Jane")) # prints "Good Morning Jane"
# We only had to define the function once, we can call it as many times as we want
```

If we don't return something it returns `None`

## Lists

```
list_with_numbers = [1, 2, 3, 4, 5]
list_with_strings = ["a", "b", "c", "d", "e"]
list_with_mixed_data_types = [1, "a", "b", "c", "d", "e"]
length_of_list = len(list_with_numbers) # This will return the length of the list
```
```
list_with_numbers = [1, 2, 3, 4, 5]
print(list_with_numbers[0]) # prints 1
```
Lists can be sliced ( create a new sublist from the list ) like this **list_variable[start:end]** (note that the start is included and the end is excluded). Lists can also be negatively indexed i.e **-1 index is the last element.**

```
list_with_numbers = [1, 2, 3, 4, 5]
print(list_with_numbers[0:2]) # prints [1, 2]
print(list_with_numbers[:2]) # prints [1, 2] not specifying a start index will start from the beginning
print(list_with_numbers[2:]) # prints [3, 4, 5] not specifying an end index will end at the end
print(list_with_numbers[-1]) # prints 5
print(list_with_numbers[-3:]) # prints [3, 4, 5] ( the last three items with the start included)
```

```
list_with_numbers = [1, 2, 3, 4, 5]
list_with_numbers.append(6) # adds 6 to the end of the list
list_with_numbers.insert(2, 7) # inserts 7 at index 2
list_with_numbers.remove(3) # removes the first 3 from the list ** Based on the value not the index
list_with_numbers.pop() # removes the last item from the list
list_with_numbers.pop(0) # removes the first item from the list
list_with_numbers.reverse() # reverses the order of the list, note that this function does not return anything
list_with_numbers.sort() # sorts the list , note that this function does not return anything
list_with_numbers.sort(reverse=True) # sorts the list in reverse order
```


