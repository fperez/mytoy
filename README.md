# My Toy Package

Note: this repository simply contains a minimal Python package with a few files as illustration for students.

It has a single source directory (`mytoy`) with an `__init__.py` file and one "implementation" file (`toys.py`) as well as a few tests in `mytoy/tests`, as well as a `LICENSE`, `requirements.txt` and `setup.py`.

This is more or less the absolute minimum for a "real" python package that can be installed from source, tested and experimented with on Binder.

The only docs included are this `README.md` file - a larger package would have a proper docs directory and associated Sphinx/JupyterBook build.


## Installation

This project can currently only be installed from source, via

```
pip install .
```

or for a development installation via


```
pip install -e .
```

## License

This project is released under the terms of the BSD 3-clause License.
