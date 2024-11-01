---
icon: bullseye-arrow
description: Install nain, see the stack and make a "Hello, World program"
cover: >-
  https://images.unsplash.com/photo-1728388939226-3fc095526a91?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHJhbmRvbXx8fHx8fHx8fDE3MzA0MTQ2OTl8&ixlib=rb-4.0.3&q=85
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Quickstart

## The stack

We use an efficient stack for you to boost your productivity.

It consists of:

* A classic GIT project setup containing:
  * `README.md`: Provides overview and instructions.
  * `LICENSE`: Specifies the project's license.
  * `nain.toml`: Configuration file for the project.
* Project Structure:
  * `src/main.na`: Main source file.
  * `lib/utils.na`: Utility functions. Comes with a colorizer for the terminal, and some other functions
* Seamless integration with NeoPack for easy publication of your program.

## Installing nain



Now, nain is made on \[the rust programming language]\(rust-lang.org), so you can use it's package manager, `cargo`.

We will not cover how to install cargo, but there are a lot of guides online.&#x20;



**If you have cargo installed**

```sh
cargo install nain-lang
```

**If you do not have cargo:**

1. Go to \[our GitHub repository releases]\([https://github.com/nainlang/nain/releases](https://github.com/nainlang/nain/releases))
2. Select the release for your OS (Operating System) **or** download the `.appimage` file.



## Making a hello world program

To create a "Hello, World!" program in Nain, follow these steps:

1. Create a new file named `hello.nain`.
2. Open the file in your preferred text editor.
3. Import the `studio` library using: `with lib studio`
4.  Add the `print` function: `print("Hello, World!")`



Now, the file **should look like this:**

{% code title="hello.nain" lineNumbers="true" %}
```python
with lib studio

print("Hello, World!")
```
{% endcode %}

### Analizing the hello world program, line by line

_Line 1:_ Imports the `studio` library, essential for any Nain program.

_Line 2:_ A blank line, they doesn't do anything, but make the code more readable.

_Line 3:_ Uses the `print` function from the `studio` library to print the text Hello, World to the screen

> **DANGER:** Always put text on **double quotes**, not single quotes, as single ones are for characters

## Conclusion

In this chapter, we've taken a close look at a simple "Hello, World!" program written in Nain. We dissected each line to understand its function and how it contributes to the overall execution of the program. Understanding these basics sets a strong foundation for building more complex programs in the future.

## Exercise

Make a program that prints 10 jokes

## Next Steps: Exploring Data Types

In the upcoming chapter, we will delve into the world of data types. Understanding data types is crucial as they define the kind of data that can be processed and manipulated within your programs. This knowledge will enable you to write more efficient and effective code. Stay tuned to learn about integers, strings, booleans, and more!
