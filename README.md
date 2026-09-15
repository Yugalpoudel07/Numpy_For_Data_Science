# NumPy Basics

A hands-on Jupyter notebook covering the fundamentals of [NumPy](https://numpy.org/), the core library for numerical and scientific computing in Python. Includes explanations, code examples, and a few practice exercises.

## Contents

The notebook (`Numpy.ipynb`) walks through:

- **Introduction** — what NumPy is, and how NumPy arrays differ from Python lists
- **Creating Arrays** — `np.array`, `np.arange`, `np.ones`, `np.zeros`, `np.random`, `np.linspace`, `np.identity`, and reshaping into 1D/2D/3D/4D arrays
- **Array Attributes** — `ndim`, `shape`, `size`, `itemsize`, `dtype`
- **Changing Datatype** — `astype`
- **Array Operations** — scalar arithmetic and relational operations
- **Array Functions** — `sum`, `prod`, `max`, `min`, `mean`, `var`, trigonometric functions, `dot` (matrix product), `exp`, and rounding with `ceil`, `floor`, `round`
- **Indexing & Slicing** — accessing elements in 1D, 2D, and 3D arrays
- **Iterating** — looping over arrays of different dimensions
- **Reshaping** — `transpose` / `.T`
- **Stacking** — `hstack`, `vstack`
- **Images as Arrays** — loading an image with Pillow and converting it to a NumPy array

## Requirements

- Python 3.x
- [NumPy](https://numpy.org/)
- [Pillow](https://pypi.org/project/Pillow/) (for the image-to-array section)
- Jupyter Notebook or JupyterLab

Install dependencies:

```bash
pip install numpy pillow jupyter
```

## Usage

Clone the repo and launch the notebook:

```bash
git clone <your-repo-url>
cd <your-repo-folder>
jupyter notebook Numpy.ipynb
```

> Note: the image-array section expects an `images.jpg` file in the same directory as the notebook.

## License

Feel free to use and adapt this notebook for learning purposes.