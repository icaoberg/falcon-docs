# FALCON Documentation

Sphinx documentation for [FALCON](https://github.com/icaoberg/falcon) — a Python implementation of the Feedback Adaptive Loop for Content-Based Retrieval algorithm.

> Leejay Wu, Christos Faloutsos, Katia P. Sycara, and Terry R. Payne. 2000. FALCON: Feedback Adaptive Loop for Content-Based Retrieval. In Proceedings of the 26th International Conference on Very Large Data Bases (VLDB '00).

FALCON is "a novel method that is designed to handle disjunctive queries within metric spaces. The user provides weights for positive examples; our system 'learns' the implied concept and returns similar objects."

## Building the Documentation

**HTML**

```bash
cd docs
make html
```

**PDF**

```bash
cd docs
make latexpdf
```

**Epub**

```bash
cd docs
make epub
```

## FALCON Package

The Python package is published on PyPI as `halcon`.

```bash
pip install halcon
```

To install from source:

```bash
git clone https://github.com/icaoberg/falcon.git
cd falcon
pip install .
```

To install in a conda environment:

```bash
conda create -n falcon-env python=3.11
conda activate falcon-env
pip install halcon
```

## Bugs and Questions

- Source code issues: https://github.com/icaoberg/falcon
- Documentation issues: https://github.com/icaoberg/falcon-docs

## License

Copyright 2014-2026 icaoberg at Carnegie Mellon University
