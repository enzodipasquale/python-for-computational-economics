# Intro to Python, NumPy, and PyTorch

Welcome! This repository contains beginner-friendly Jupyter notebooks designed to teach the fundamentals of Python programming, numerical computing with NumPy, and tensor operations with PyTorch. The materials are suitable for anyone interested in scientific computing, data science, or machine learning—no prior experience required.

## 🎯 What You'll Learn

By working through these notebooks, you will:
- **Master Python basics**: Variables, data types, arithmetic, and control flow
- **Work with NumPy**: Efficient array operations, broadcasting, and basic linear algebra
- **Explore PyTorch**: Tensors, memory layout, and essential tensor manipulations

## 📚 Notebook Overview

### Lecture 0: Python Fundamentals
- Defining variables and basic data types (`str`, `int`, `float`, `bool`)
- Printing, string concatenation, and arithmetic operations
- Comparisons and boolean logic
- Floating-point representation and its limits in Python
- Using the `sys` module to inspect float info

### Lecture 1: NumPy for Numerical Computing
- Introduction to NumPy and its efficiency
- What is a tensor? (mathematical and practical perspective)
- Creating arrays: `np.array`, `np.zeros`, `np.ones`, `np.arange`, `np.linspace`, `np.random`
- Array data types, shape, and attributes (`shape`, `size`, `dtype`, `ndim`)
- Array methods: `mean()`, `sum()`, `max()`, `argmax()`
- Summing over array axes and basic aggregations

### Lecture 2: PyTorch for Tensors
- Introduction to PyTorch tensors
- Contiguous memory and tensor storage
- Creating and inspecting tensors (shape, stride, contiguity)
- View vs copy in tensors
- Tensor operations: `.view()`, `.expand()`, `.unsqueeze()`, `.squeeze()`, `.transpose()`, `.permute()`
- Difference between `.view()` and `.reshape()`
- Handling errors with tensor reshaping

## 📋 Prerequisites

- Curiosity and willingness to learn
- Basic familiarity with programming concepts is helpful, but not required
- No prior experience with Python, NumPy, or PyTorch needed

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/enzodipasquale/intro-to-python.git
cd intro-to-python
```

### 2. Set up your environment

#### Using `venv` (recommended)
```bash
python3 -m venv myenv
source myenv/bin/activate  # On Windows: myenv\Scripts\activate
pip install -r requirements.txt
```

#### Or with Conda
```bash
conda create -n intro-python python=3.9
conda activate intro-python
conda install numpy pytorch torchvision torchaudio -c pytorch
pip install torchviz graphviz jupyter ipykernel
```

### 3. Install the Jupyter kernel
```bash
python -m ipykernel install --user --name=intro-python --display-name "Intro Python"
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook notebooks/
```

## 📦 Dependencies

All required packages are listed in `requirements.txt`:
- `numpy` - Numerical computing
- `torch`, `torchvision`, `torchaudio` - PyTorch ecosystem
- `torchviz`, `graphviz` - Computational graph visualization
- `jupyter`, `ipykernel` - Jupyter notebook environment

**Note:** For `torchviz` to work, you may need to install Graphviz system-wide:
- **macOS**: `brew install graphviz`
- **Ubuntu**: `sudo apt-get install graphviz`
- **Windows**: Download from [graphviz.org](https://graphviz.org/download/)

## 📖 How to Use These Notebooks

1. Work through the notebooks in order: `lecture0_python.ipynb` → `lecture1_numpy.ipynb` → `lecture2_pytorch.ipynb`
2. Run all code cells and experiment by modifying them
3. Use the notebooks as a reference for your own projects

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome! Feel free to open issues or submit pull requests.

## 📄 License

This material is provided for educational purposes and is open for public use and modification.

