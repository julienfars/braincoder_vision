Welcome to Braincoder's documentation! (this is a fork to adapt code to a specific setup)
======================================

**Braincoder** is a package to fit encoding models to neural data (for now fMRI) and
to then *invert* those models to decode stimulus information from neural data.

Important links
===============

- Official source code repo: https://github.com/Gilles86/braincoder/tree/main
- HTML documentation (stable release): https://braincoder-devs.github.io/

Installation
============

Note that you need an environment with both `tensorflow-probability` and
`tensorflow`.

Set up conda environment and install Braincode
-----------------

.. code-block:: bash

        # Install 
        conda create --name braincoder tensorflow-probability tensorflow -c conda-forge
        conda activate braincoder
        pip install git+https://github.com/Gilles86/braincoder.git

How to Cite
===========

If you use **Braincoder** in your research, please cite it using the following information:

> de Hollander, G., Renkert, M., Ruff, C. C., & Knapen, T. H. (2024). *Braincoder: A package for fitting encoding models to neural data and decoding stimulus features*. `Zenodo <https://doi.org/10.5281/zenodo.10778413>`_. DOI: `10.5281/zenodo.10778413 <https://doi.org/10.5281/zenodo.10778413>`_.

Alternatively, use this BibTeX entry:

.. code-block:: bibtex

    @software{deHollander2024braincoder,
      author       = {Gilles de Hollander and Maike Renkert and Christian C. Ruff and Tomas H. Knapen},
      title        = {braincoder: A package for fitting encoding models to neural data and decoding stimulus features},
      year         = {2024},
      publisher    = {Zenodo},
      doi          = {10.5281/zenodo.10778413},
      url          = {https://github.com/Gilles86/braincoder}
    }

By citing this software, you help support open-source development and proper crediting in academic research.

Usage
=====

Please have a look at the `tutorials <https://braincoder-devs.github.io/tutorial/index.html>`_ to get started.
