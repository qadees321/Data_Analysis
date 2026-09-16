# Python Practice Notebooks 🐍

This repo is a collection of Jupyter notebooks I've been using to practice Python fundamentals — basically my personal playground while learning the language. Each notebook focuses on a different chunk of core concepts, with short tasks/exercises and my solutions to them.

## What's inside

### 📘 `python_basics.ipynb`
The starting point — covers the absolute basics:
- `print()` statement variations (`sep`, `end` parameters)
- Variables, variable naming rules, and reassignment
- Data types and type checking with `type()`
- Taking user input with `input()`
- String concatenation and formatting (f-strings, `.format()`)
- Swapping variables (with and without a third variable)
- A bunch of small "guess the output" and mini-program exercises

### 📗 `operators_and_modules.ipynb`
Builds on the basics with operators and a couple of standard library modules:
- Arithmetic, assignment, relational, membership, identity, and bitwise operators
- Practical mini-programs: calculators, discount/salary calculators, bank balance tracker, gym fee calculator, e-wallet simulation, etc.
- Intro to Python modules — working with `datetime` and `random` (e.g. an expiry date tracker and a simple OTP generator)

### 📙 `container_data_types.ipynb`
All about Python's built-in data structures:
- **Lists** — indexing, slicing, `append()`, `insert()`, `remove()`, `pop()`
- **Tuples** — immutability, `count()`, `index()`
- **Sets** — uniqueness, `union()`, `intersection()`, `difference()`
- **Dictionaries** — key-value access, `.keys()`, `.values()`, `.items()`
- Practice tasks for each data type: grocery stock tracker, playlist manager, apartment/payroll records, unique visitor counter, student performance tracker, and more

### 📕 `Conditional_statemtents_and_loops.ipynb`
Getting into control flow — `if`/`else`, `for`, and `while` loops:
- Using `for` loops with conditions (e.g. printing multiples, summing even numbers)
- `while` loops with `break` — password retry system, countdown timer, finding numbers divisible by multiple values
- Comprehension basics sneak in here too (dictionary and list comprehension)
- Small systems built with conditionals: a student grade system, a list categorizer, and a FizzBuzz-style dictionary generator

### 📓 `comprehension_functions_and_type_hunting.ipynb`
The most advanced notebook so far — comprehensions and functions:
- **List, dictionary, and set comprehension** — filtering, transforming, and building collections in one line
- **Functions** — defining reusable functions, return values, and input validation
- A `prime_upto(n)` function to generate primes with validation
- Timing code execution using the `time` module
- A number-analysis function that returns total, average, max, min, and evens in one dictionary
- A mini "Email Filtering System" combining list comprehension and set comprehension together

## Why this repo exists

I'm learning Python step by step, and rather than losing my exercises in random files, I wanted a clean place to track my progress and look back on how I solved each task. If you're learning too, feel free to browse through, borrow ideas, or fork it and try the tasks yourself before peeking at the solutions!

## How to use

1. Clone the repo
2. Open any notebook in Jupyter Notebook / JupyterLab / VS Code
3. Run the cells top to bottom — most tasks include the problem statement as a docstring/comment right above the code

## Requirements

Just Python 3 and Jupyter. No external libraries needed — everything here uses the standard library.

---

*Work in progress — more notebooks will be added as I keep learning!*
