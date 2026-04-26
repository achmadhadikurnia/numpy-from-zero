# NumPy From Zero

This repository documents my journey of learning NumPy from scratch. 
The goal is not just to understand the theory, but to practice it through simple examples and gradually move into more practical use cases. I created this repository because I believe learning becomes more effective when it is documented, and hopefully it can also help others who are learning NumPy.

## What is NumPy?

NumPy (Numerical Python) is a powerful open-source library in Python used for numerical computations. It provides support for large, multi-dimensional arrays and matrices, along with a vast collection of high-level mathematical functions to operate on these arrays efficiently. It is the foundational package for scientific computing, machine learning, and data analysis in Python.

## Learning Path

- [x] **Basic Arrays**
  - [x] Array Creation (`np.array`, `np.zeros`, `np.ones`, `np.full`, `np.arange`, `np.linspace`, `np.eye`)
  - [x] Array Attributes (`shape`, `size`, `ndim`, `dtype`)
  - [x] Array Manipulation (`reshape`, `astype`)
  - [x] Random Number Generation (`np.random`)
- [x] **Indexing & Slicing**
  - [x] 1D Array Indexing & Slicing
  - [x] 2D/3D Array Indexing & Slicing
  - [x] Boolean Indexing (Masking)
  - [x] Fancy Indexing
- [ ] **Mathematical Operations**
  - [ ] Element-wise Operations (Arithmetic)
  - [ ] Aggregation Functions (`sum`, `mean`, `max`, `min`, `std`)
  - [ ] Matrix Operations (Dot product, etc.)
- [ ] **Broadcasting**
  - [ ] Rules of Broadcasting
  - [ ] Broadcasting with Scalars and Arrays
- [ ] **Simple Mini Projects**
  - [ ] Data Normalization
  - [ ] Basic Image Manipulation (Arrays representing pixels)
  - [ ] Statistical Analysis on a dummy dataset

## Getting Started

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
