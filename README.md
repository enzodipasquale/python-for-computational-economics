# Python for Computational Economics

Teaching notebooks for an introductory course on scientific computing in Python, with economics examples. They start from basic Python and build up to NumPy and PyTorch.

## Notebook map

- [`lecture0_python.ipynb`](notebooks/lecture0_python.ipynb) - Python syntax, scalar types, floating-point limits, lists/tuples/dictionaries, loops, comprehensions, functions, recursion, merge sort, and dynamic programming for knapsack.
- [`lecture1_numpy.ipynb`](notebooks/lecture1_numpy.ipynb) - NumPy arrays as tensors: shapes, dtypes, reductions over axes, slicing, fancy and boolean indexing, reshaping, broadcasting, matrix multiplication, linear algebra, value iteration, and policy iteration.
- [`lecture2_pytorch.ipynb`](notebooks/lecture2_pytorch.ipynb) - PyTorch tensors, strides, contiguous storage, views vs. copies, reshape/view behavior, CUDA checks, autograd, Jacobians/Hessians, MLE for a logit model, and a small neural-network classifier.

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebooks/
```

`torchviz` needs Graphviz installed separately (e.g. `brew install graphviz` on macOS).

## License

MIT.
