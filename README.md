# NumPy Fundamentals and Array Operations

This project demonstrates core concepts and operations using the NumPy library in Python. It covers array creation, manipulation, mathematical operations, and basic data handling techniques commonly used in data science and scientific computing.

---

## Overview

The purpose of this project is to provide practical examples of working with NumPy arrays, including single-dimensional and multi-dimensional arrays, array initialization techniques, mathematical computations, and data persistence.

---

## Features

* Creation of single-dimensional and multi-dimensional arrays
* Array initialization using zeros, full values, ranges, and random numbers
* Array reshaping and matrix construction
* Horizontal and vertical stacking of arrays
* Set operations such as intersection and difference
* Element-wise arithmetic operations
* Statistical computations including mean, median, and standard deviation
* Saving and loading NumPy arrays to and from files
* Basic conditional logic implementation in Python

---

## Technologies Used

* Python
* NumPy

---

## Code Highlights

### Array Creation

* One-dimensional arrays using `np.array()`
* Multi-dimensional arrays (matrices)

### Array Initialization

* `np.zeros()` for zero-filled arrays
* `np.full()` for constant values
* `np.arange()` for sequences with step control
* `np.random.randint()` for random number generation

### Array Manipulation

* Combining arrays using:

  * `np.vstack()`
  * `np.hstack()`
  * `np.column_stack()`

### Set Operations

* Intersection using `np.intersect1d()`
* Difference using `np.setdiff1d()`

### Mathematical Operations

* Element-wise operations such as addition, subtraction, multiplication, and division
* Aggregation using `np.sum()` with axis control

### Statistical Functions

* Mean using `np.mean()`
* Standard deviation using `np.std()`
* Median using `np.median()`

### File Operations

* Saving arrays using `np.save()`
* Loading arrays using `np.load()`

---

## Project Structure

```bash id="n2k8sd"
numpy-fundamentals/
│── main.py
│── Spriha.npy
│── README.md
```

---

## How to Run

1. Install NumPy:

```bash id="f3k91d"
pip install numpy
```

2. Run the script:

```bash id="k91xlp"
python main.py
```

---

## Notes

* Ensure Python is properly installed before running the script
* The saved NumPy file (`.npy`) will be generated in the project directory
* Modify input values or array sizes to experiment with different outputs

---

## Future Improvements

* Extend to advanced NumPy topics such as broadcasting and vectorization
* Integrate with Pandas for data analysis workflows
* Add visualization using Matplotlib
* Optimize performance for large-scale datasets

---

## License

This project is intended for educational purposes and can be used for learning and reference.
