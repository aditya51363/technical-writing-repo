# Doxygen

Doxygen is a tool used to automatically generate documentation from source code. We can add specially formatted comments to our programs, and Doxygen uses these comments to create proper documentation for functions, classes and other parts of the code.

It is especially useful when working on larger projects where understanding and maintaining code becomes difficult.

## 1. Introduction to Doxygen
- What Doxygen is and why it is used.
- Supported languages like C, C++, Python and Java.
- Generating reference manuals and API documentation.

## 2. Features of Doxygen
- Extracting information from source code comments.
- Documenting functions, classes and modules.
- Creating call graphs and inheritance diagrams.
- Supporting Markdown, formulas and diagrams.

## 3. Installation and Setup
- Installing Doxygen on Windows, macOS and Linux.
- Checking the installation.
- Creating a configuration file (`Doxyfile`).
- Setting input and output options.

## 4. Documentation Comments

This is probably the most important part of Doxygen. We write specially formatted comments in our code so that Doxygen can understand and include them in the generated documentation.

Some commonly used tags are:
- `\brief` – Short description.
- `\param` – Description of a parameter.
- `\return` – Description of the return value.
- `\author` – Author information.
- `\version` – Version details.
- `\note` – Additional information.
- `\see` – Reference to related functions or sections.

We also looked at documenting classes and their member functions.

## 5. Generating Documentation
The basic process is quite simple:
- Add documentation comments to the source code.
- Create and configure the Doxyfile.
- Run Doxygen to generate the documentation.
- Open the generated files and explore them.

## 6. Output Formats

Doxygen supports different formats depending on how we want to use the documentation.

- HTML – View documentation in a browser.
- LaTeX/PDF – Printable documentation.
- XML, RTF and DocBook – Other supported formats.

## 7. Diagrams and Best Practices
Doxygen can also generate diagrams such as call graphs, include diagrams and inheritance diagrams. Graphviz can be used for generating these diagrams.

A few things to keep in mind:
- Write clear and meaningful descriptions.
- Document important functions and classes.
- Keep documentation consistent.
- Update comments whenever the code changes.

---

These are the main Doxygen concepts and features covered during the Technical Writing course.

