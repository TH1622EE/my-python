# Radio Frequency (RF) Microwave Engineering Library

This repository contains the modules contained within the RF/Microwave Engineering library. As explained in the [my-python/tutorials/README.md file](../../tutorials/README.md), libraries and modules are defined as follows:

**Libraries**

A Python library is a collection of modules that provide a set of related functionality. Libraries are often designed to solve specific problems or provide common utilities that can and often are designed to be reused across multiple projects. Libraries provide pre-written code for common tasks, such as data manipulation (e.g., pandas), numerical computation (e.g., numpy), or web requests (e.g., requests). A Python library is a collection of multiple modules/scripts designed to perform a variety of very specific and closely associated tasks.

**Modules**

 A Python module is any Python file (i.e., script) that can be imported and used in other Python code. It can and often does contain functions, classes, and variables. Modules allow a developer to organize your code into reusable components used to a more modular and maintainable codebase. Though a script is often used as a module, the distinction is that a script is a standalone Python file designed as standalone code to perform a singular, or multiple common tasks. Whereas, a *module* is a script which is designed to perform a collection of common tasks typically associated with the modules name, which are combined with other modules to create a library.

## Table of Contents

The following is a table listing each of the modules contained within the RF/Microwave Engineering library:

| Module | Description |
| :-- | :-- |
| constants.py | This module contains the physical constants used throughout other modules within the library. |
| emag.py | This module contains the classes specific to fundamental electromagnetics. |
| tlines.py | This module contains the classes specific to both lossy and lossless transmission line equations. |
| waveguides.py | This module contains the classes with equations specific to various types of waveguides. |
