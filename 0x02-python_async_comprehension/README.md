# 0x02. Python - Async Comprehension 🐍

Welcome to the **Async Comprehension** project, part of the ALX Backend Python curriculum. In this project, you will explore asynchronous programming in Python, focusing on asynchronous generators, comprehensions, and type annotations.

## 📝 Learning Objectives

By completing this project, you will:

- ✨ **Write Asynchronous Generators:** Learn how to create asynchronous generators in Python.
- 🧑‍💻 **Use Async Comprehensions:** Master the use of async comprehensions to collect data from asynchronous generators.
- 🛠️ **Type-Annotate Generators:** Understand how to use Python type annotations with generators and async functions.

## 📂 Project Structure

This project includes the following tasks:

1. **Task 0: Async Generator**  
   - **File:** [0-async_generator.py](./0-async_generator.py)  
   - **Description:** Write a coroutine `async_generator` that loops 10 times, waits for 1 second asynchronously, and yields a random number between 0 and 10.

2. **Task 1: Async Comprehensions**  
   - **File:** [1-async_comprehension.py](./1-async_comprehension.py)  
   - **Description:** Write a coroutine `async_comprehension` that collects 10 random numbers using an async comprehension over `async_generator` and returns them.

3. **Task 2: Run Time for Four Parallel Comprehensions**  
   - **File:** [2-measure_runtime.py](./2-measure_runtime.py)  
   - **Description:** Write a coroutine `measure_runtime` that executes `async_comprehension` four times in parallel using `asyncio.gather` and returns the total runtime.

## 📚 Resources

### Read or Watch:

- 📘 [PEP 530 – Asynchronous Comprehensions](https://www.python.org/dev/peps/pep-0530/)
- 📚 [What’s New in Python: Asynchronous Comprehensions / Generators](https://www.blog.pythonlibrary.org/2017/02/14/whats-new-in-python-asynchronous-comprehensions-generators/)
- 🔧 [Type-hints for Generators](https://stackoverflow.com/questions/42531143/how-to-type-hint-a-generator-in-python-3)

## ⚙️ Setup Instructions

To get started with this project, follow these steps:

1. **Install Python 3.7**:
   - You can install Python 3.7 on Ubuntu 18.04 LTS using the following commands:
     ```bash
     sudo apt update
     sudo apt install python3.7
     ```

2. **Clone the repository**:
   - Clone this project to your local machine:
     ```bash
     git clone https://github.com/Alogyn/alx-backend-python.git
     cd alx-backend-python/0x02-python_async_comprehension
     ```

3. **Run the Python scripts**:
   - You can run the provided Python scripts using the following commands:
     ```bash
     ./0-main.py
     ./1-main.py
     ./2-main.py
     ```

4. **Verify your environment**:
   - Ensure that your code follows the `pycodestyle` guidelines (version 2.5.x) by running:
     ```bash
     pycodestyle <filename.py>
     ```

## 🧑‍💻 Requirements

- All files should be interpreted on **Ubuntu 18.04 LTS** using **Python 3.7**.
- All your files should end with a new line.
- All your functions and coroutines must be type-annotated.
- Your code should follow the **pycodestyle** style (version 2.5.x).

### Environment:

- This project will be executed on **Ubuntu 18.04 LTS** using **Python 3.7**.

## 📜 License

This project is licensed under the terms of the [MIT License](https://opensource.org/licenses/MIT).

---

© 2024 [ALX](https://www.alxafrica.com/). All rights reserved.
