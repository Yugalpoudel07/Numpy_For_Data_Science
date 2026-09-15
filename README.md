# NumPy for Data Science

A hands-on beginner notebook for learning the foundations of [NumPy](https://numpy.org/), Python's core library for numerical and scientific computing. The examples focus on creating, inspecting, transforming, and working with multidimensional arrays (`ndarray`).

## Notebook

Open [Notebook/Numpy.ipynb](Notebook/Numpy.ipynb) to follow the lesson from start to finish.

## What you'll learn

- What NumPy is and why NumPy arrays differ from Python lists
- Creating 1D, 2D, 3D, and 4D arrays with `np.array`, `np.arange`, `np.ones`, `np.zeros`, `np.random`, `np.linspace`, and `np.identity`
- Controlling data types with `dtype` and converting them with `astype`
- Reading array properties: `ndim`, `shape`, `size`, `itemsize`, and `dtype`
- Reshaping arrays and calculating row- and column-wise values with `axis`
- Performing vectorized arithmetic, comparison, and mathematical operations
- Using aggregate functions such as `sum`, `prod`, `max`, `min`, `var`, and `mean`
- Applying trigonometric, exponential, and rounding functions (`sin`, `exp`, `ceil`, `floor`, and `round`)
- Computing matrix products with `np.dot`
- Indexing, slicing, and iterating through 1D, 2D, and 3D arrays
- Transposing arrays and combining them with `hstack` and `vstack`
- Loading an image with Pillow and representing it as a NumPy array

## Requirements

- Python 3.x
- [NumPy](https://numpy.org/)
- [Pillow](https://pypi.org/project/Pillow/) for the image example
- Jupyter Notebook or JupyterLab

Install the dependencies:

```bash
pip install numpy pillow jupyter
```

## Run locally

```bash
git clone <your-repository-url>
cd Numpy_For_Data_Science
jupyter notebook Notebook/Numpy.ipynb
```

Or, with JupyterLab:

```bash
jupyter lab Notebook/Numpy.ipynb
```

The notebook's image example uses `Notebook/images.jpg`; keep the notebook and image in the same folder when running it.

## Repository structure

```text
.
├── Notebook/
│   ├── Numpy.ipynb      # Lesson notebook
│   └── images.jpg       # Image used in the NumPy image-array example
├── Handwritten Notes/   # Supporting study notes
└── Resources/           # Additional learning resources
```

## License

This project is intended for learning. Feel free to use and adapt the material for educational purposes.
