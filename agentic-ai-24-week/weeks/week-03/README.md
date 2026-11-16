# Week 03 - Python Fundamentals

This folder contains the Week 3 Python Fundamentals module for the eCOMMart AI Squad program. It starts from the basics of programming and Python setup, then builds through variables, control flow, functions, exceptions, and collections. The week ends with six worked examples and twelve exercises, including a capstone order terminal and a mini agent tool.

## At a glance

| Field | Detail |
|---|---|
| Week | 3 of 24 |
| Theme | Python fundamentals |
| Program | eCOMMart AI Squad |
| Format | Lessons, worked examples, exercises, and supplemental slides |
| Prerequisites | None. Lesson 003 covers Python and VS Code setup. |
| Status | Materials added; review in progress |

## What you will learn

By the end of this week you should be able to:

- Explain what programming is and how Python code is executed.
- Install Python and VS Code, run scripts from the terminal, and use the interactive shell.
- Use variables, constants, literals, type conversion, and the `datetime` module.
- Apply operators, `if`/`elif`/`else`, `for` and `while` loops, and list comprehensions.
- Write functions with default values, positional and keyword arguments, `*args` and `**kwargs`, and understand scope.
- Handle errors with `try`/`except`/`else`/`finally`, `raise`, and `assert`.
- Work with lists, dictionaries, tuples, sets, and booleans.
- Build small eCOMMart programs and combine the week's concepts into a mini agent tool.

## Getting started

1. **Set up your tools.** Follow [003 - How to install Python](<01 - Introduction to Python/003_How_to_Install_Python.md>) to install Python, VS Code, and the Python extension.
2. **Open this folder in VS Code.** You will run lesson snippets, worked examples, and your own exercise files from here.
3. **Work through the lessons in order.** Start at `01 - Introduction to Python` and continue through `03 - Programming Building Blocks`.
4. **Run the worked examples.** Each one is a complete program you can run, trace, and modify.
5. **Attempt the exercises before reading the solutions.** Use the solutions only to check your approach.
6. **Review the supplemental slides and demos.** They reinforce the core lessons with additional examples.
7. **Record your notes.** Add key concepts, questions, and takeaways to `resource-notes.md`.

## Folder map

```text
week-03/
├── README.md                          # This file
├── resource-notes.md                  # Personal notes and open questions
├── 01 - Introduction to Python/       # Lessons 001-005
├── 02 - Variables, Literals and Constants/  # Lessons 006-009
├── 03 - Programming Building Blocks/
│   ├── A - Operators and Conditions/  # Lessons 010-013
│   ├── B - Loops/                     # Lesson 014
│   ├── C - Functions and Scope/       # Lessons 015-019
│   └── D - Collections/               # Lessons 020-025
├── 04 - Worked Examples/              # Six complete programs
├── 05 - Exercises/                    # Twelve exercises and solutions
└── more resources/
    └── Python fundamentals/           # Supplemental slides and demos
```

## Core lessons

| Section | Lessons | Link |
|---|---|---|
| 01 - Introduction to Python | 001-005: What programming is, Python, installation, Hello World, keywords, and identifiers | [Open folder](<01 - Introduction to Python>) |
| 02 - Variables, Literals and Constants | 006-009: Variables, constants, literals, data types, type conversion, date and time | [Open folder](<02 - Variables, Literals and Constants>) |
| 03A - Operators and Conditions | 010-013: Operators, `if`/`elif`/`else`, conditional statements, list comprehensions | [Open folder](<03 - Programming Building Blocks/A - Operators and Conditions>) |
| 03B - Loops | 014: `while` loops, user input, menus, and sentinel patterns | [Open lesson](<03 - Programming Building Blocks/B - Loops/014_While_Loops_and_User_Input.md>) |
| 03C - Functions and Scope | 015-019: Functions, arguments, `*args` and `**kwargs`, scope, exceptions | [Open folder](<03 - Programming Building Blocks/C - Functions and Scope>) |
| 03D - Collections | 020-025: Lists, dictionaries, tuples, sets, and booleans | [Open folder](<03 - Programming Building Blocks/D - Collections>) |

### Lesson map

| Section | Lessons |
|---|---|
| 01 - Introduction to Python | 001 What is programming?; 002 Python programming; 003 How to install Python; 004 Hello, World; 005 Python keywords and identifiers |
| 02 - Variables, Literals and Constants | 006 Variables and constants; 007 Literals; 008 Data types and type conversion; 009 Date and time |
| 03A - Operators and Conditions | 010 Operators; 011 `if`, `elif`, `else`; 012 Conditional statements; 013 List comprehensions |
| 03B - Loops | 014 While loops and user input |
| 03C - Functions and Scope | 015 Functions; 016 More functions; 017 `*args` and `**kwargs`; 018 Nested statements and scope; 019 Exceptions |
| 03D - Collections | 020 Lists; 021 Advanced lists; 022 Dictionaries; 023 Tuples; 024 Sets and booleans; 025 Advanced sets |

## Worked examples

The [worked examples](<04 - Worked Examples/worked_examples.md>) are complete, runnable programs. Read the explanation, trace the code, then run it yourself. Each example builds toward the mini agent tool.

| Example | Program | Key concepts |
|---|---|---|
| 1 | Product Card Printer | Variables, string types, f-strings, `print` |
| 2 | Customer Membership Tier Checker | `if`/`elif`/`else`, booleans, comparison operators |
| 3 | Shopping Cart with a List and Dictionary | Lists, dictionaries, `for` loops, arithmetic |
| 4 | Product Validator | Functions, docstrings, `is_nan`, `safe_eval`, `try`/`except` |
| 5 | Inventory Manager | Sets, `while` loops, menu-driven programs |
| 6 | eCOMMart Mini Agent Tool | All Week 3 concepts combined |

## Exercises

The [exercise set](<05 - Exercises/exercises.md>) contains twelve tasks across three levels. Attempt each one before opening the [solutions](<05 - Exercises/solutions.md>).

| Level | Exercises | Focus |
|---|---|---|
| Beginner | 1-4 | String types, price calculations, membership tiers, dictionaries |
| Intermediate | 5-8 | Tuples, sets, validation, functions, delivery zones |
| Advanced | 9-12 | Agent tool validation, comprehensions, exception handling, capstone order terminal |

## Supplemental resources

Extra slide decks and runnable demos from the Python fundamentals series are kept under [`more resources/Python fundamentals`](<more resources/Python fundamentals>).

| Module | Slides | Demos |
|---|---|---|
| 02 - Run Python and explore data types | [Open slides](<more resources/Python fundamentals/02/run-python-and-explore-data-types-slides.pdf>) | [Open demos](<more resources/Python fundamentals/02/demos/demos>) |
| 03 - Conditionals and imports | [Open slides](<more resources/Python fundamentals/03/conditionals-and-imports-slides.pdf>) | [Open demos](<more resources/Python fundamentals/03/demos/demos>) |
| 04 - Lists and loops | [Open slides](<more resources/Python fundamentals/04/lists-and-loops-slides.pdf>) | [Open demos](<more resources/Python fundamentals/04/demos/demos>) |
| 05 - Dictionaries, JSON, and pip | [Open slides](<more resources/Python fundamentals/05/dictionaries-json-and-pip-slides.pdf>) | [Open demos](<more resources/Python fundamentals/05/demos/demos>) |
| 06 - Functions | [Open slides](<more resources/Python fundamentals/06/functions-slides.pdf>) | [Open demos](<more resources/Python fundamentals/06/demos/demos>) |
| 07 - Classes and objects | [Open slides](<more resources/Python fundamentals/07/classes-and-objects-slides.pdf>) | [Open demos](<more resources/Python fundamentals/07/demos/demos>) |
| 08 - Working with files | [Open slides](<more resources/Python fundamentals/08/working-with-files-slides.pdf>) | [Open demos](<more resources/Python fundamentals/08/demos/demos>) |

## Suggested workflow

- [ ] Set up Python and VS Code with lesson 003.
- [ ] Work through lessons 001-025 in order.
- [ ] Run each of the six worked examples and trace what the code does.
- [ ] Complete exercises 1-4 at the beginner level.
- [ ] Complete exercises 5-8 at the intermediate level.
- [ ] Complete exercises 9-12 at the advanced level.
- [ ] Review the supplemental slides and run the demo scripts.
- [ ] Record key concepts and open questions in `resource-notes.md`.
- [ ] Update the week status in `ROADMAP.md` when review is complete.

## Content notes

- `012_Conditional_Statements.md` actually covers `for` loops, `range()`, `break`, `continue`, and `pass`, so it fits better with the loops section than with operators and conditions.
- `017_Args_and_Kwargs.md` refers to `022_More_Functions`, but the related lesson in this folder is `016_More_Functions.md`.
- Some lesson Markdown files show `?` where punctuation was lost during export. The technical content is still readable.
- Several lesson files reference diagrams under `img/` that were not included in this folder, so those images will not render.

## Related files

- [Resource notes](resource-notes.md)
- [Worked examples](<04 - Worked Examples/worked_examples.md>)
- [Exercises](<05 - Exercises/exercises.md>)
- [Exercise solutions](<05 - Exercises/solutions.md>)
- [Week 3 roadmap entry](../../ROADMAP.md)
- [Back to the 24-week guide](../../README.md)
