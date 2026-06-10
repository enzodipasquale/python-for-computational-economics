# Intro to Python, NumPy, and PyTorch

Teaching notebooks for an introductory course on scientific computing in Python. They start from zero and build up to NumPy and PyTorch, so no prior Python is needed.

## Notebooks

Work through them in order:

- `lecture0_python.ipynb` — variables and types, arithmetic, control flow, and how floating point actually works.
- `lecture1_numpy.ipynb` — creating arrays, shapes and dtypes, broadcasting, and reductions over axes.
- `lecture2_pytorch.ipynb` — tensors, contiguous storage and strides, views vs. copies, and reshaping.

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
