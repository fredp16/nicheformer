# nicheformer

This is the official repository for **Nicheformer: a foundation model for single-cell and spatial omics**

[![Preprint](https://img.shields.io/badge/preprint-available-brightgreen)]() &nbsp;

A rendered Jupyter book version of this repository will be available soon.

## Citation

If you use our tool or build upon our concepts in your own work, please cite it as

```
Schaar, A.C., Tejada-Lapuerta, A., et al. Nicheformer: a foundation model for single-cell and spatial omics. bioRxiv (2024)
```

## Installation

You need to have Python 3.9 or newer installed on your system. If you don't have
Python installed, we recommend installing [Mambaforge](https://github.com/conda-forge/miniforge#mambaforge).


<!--
1) Install the latest release of `nicheformer` from `PyPI <https://pypi.org/project/nicheformer/>`_:

```bash
pip install nicheformer
```
-->

Install the latest development version:

```bash
git clone https://github.com/theislab/nicheformer.git
cd nicheformer
pip install -e .
```
## Nicheformer data
We additionally provide a separate data repository that can be used to download and preprocess all publically available datasets used in the Nicheformer pretraining and for downstream tasks. Examplary scripts for accessing the datasets from the SpatialCorpus-110M are avaiable at https://github.com/theislab/nicheformer-data.

## Contact

For questions and help requests, you can reach out (preferably) on GitHub or email to the corresponding author. 



[issue-tracker]: https://github.com/theislab/nicheformer/issues
[changelog]: https://nicheformer.readthedocs.io/latest/changelog.html
[link-docs]: https://nicheformer.readthedocs.io
[link-api]: https://nicheformer.readthedocs.io/latest/api.html
