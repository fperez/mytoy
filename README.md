# MyToy: a minimal Python package

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fperez/mytoy/HEAD?urlpath=lab)

This repository simply contains a minimal, toy Python package with a few files as illustration for students of how to lay out their code to meet minimal Python packaging requirements.

It has a single source directory (`mytoy`) with an `__init__.py` file and one "implementation" file (`toys.py`) as well as a few tests in `mytoy/tests`.

In addition to this `README.md` it includes some basic infrastructure: `LICENSE`, `requirements.txt`, `setup.py` and `.gitignore` files.

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

## Tests

You can run the project test suite via

```
pytest mytoy
```

## License

This project is released under the terms of the BSD 3-clause License.
