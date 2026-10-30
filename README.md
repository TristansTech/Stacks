# C++ Stack Demo

A beginner C++ program that demonstrates how the Standard Template Library (STL) `stack` container works, using a stack of ages.

## What it does

1. Pushes several age values onto a stack
2. Prints the top element (the last age pushed)
3. Removes the top element with `pop()`
4. Prints the new top element
5. Prints and removes every remaining element until the stack is empty

## Concept: LIFO

A stack follows the **LIFO** principle: *last in, first out*. The last value pushed onto the stack is always the first one to come off.

| Function   | What it does                                  |
|------------|-----------------------------------------------|
| `push(x)`  | Adds `x` to the top of the stack              |
| `top()`    | Returns the element at the top of the stack   |
| `pop()`    | Removes the element at the top of the stack   |
| `empty()`  | Returns `true` if the stack has no elements   |

## How to run

Compile and run with g++:

```bash
g++ stack_demo.cpp -o stack_demo
./stack_demo
```

On Windows:

```bash
g++ stack_demo.cpp -o stack_demo.exe
stack_demo.exe
```

## Sample output

```
The last age pushed: 24
Top after calling pop function: 25
Remaining elements: 25 22 21 18 25
```

## Built with

- C++
- `<iostream>` and `<stack>` from the C++ Standard Library

## Author

Tristan Harper ([TristansTech](https://github.com/TristansTech))
