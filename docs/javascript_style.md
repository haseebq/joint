JavaScript Style Guide
======================

This document lays out conventions for JavasScript in the Joint source code.

## General
* All code must be tested with JSHint, passing completely. JSHint is slightly more liberal with coding style than JSLint while providing the same type of static analysis for error checking.
* Indent with 2 spaces. Never use tabs.
* Use a maximum 79 characters per line. This limits confusing nesting, among other things.
* Use line breaks between function definitions.
* Use 1 space before and after assignment operators.
* Use 1 space before and after function argument lists in declarations.
* Use 1 space before and after outer parens in conditionals and argument lists.
* Don't use spaces after `{`, `[`, or `(` or before `}`, `]`, or `)`.
* Terminate all expressions with semicolons.
* Always use `var` when initializing a variable. All variables should be local to the current scope.

## Naming conventions
* Variable and function names should start with a lowercase letter and use camelCase.
* Keep variable names short but descriptive.
