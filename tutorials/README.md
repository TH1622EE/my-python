# Python Tutorials

This repository contains various tutorials specific to high-level Python programming with respect to syntax, semantics, architecture, etc. The following is a high-level table of contents which describes what the topics of the tutorial, each of which will will contain a collection of scripts/mmodules of example code and a README.md file describing the contents contained within. 

## Python Scripts, Modules, Libraries, and Frameworks

In Python, the terms *script*, *module*, *library*, and *framework* are often used interchangably and synonymous. However, this is inaccurate, and each of these terms has a contextually distinct meaning, but more importantly a distinct functionality and purpose. The following is an explanation of each:

### Scripts

A Python script is a single file (i.e., fileName.py) containing Python source code that is intended to be executed directly. Scripts are typically standalone programs designed to perform a specific task(s) such as automating a process, parsing data from an input file, running a small application, or simply to execute a singular operation.

### Modules

A Python module is any Python file (i.e., script) that can be impored and used in other Python code. It can and often does contain functions, classes, and variables. Modules allow a developer to organize your code into reusable components used to a more modular and maintainable codebase. Though a script is often used as a module, the distinction is that a script is a standalone Python file designed as standalone code to perform a singular, or multiple common tasks. Whereas, a *module* is a script which is designed to perform a collection of common tasks typically associated with the modules name, which are combined with other modules to create a library.

### Libraries

A Python library is a collection of modules that provide a set of related functionality. Libraries are often designed to solve specific problems or provide common utilities that can and often are designed to be reused across multiple projects. Libraries provide pre-written code for common tasks, such as data manipulation (e.g., pandas), numerical computation (e.g., numpy), or web requests (e.g., requests). A Python library is a collection of multiple modules/scripts designed to perform a variety of very specific and closely associated tasks.

### Frameworks

A Python *framework* is a comprehensive and structured set of libraries and tools designed to provide a foundation for building software applications. *Frameworks* often include predefined components that dictate the architecture of the application. *Frameworks* offer a standardized way of building and deploying complex applications by providing a skeleton structure and means of handling many low-level details which allows a developer to focus on the application logic. Examples of common Python *frameworks* include *Django* which is used for building web application; whereas, *Flask* is a *framework* used for web development.

### Hierarchial Relationships between Scripts, Modules, Libraries and Frameworks

1. Assume your intent is initially to write a script to simply parse text files to extract data you want to analyze.
2. After doing so, you realize you also need to write another script (i.e., module) to construct a data structure of the parsed data to allow further manipulation and analysis for which there is no existing module given the specific purpose of your program. Therefore, additional code is required to perform the desired tasks, but rather than writing a single script to perform **all** these tasks, you decide to write multiple scripts (i.e., modules), each of which contains code used for a common purpose. For example, one script is written to parse multiple types of formatted data (e.g., XML, YAML, JSON, Text, etc...). Another script is written to manipulate, clean, and format the data into a data structure which can be used ubiquitously for your project specific application.
3. As your project continues to grow, you now have a collection of modules (i.e., libraries) designed to perform a variety of specific tasks such as data manipulation (e.g., Pandas), numerical analysis (e.g., NumPy), and visualization (i.e., Matplotlib). At this point, the scope of your project has grown such that you now have a collection of libraries for which you would like to create a web application to provide a service with both a deprecated but free, and a paid version.
4. This collection of libraries and common utilities has now become a *framework* (e.g., Django) designed to solve a broad spectrum of common problem sets for a specific set of applications.

### Summary

The following describes the key differences between *scripts*, *modules*, *libraries*, and *frameworks* in Python:

<p align="center">
| Type | Definition | Use Case |
| :-- | :-- | :-- | :-- |
| Script | Standalone Python file | Performs a specific task(s) |
| Module | Collection of scripts | Imported to add additional functionality to another script |
| Library | Collection of modules | Provides a comprehensive set of reusable utilities |
| Framework | Collection of libraries and tools | Provides a reusable structure for a broad spectrum of solutions for large scale applications |
</p>

In conclusion, these terms are contextually specific and used to define the scale of the use-case for which the code is being developed. This hierarchy provides for a layered approach which keeps your Python projects organized, modular, scalable, and maintainable.