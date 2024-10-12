# 0x00. Python - Variable Annotations

## Project Overview

This project focuses on **Python variable annotations**, a feature that allows specifying the types of variables and function arguments in Python 3.7+. The goal is to familiarize you with the use of type annotations, improve code readability, and validate your code using tools like `mypy`. 

This is part of the **ALX Backend Python** curriculum, where you'll work on annotating Python code, writing type-annotated functions, and handling more complex types.

## Concepts

- **Advanced Python**
- **Type Annotations**
- **Duck Typing**
- **Mypy for code validation**

## Learning Objectives

By the end of this project, you should be able to:

- Understand type annotations in Python 3.
- Use type annotations to specify function signatures and variable types.
- Apply duck typing.
- Validate your code with `mypy`.

## Project Tasks

### Mandatory Tasks

1. **Basic annotations - add**
   - Write a type-annotated function `add` that takes two floats and returns their sum.
   
   File: `0-add.py`

2. **Basic annotations - concat**
   - Write a type-annotated function `concat` that takes two strings and returns their concatenation.

   File: `1-concat.py`

3. **Basic annotations - floor**
   - Write a type-annotated function `floor` that returns the floor of a float.

   File: `2-floor.py`

4. **Basic annotations - to string**
   - Write a type-annotated function `to_str` that returns the string representation of a float.

   File: `3-to_str.py`

5. **Define variables**
   - Define and annotate several variables with specific values.

   File: `4-define_variables.py`

6. **Complex types - list of floats**
   - Write a type-annotated function `sum_list` that takes a list of floats and returns their sum.

   File: `5-sum_list.py`

7. **Complex types - mixed list**
   - Write a type-annotated function `sum_mixed_list` that takes a list of integers and floats and returns their sum as a float.

   File: `6-sum_mixed_list.py`

8. **Complex types - string and int/float to tuple**
   - Write a type-annotated function `to_kv` that takes a string and an int/float and returns a tuple.

   File: `7-to_kv.py`

9. **Complex types - functions**
   - Write a type-annotated function `make_multiplier` that returns a function to multiply a float by a given multiplier.

   File: `8-make_multiplier.py`

10. **Let's duck type an iterable object**
    - Annotate the `element_length` function to handle an iterable object.

    File: `9-element_length.py`

### Advanced Tasks

1. **Duck typing - first element of a sequence**
   - Add annotations to a function that returns the first element of a sequence or `None`.

   File: `100-safe_first_element.py`

2. **More involved type annotations**
   - Add type annotations to a function `safely_get_value` to handle default values.

   File: `101-safely_get_value.py`

3. **Type Checking**
   - Use `mypy` to validate the provided code and fix any type issues.

   File: `102-type_checking.py`

## Resources

- [Python 3 typing documentation](https://docs.python.org/3/library/typing.html)
- [MyPy cheat sheet](https://mypy.readthedocs.io/en/stable/cheat_sheet_py3.html)

## Requirements

- All files will be interpreted/compiled on Ubuntu 18.04 LTS using Python 3.7.
- All code must follow `pycodestyle` (version 2.5).
- All files should be executable and contain proper documentation for modules, classes, and functions.

## Repository

- GitHub repository: `alx-backend-python`
- Directory: `0x00-python_variable_annotations`
