# NumPy From Zero

This repository documents my journey of learning NumPy from scratch.
The goal is not just to understand the theory, but to practice it through simple examples and gradually move into more practical use cases. I created this repository because I believe learning becomes more effective when it is documented, and hopefully it can also help others who are learning NumPy.

## What is NumPy?

NumPy (Numerical Python) is a powerful open-source library in Python used for numerical computations. It provides support for large, multi-dimensional arrays and matrices, along with a vast collection of high-level mathematical functions to operate on these arrays efficiently. It is the foundational package for scientific computing, machine learning, and data analysis in Python.

## Learning Path

- [x] [**1. Basic Arrays**](notes/01-basic-arrays.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/achmadhadikurnia/numpy-from-zero/blob/main/notes/01-basic-arrays.ipynb)
  - [x] 1.1 Array Creation (`np.array`, `np.zeros`, `np.ones`, `np.full`, `np.arange`, `np.linspace`, `np.eye`)
  - [x] 1.2 Array Attributes (`shape`, `size`, `ndim`, `dtype`)
  - [x] 1.3 Random Number Generation (`np.random`)
  - [x] 1.4 Array Manipulation (`reshape`, `flatten`, `astype`, `copy`)
- [x] [**2. Indexing & Slicing**](notes/02-indexing-and-slicing.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/achmadhadikurnia/numpy-from-zero/blob/main/notes/02-indexing-and-slicing.ipynb)
  - [x] 2.1 1D Array Indexing & Slicing
  - [x] 2.2 2D/3D Array Indexing & Slicing
  - [x] 2.3 Boolean Indexing (Masking)
  - [x] 2.4 Fancy Indexing
- [x] [**3. Mathematical Operations**](notes/03-mathematical-operations.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/achmadhadikurnia/numpy-from-zero/blob/main/notes/03-mathematical-operations.ipynb)
  - [x] 3.1 Element-wise Operations (Arithmetic)
  - [x] 3.2 Aggregation Functions (`sum`, `mean`, `max`, `min`, `std`)
  - [x] 3.3 Matrix Operations (Dot product, etc.)
  - [x] 3.4 Universal Math Functions (ufuncs) (`sqrt`, `exp`, `log`)
  - [x] 3.5 Rounding (`round`, `floor`, `ceil`)
  - [x] 3.6 Argmax and Argmin (`argmax`, `argmin`)
  - [x] 3.7 Advanced Statistics (Median & Percentiles)
  - [x] 3.8 Absolute Values (`np.abs`)
  - [x] 3.9 Value Clipping (`np.clip`)
  - [x] 3.10 Cumulative Computations (`np.cumsum`)
- [x] [**4. Broadcasting in NumPy**](notes/04-broadcasting.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/achmadhadikurnia/numpy-from-zero/blob/main/notes/04-broadcasting.ipynb)
  - [x] 4.1 Broadcasting with Scalars
  - [x] 4.2 The Rules of Broadcasting
  - [x] 4.3 Broadcasting Arrays of Different Shapes
  - [x] 4.4 Real-world Example: Data Normalization
- [ ] **Simple Mini Projects**
  - [ ] Data Normalization
  - [ ] Basic Image Manipulation (Arrays representing pixels)
  - [ ] Statistical Analysis on a dummy dataset

## Getting Started

### Run on Google Colab

You can run the notebooks directly in your browser without installing anything locally by clicking the **Open In Colab** badge next to each module in the Learning Path above.

### Run Locally

If you want to run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/achmadhadikurnia/numpy-from-zero.git
   cd numpy-from-zero
   ```

2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   # Windows
   python -m venv venv
   .\venv\Scripts\activate

   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

   > **💡 Editor Recommendation:**
   > It is highly recommended to use a VS Code-based text editor (such as **VS Code** or **Antigravity**) to run these notebooks. Simply open the `.ipynb` files directly in the editor and make sure you have the **Jupyter** extension installed for the best interactive experience.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
This is an ongoing project and will continue to be updated.

If you're also learning NumPy, feel free to explore, fork, or discuss 🙌
