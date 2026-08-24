# Computation with NumPy and N-Dimensional Arrays

A hands-on Jupyter Notebook covering the fundamentals of **NumPy**, N-dimensional arrays, array manipulation, linear algebra, and basic image processing.

## 📌 Overview

This project is based on practical exercises and challenges designed to build a strong understanding of NumPy and how it can be used for numerical computing and data manipulation in Python.

The notebook progresses from basic 1D arrays to multidimensional arrays, slicing, vector operations, matrix multiplication, and image manipulation using NumPy arrays.

## 📚 Topics Covered

### 1. NumPy `ndarray`

* Creating NumPy arrays
* 1-dimensional arrays (vectors)
* 2-dimensional arrays (matrices)
* N-dimensional arrays (tensors)
* Understanding:

  * `.ndim`
  * `.shape`
  * Array indexing
  * Multidimensional indexing

### 2. NumPy Slicing

Practical exercises using slicing techniques to:

* Extract the last few elements
* Select specific ranges
* Create subsets
* Select every second element
* Reverse arrays

Example:

```python
a[::2]
```

### 3. Array Indexing

Working with specific elements and coordinates in multidimensional arrays.

The notebook also covers finding the indices of non-zero elements using:

```python
np.nonzero()
```

### 4. Creating Arrays

Using NumPy functions such as:

* `np.arange()`
* `np.random.random()`
* `np.linspace()`

These are used to create sequences, random arrays, and evenly spaced values.

### 5. Data Visualization

Using **Matplotlib** to visualize NumPy arrays and numerical data.

Examples include:

* Line plots
* Displaying random arrays as images
* Displaying image data using `plt.imshow()`

### 6. Linear Algebra

Introduction to vector operations and matrix calculations.

Topics include:

* Vector multiplication
* Python lists vs NumPy arrays
* Broadcasting
* Scalar operations
* Matrix multiplication

Matrix multiplication is demonstrated using:

```python
np.matmul(a, b)
```

and:

```python
a @ b
```

### 7. Image Manipulation

Images are treated as NumPy arrays so that their underlying pixel values can be manipulated.

The notebook explores:

* Image dimensions
* Image shape
* Pixel values
* Converting images to grayscale
* Flipping images
* Rotating images
* Inverting image colors

For example:

```python
plt.imshow(255 - img_arr)
```

inverts the pixel values of an image.

### 8. Working with Your Own Images

The notebook also demonstrates how to load an image using **PIL (Pillow)** and convert it into a NumPy array:

```python
img = Image.open(file_name)
img_arr = np.array(img)
```

This allows the image to be manipulated using NumPy operations.

## 🛠️ Technologies Used

* Python
* NumPy
* Matplotlib
* SciPy
* Pillow (PIL)
* Jupyter Notebook

## 🎯 Learning Objectives

By completing this notebook, you should be able to:

* Understand NumPy's `ndarray`
* Work with vectors, matrices, and N-dimensional arrays
* Understand array dimensions and shapes
* Perform indexing and slicing
* Generate numerical arrays
* Perform basic vector and matrix operations
* Understand matrix multiplication
* Use NumPy for basic image manipulation
* Visualize numerical data with Matplotlib

## 📂 Project Structure

```text
.
├── Computation_with_NumPy_and_N_Dimensional_Arrays_.ipynb
└── README.md
```

## 🚀 Getting Started

Clone the repository and open the notebook using Jupyter Notebook or JupyterLab.

Install the required libraries if necessary:

```bash
pip install numpy matplotlib scipy pillow
```

Then launch Jupyter:

```bash
jupyter notebook
```

Open:

```text
Computation_with_NumPy_and_N_Dimensional_Arrays_.ipynb
```

## 📈 What's Next?

This notebook provides a foundation for working with numerical data in Python. The concepts learned here can be applied to:

* Data Analysis
* Data Science
* Machine Learning
* Scientific Computing
* Computer Vision
* Image Processing

---

**Learning Python, NumPy, and Data Science one step at a time. 🐍📊**
