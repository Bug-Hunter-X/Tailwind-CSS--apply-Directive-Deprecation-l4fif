# Tailwind CSS @apply Directive Deprecation

This repository demonstrates the deprecation of the `@apply` directive in Tailwind CSS v3 and provides a solution.

## Problem

The `@apply` directive, used to apply custom CSS classes defined in your Tailwind configuration, is no longer supported in Tailwind CSS v3.  Using it will result in build errors or unexpected styling.

## Solution

The solution is to directly apply the required utility classes to your HTML elements instead of using `@apply`.

## Usage

1. Clone the repository.
2. Open `bug.html` to see the deprecated code example.
3. Open `bugSolution.html` to see the updated code that applies utility classes directly.