# 0x00. Python - Variable Annotations 📜

Welcome to the **Python - Variable Annotations** project, part of the ALX Backend Python curriculum. In this project, you will explore type annotations in Python 3, which allows you to specify the types of variables, function parameters, and return values.

## 📝 Learning Objectives

By completing this project, you will:

- 🏷️ **Understand Type Annotations in Python 3:** Learn how to use type annotations to specify function signatures and variable types.
- 🐦 **Duck Typing:** Explore how Python allows dynamic typing, but lets you enforce type hints with MyPy.
- ✔️ **Validate Code with MyPy:** Learn how to use MyPy to check your code for correct type annotations.

## 📂 Project Structure

This project includes the following:

1. **Task 0: Basic Annotations - Add**  
   - **File:** [0-add.py](./0-add.py)  
   - **Description:** Write a type-annotated function `add` that takes two `float` arguments and returns their sum as a `float`.

2. **Task 1: Basic Annotations - Concat**  
   - **File:** [1-concat.py](./1-concat.py)  
   - **Description:** Write a type-annotated function `concat` that takes two `string` arguments and returns a concatenated string.

3. **Task 2: Basic Annotations - Floor**  
   - **File:** [2-floor.py](./2-floor.py)  
   - **Description:** Write a type-annotated function `floor` that takes a `float` as an argument and returns the `int` floor of the float.

4. **Task 3: Basic Annotations - To String**  
   - **File:** [3-to_str.py](./3-to_str.py)  
   - **Description:** Write a type-annotated function `to_str` that takes a `float` as an argument and returns its string representation.

5. **Task 4: Define Variables**  
   - **File:** [4-define_variables.py](./4-define_variables.py)  
   - **Description:** Define and annotate variables with specified values: an integer `a`, a float `pi`, a boolean `i_understand_annotations`, and a string `school`.

6. **Task 5: Complex Types - List of Floats**  
   - **File:** [5-sum_list.py](./5-sum_list.py)  
   - **Description:** Write a type-annotated function `sum_list` that takes a list of floats and returns their sum as a `float`.

7. **Task 6: Complex Types - Mixed List**  
   - **File:** [6-sum_mixed_list.py](./6-sum_mixed_list.py)  
   - **Description:** Write a type-annotated function `sum_mixed_list` that takes a list of integers and floats, and returns their sum as a `float`.

8. **Task 7: Complex Types - String and Int/Float to Tuple**  
   - **File:** [7-to_kv.py](./7-to_kv.py)  
   - **Description:** Write a type-annotated function `to_kv` that takes a string and an int/float, and returns a tuple where the second element is the square of the int/float.

9. **Task 8: Complex Types - Functions**  
   - **File:** [8-make_multiplier.py](./8-make_multiplier.py)  
   - **Description:** Write a type-annotated function `make_multiplier` that takes a float and returns a function that multiplies a float by the multiplier.

10. **Task 9: Duck Typing - First Element of a Sequence**  
    - **File:** [100-safe_first_element.py](./100-safe_first_element.py)  
    - **Description:** Write a duck-typed function `safe_first_element` that returns the first element of a sequence if it exists, otherwise `None`.

11. **Task 10: Type Checking**  
    - **File:** [102-type_checking.py](./102-type_checking.py)  
    - **Description:** Use MyPy to validate a function `zoom_array` that takes a tuple and a factor, and returns a list with elements repeated according to the factor.

## 📚 Resources

### Read or Watch:

- 📘 [Python 3 Typing Documentation](https://docs.python.org/3/library/typing.html)
- 📋 [MyPy Cheat Sheet](https://mypy.readthedocs.io/en/latest/cheat_sheet_py3.html)

## ⚙️ Setup Instructions

To get started with this project, follow these steps:

1. **Install Python**:
   - Make sure you have Python 3.7 installed on your system. If not, you can install it using the following commands:
     ```bash
     sudo apt-get update
     sudo apt-get install python3
     ```

2. **Clone the repository**:
   - Clone this project to your local machine:
     ```bash
     git clone https://github.com/Alogyn/alx-backend-python.git
     cd alx-backend-python/0x00-python_variable_annotations
     ```

3. **Make the script executable**:
   - Ensure that all your Python scripts are executable:
     ```bash
     chmod u+x *.py
     ```

4. **Run the code**:
   - You can test the code by running:
     ```bash
     ./main.py
     ```

## 🧑‍💻 Requirements

- Your code must follow **Pycodestyle** guidelines (version 2.5).
- All functions, classes, and modules must have proper documentation.
- The first line of all your files should be `#!/usr/bin/env python3`.
- All your files should be executable.

### Environment:

- All scripts will be interpreted/compiled on **Ubuntu 18.04 LTS** using **Python 3.7**.

## 📜 License

This project is licensed under the terms of the [MIT License](https://opensource.org/licenses/MIT).

---

© 2024 [ALX](https://www.alxafrica.com/). All rights reserved.
