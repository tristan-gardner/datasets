# Notebooks/scripts creating decay datasets for radioactivedecay

This repo contains Jupyter Notebooks that process raw decay data from
different sources and creates dataset files suitable for radioactivedecay.

Currently implemented are:

- ICRP-107: in the ``icrp107_ame2020_nubase2020`` directory.
- PyNE: scrapes decay data from PyNE v0.7.5 for a
[comparison](https://github.com/radioactivedecay/comparisons/tree/main/pyne) of
decay calculation results between PyNE and radioactivedecay (``pyne``
directory).
