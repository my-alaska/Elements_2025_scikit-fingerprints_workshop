# Elements 2025 molecular ML workshop

Short introductory workshop for molecular ML and chemoinformatics.

If you are looking for expanded materials, see:
- [our longer workshop on molecular ML](https://github.com/j-adamczyk/molecular_ml_workshops)
- [scikit-fingerprints tutorials](https://scikit-fingerprints.readthedocs.io/latest/examples.html)

### Setup

Recommended way is to use [uv dependency manager](https://docs.astral.sh/uv/). To install it, follow the instructions
in the documentation. On Linux and macOS, this is just one line with curl and bash.

On Linux and macOS, run:
```commandline
uv venv && source .venv/bin/activate && uv sync
```

On Windows CMD, run:
```commandline
uv venv && .venv\Scripts\activate && uv sync
```

On Windows PowerShell, run:
```commandline
uv venv; .venv\Scripts\Activate.ps1; uv sync
```

If you prefer plain `venv` or to use Conda, use `requirements.txt`:
```commandline
pip install -r requirements.txt
```

### Code

Everything is in the Jupyter Notebook file `notebook.ipynb`. Run Jupyter Notebook
(in VS Code, PyCharm, or terminal + web browser) and open it there.

We also provide the `notebook_solution.ipynb` with exercise solutions. We recommend
not to use it until you went through the empty one yourself first.
