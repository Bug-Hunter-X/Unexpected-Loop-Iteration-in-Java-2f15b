# Unexpected Loop Iteration in Java

This repository demonstrates a common, yet subtle, error in Java's while loops involving the post-increment operator (++). The `Bug.java` file contains code that exhibits the unexpected behavior. The `BugSolution.java` provides a correction and explanation.

## Problem Description

The issue lies in the usage of the post-increment operator (`x++`) within the loop condition. This leads to an additional iteration, resulting in ten iterations rather than the expected nine.

## Solution

The solution, found in `BugSolution.java`, involves either using a pre-increment operator (`++x`), changing the comparison operator, or restructuring the loop to explicitly control the number of iterations.
