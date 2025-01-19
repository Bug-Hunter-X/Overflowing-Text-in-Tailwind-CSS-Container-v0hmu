# Overflowing Text in Tailwind CSS Container

This repository demonstrates a common layout issue in Tailwind CSS where long text overflows its container, disrupting the intended design.  The `bug.html` file showcases the problem, while `solution.html` provides a fix using Tailwind's built-in utilities.

## Problem
The initial code uses Tailwind CSS classes to style a container with a paragraph of text.  If the text exceeds the container's width, it will overflow, causing a poor user experience.

## Solution
The solution involves using Tailwind's `text-ellipsis` and `whitespace-nowrap` utilities to truncate the text and prevent wrapping, ensuring it stays within the bounds of its container.