# 0x01. Python - Async ⚡

Welcome to the **Python - Async** project, part of the ALX Backend Python curriculum. In this project, you will explore the power of asynchronous programming in Python, using async and await syntax, coroutines, and tasks to manage concurrent operations.

## 📝 Learning Objectives

By completing this project, you will:

- ⏳ **Understand Async/Await Syntax:** Learn how to write and execute asynchronous programs in Python using `async` and `await`.
- 🤖 **Execute Concurrent Coroutines:** Run coroutines concurrently using `asyncio` and manage their execution efficiently.
- 🛠️ **Create Asyncio Tasks:** Learn how to create and handle asyncio tasks to perform asynchronous actions.
- 🎲 **Use the Random Module:** Implement functions using `random.uniform` to generate random values for asynchronous delays.

## 📂 Project Structure

This project includes the following:

1. **Task 0: The Basics of Async**  
   - **File:** [0-basic_async_syntax.py](./0-basic_async_syntax.py)  
   - **Description:** Write an asynchronous coroutine `wait_random` that waits for a random delay between 0 and `max_delay` seconds and returns it. 
     - Use the `random` module to generate the delay.

2. **Task 1: Let's Execute Multiple Coroutines at the Same Time**  
   - **File:** [1-concurrent_coroutines.py](./1-concurrent_coroutines.py)  
   - **Description:** Write an async routine `wait_n` that takes two integers `n` and `max_delay`, spawns `wait_random` `n` times, and returns a list of all delays in ascending order.

3. **Task 2: Measure the Runtime**  
   - **File:** [2-measure_runtime.py](./2-measure_runtime.py)  
   - **Description:** Write a function `measure_time` that measures the total execution time for `wait_n(n, max_delay)` and returns the average time per coroutine.

4. **Task 3: Tasks**  
   - **File:** [3-tasks.py](./3-tasks.py)  
   - **Description:** Write a function `task_wait_random` that takes an integer `max_delay` and returns an asyncio task.

5. **Task 4: More Tasks**  
   - **File:** [4-tasks.py](./4-tasks.py)  
   - **Description:** Write a function `task_wait_n` that is similar to `wait_n` but uses `task_wait_random` instead of `wait_random`.

## 📚 Resources

### Read or Watch:

- 📘 [Async IO in Python: A Complete Walkthrough](https://realpython.com/async-io-python/)
- 📚 [asyncio - Asynchronous I/O](https://docs.python.org/3/library/asyncio.html)
- 🎲 [random.uniform](https://docs.python.org/3/library/random.html#random.uniform)

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
     cd alx-backend-python/0x01-python_async_function
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

- Your code must follow **Pycodestyle** guidelines (version 2.5.x).
- All functions and coroutines must be type-annotated.
- All modules, functions, and coroutines must have proper documentation.
- The first line of all your files should be `#!/usr/bin/env python3`.
- All your files should be executable.

### Environment:

- All scripts will be interpreted/compiled on **Ubuntu 18.04 LTS** using **Python 3.7**.

## 📜 License

This project is licensed under the terms of the [MIT License](https://opensource.org/licenses/MIT).

---

© 2024 [ALX](https://www.alxafrica.com/). All rights reserved.
