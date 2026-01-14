# Linear Algebra Scientific Calculator

A single-file web application for performing complex linear algebra computations. This tool is designed for students, educators, and engineers who need a quick, visual, and powerful way to manipulate matrices and explore vector spaces directly in the browser.

## Overview

This project is a "zero-dependency" scientific calculator. It is built entirely with vanilla HTML5, CSS3, and JavaScript. You do not need to install any libraries or run a local server; simply open the `Linear Algebra Scientific Calculator.html` file in any modern web browser to start calculating.

## Features

The calculator is divided into several specialized modules:

### 1. Matrices & Systems of Linear Equations

* **Matrix Operations**: Calculate Determinants, Inverses, Rank, Row Reduced Echelon Form (RREF), Transpose, and Trace.
* **System Solver**: Solves  using Gaussian elimination.
* **Least Squares**: Handles overdetermined systems by finding the best-fit solution via normal equations.
* **Matrix Multiplication**: Multiply two matrices of compatible dimensions.

### 2. Vector Spaces & Basis

* **Linear Independence**: Check if a set of vectors is linearly independent.
* **Basis Extraction**: Find the basis of the span of a set of vectors.
* **Rank Calculation**: Determine the dimension of the subspace spanned by the input vectors.

### 3. Linear Mappings (Transformations)

* **Transformation Analysis**: Visualize a linear mapping .
* **Kernel & Image**: Compute the basis for the Null Space (Kernel) and the Column Space (Image).
* **Composition**: Compute the matrix representing the composition of two linear transformations.

### 4. Affine Spaces

* **Membership Testing**: Check if a point  lies within an affine space defined by a base point  and a direction subspace .
* **Affine Coordinates**: Calculate the specific coordinates of a point relative to the affine frame.

## User Interface & Experience

* **Dynamic Grids**: Input matrices aren't just text areas; they are dynamic grids. Use the **Resize** buttons to change dimensions, and the input fields will update instantly.
* **Glassmorphism Design**: The UI uses CSS gradients and semi-transparent panels for a sleek, professional look.
* **Instant Feedback**: Results are printed in dedicated "Output" blocks below each section, formatted for readability (tab-separated values).
* **Example & Clear**: Use the "Example" button at the top to pre-fill the calculator with a complex scenario to see how the math works, or "Clear" to start fresh.

## Technical Implementation

* **Matrix Engine**: The JavaScript contains a custom-built math engine for matrix manipulation (RREF, Matrix Multiplication, and Inverse calculation using Gauss-Jordan elimination).
* **Precision**: Uses a formatting helper to handle floating-point rounding errors common in JavaScript, ensuring results like `0.0000000000001` are displayed as a clean `0`.
* **Responsive CSS**: Uses CSS Grid and Variables to ensure the interface looks great on both desktops and tablets.

## How to Use

1. **Download** the `Linear Algebra Scientific Calculator.html` file.
2. **Double-click** the file to open it in your preferred browser.
3. **Input** your data into the grids.
4. **Click** the function button (e.g., `det(A)` or `Solve Ax = b`) to see the result instantly.

## License
[GNU Lesser General Public License v2.1](LICENSE) - Feel free to use and modify
