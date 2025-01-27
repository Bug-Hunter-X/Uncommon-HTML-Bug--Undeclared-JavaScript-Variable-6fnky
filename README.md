# Uncommon HTML Bug: Undeclared JavaScript Variable

This repository demonstrates a common yet easily overlooked error in HTML when using JavaScript: attempting to use a variable or function before it's declared.  This often leads to unexpected behavior and runtime errors.  The `bug.html` file showcases the issue, while `bugSolution.html` presents the corrected code.

## Bug Description

The bug lies in the usage of the JavaScript variable `myVar` within an HTML context without first declaring or initializing it.  Modern JavaScript environments typically don't implicitly initialize variables, resulting in a `ReferenceError` when the code tries to access `myVar` before assigning it a value.

## Solution

The solution involves ensuring that the JavaScript variable `myVar` is declared and, optionally, initialized before being referenced in the HTML's JavaScript section or in a linked script file.