# Python Decorator Example

A simple yet illustrative example of how to use **decorators** in Python.

## 🧠 What is This?

This small project demonstrates the concept of **function decorators** in Python. It shows how you can wrap a function with additional behavior — such as logging or timing — without modifying its internal logic.

---

## 🧩 How It Works

The program defines a decorator called `@decorator`, which wraps the `greet()` function. When `greet()` is called, it prints:

### 🔍 Code Breakdown

- **`decorator(func)`**: A higher-order function that takes another function as input.
- **`wrapper()`**: Inner function that extends the behavior of `func()`.
- **`@decorator`**: Syntactic sugar to apply the decorator to the `greet()` function.
- **`greet()`**: The decorated function that simply prints "Hello, World!".

---

## 📁 Project Structure

python-decorator-example/
└── greet.py

- `greet.py`: Contains the full implementation of the decorator and the greeting function.

---

## ▶️ How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/Soumyadeeps006/python-decorator-example.git

2. Navigate to the directory:

    ```bash
    cd python-decorator-example
    ```

3. Run the script:

    ```bash
    python greet.py
    ```

4. You should see the following output:

    ```bash
    Before calling the function
    Hello, World!
    After calling the function
    ```