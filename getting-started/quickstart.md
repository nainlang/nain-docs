---
description: Install nain, see the stack and learn the history of nain
icon: bullseye-arrow
cover: >-
  https://images.unsplash.com/photo-1728388939226-3fc095526a91?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHJhbmRvbXx8fHx8fHx8fDE3MzA0MTQ2OTl8&ixlib=rb-4.0.3&q=85
coverY: 0
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

Nain uses a tool called `nain-chains`for managing installs.

> **Note**: Nain-chains is the way we are using on this tutorial for installing nain

Now, nain is made on \[the rust programming language]\(rust-lang.org), so you can use it's package manager, `cargo`.

We will not cover how to install cargo, but there are a lot of guides online.&#x20;



**If you have installed**

```bash
cargo install nain-chains
```

**If you do not have cargo:**

1. **Clone the repo**

```bash
git clone https://github.com/nainlang/nain.git
```

