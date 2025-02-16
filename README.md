# The Dratini Programming Language

Dratini is a sister of the Python programming language designed to compile to native binaries 💝

## Preface

You're welcome to skip this section and head straight to [Getting Started](#getting-started) if you'd like.
This preface is here to explain some background information about the compiler's name, purpose, and design goals.

Dratini (DraTINI) stands for Dragon Transpiler, Interpreter, and Native-code Infrastucture.
The word "dragon" is in the name as a reference to the fact that the Dratini language is designed to be far more powerful than Python at the cost of a slightly-differing API and underlying implementation.
So far, there are currently no syntactical *(visual)* changes to the Dratini language.
This means that Dratini code is 100% identical to Python code at the moment.
However, this may potentially change in the future if the community collectively agrees on syntactical sugar valuable enough to the community to justify writing our own parser.

## Getting Started

If you follow the steps below, we'll have you up and running Dratini code in no time!

Each section has two sub-sections: `GitHub Desktop` and `git`.
`GitHub Desktop` sub-sections are for users who have installed and use the GitHub Desktop application *([Download `GitHub Desktop` for Linux](https://github.com/shiftkey/desktop/releases/latest) | [Download `GitHub Desktop` for Windows/Mac](https://desktop.github.com/download/))*.
The other sub-section, `git`, is for users who have installed and use the `git` command-line interface *([Download `git` for Linux/Windows/Mac](https://git-scm.com/downloads))*.

### Download the Project

First, please download the project using either `git` or GitHub Desktop.

#### GitHub Desktop:

For GitHub Desktop users, the project can be downloaded by clicking on the **(`<>` Code ↓)** button in the top-right-ish of [the repository page](https://github.com/dratini-lang/dratini) *(likely the page you're reading this on)* and then selecting `Open with GitHub Desktop`.

#### `git`:

For command-line `git` users, please run the following command:

```sh
git clone https://github.com/dratini-lang/dratini.git
```

### Open the Dratini SDK Project Directory/Folder

Next, you'll need to open the project directory/folder that you cloned in the previous step.

#### GitHub Desktop:

Please switch over to the the GitHub Desktop application, and follow these steps:
* Open/select the `dratini` repository if it's not already the open/selected repository.
* Right-click on the repository name in the top-left corner where it says `dratini` and click `Show in {Explorer/Finder/etc.}` *(whether it's `Explorer` or `Finder` depends on your operating system, i.e. Linux, Windows, Mac OS X, etc.)*

#### `git`:

You'll need to navigate to the cloned project directory using the `cd` command.

### Installation

Now that you've opened the folder, please run `install.py`, which is located inside the folder.

#### GitHub Desktop:

This can be done by double-clicking on the file named `install.py`.

#### `git`:

This can be done by running the following command:

```sh
python install.py
```

### Setup is Complete

Congratulations!
You've installed the Dratini SDK (Software Development Kit)!

From here, I highly recommend visiting [our ever-growing collection of examples](https://github.com/dratini-lang/examples)!
What happens next is up to you, friend 💝
