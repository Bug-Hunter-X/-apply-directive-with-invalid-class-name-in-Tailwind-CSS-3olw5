# @apply Directive with Invalid Class Name in Tailwind CSS

This repository demonstrates an uncommon error that can occur when using Tailwind CSS's `@apply` directive with a class name that is either misspelled, doesn't exist in your configuration, or is otherwise invalid.

## The Problem
The `@apply` directive is a powerful feature, but if you make a typo or use a class that's not defined, you won't necessarily get an error message.  Instead, you'll see unexpected or missing styling. This makes the error difficult to debug.

## Reproducing the Error
The `bug.html` file contains the problematic code using `@apply` with an invalid class name.

## Solution
The `solution.html` file shows the corrected code, ensuring the class name is valid and exists in your Tailwind CSS configuration.  Always double-check your class names, especially when using `@apply`.

## How to use:
1. Make sure you have node.js and npm installed.
2. Install Tailwind CSS according to the official documentation (https://tailwindcss.com/docs/guides/nextjs).
3. Run `npm install` to install the dependencies.
4. Open `bug.html` and `solution.html` in your browser and compare the results.