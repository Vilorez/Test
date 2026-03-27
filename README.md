# Data Types Reference from FreeCodeCamp.org
Here are the most common data types you'll use in Python:

    Integer: A whole number without decimals, for example, 10 or -5.

Example Code

my_integer_var = 10
print('Integer:', my_integer_var) # Integer: 10

    Float: A number with a decimal point, like 4.41 or -0.4.

Example Code

my_float_var = 4.50
print('Float:', my_float_var) # Float: 4.5

    String: A sequence of characters enclosed in single or double quotation marks like 'Hello world!'.

Example Code

my_string_var = 'hello'
print('String:', my_string_var) # String: hello

    Boolean: A true or false type, written as True or False.

Example Code

my_boolean_var = True
print('Boolean:', my_boolean_var) # Boolean: True

    Set: An unordered collection of unique elements, like {0.5, 4, 'apple'}.

Example Code

my_set_var = {7, 'hello', 8.5}
print('Set:', my_set_var) # Set: {7, 'hello', 8.5}

    Dictionary: A collection of key-value pairs enclosed in curly braces, like {'name': 'John Doe', 'age': 28}.

Example Code

my_dictionary_var = {'name': 'Alice', 'age': 25}
print('Dictionary:', my_dictionary_var) # Dictionary: {'name': 'Alice', 'age': 25}

    Tuple: An immutable ordered collection, enclosed in parentheses, like ('apple', 4.5, 7).

Example Code

my_tuple_var = (7, 'hello', 8.5)
print('Tuple:', my_tuple_var) # Tuple: (7, 'hello', 8.5)

    Range: A sequence of numbers, often used in loops, for example, range(5).

Example Code

my_range_var = range(5)
print('Range:', my_range_var) # Range: range(0, 5)

    List: An ordered collection of elements that supports different data types.

Example Code

my_list = [22, 'Hello world', 3.14, True]
print(my_list) # [22, 'Hello world', 3.14, True]

    None: A special value that represents the absence of a value.

Example Code

my_none_var = None
print('None:', my_none_var) # None: None

To get the data type of a variable, you can use the type() function:
Example Code

my_var_1 = 'Hello world'
my_var_2 = 21

print(type(my_var_1)) # <class 'str'>
print(type (my_var_2)) # <class 'int'>

And here's are all the data types covered in this lesson, along with their types in the terminal:
Example Code

my_integer_var = 10
print(type(my_integer_var))  # <class 'int'>

my_float_var = 4.50
print(type(my_float_var))  # <class 'float'>

my_string_var = 'hello'
print(type(my_string_var))  # <class 'str'>

my_boolean_var = True
print(type(my_boolean_var))  # <class 'bool'>

my_set_var = {7, 'hello', 8.5}
print(type(my_set_var))  # <class 'set'>

my_dictionary_var = {'name': 'Alice', 'age': 25}
print(type(my_dictionary_var))  # <class 'dict'>

my_tuple_var = (7, 'hello', 8.5)
print(type(my_tuple_var))  # <class 'tuple'>

my_range_var = range(5)
print(type(my_range_var))  # <class 'range'>

my_list = [22, 'Hello world', 3.14, True]
print(type(my_list)) # <class 'list'>

my_none_var = None
print(type(my_none_var))  # <class 'NoneType'>

The built-in isinstance() function lets you check if a variable matches a specific data type. It takes in an object and the type you want to check it against, then returns a boolean. Here are some examples:
Example Code

isinstance('Hello world', str) # True
isinstance(True, bool) # True
isinstance(42, int) # True
isinstance('John Doe', int) # False

