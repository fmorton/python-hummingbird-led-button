========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/hummingbird-led-button/badge/?style=flat
    :target: https://hummingbird-led-button.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/fmorton/hummingbird-led-button/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/fmorton/hummingbird-led-button/actions

.. |requires| image:: https://requires.io/github/fmorton/hummingbird-led-button/requirements.svg?branch=main
    :alt: Requirements Status
    :target: https://requires.io/github/fmorton/hummingbird-led-button/requirements/?branch=main

.. |codecov| image:: https://codecov.io/gh/fmorton/hummingbird-led-button/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://codecov.io/github/fmorton/hummingbird-led-button

.. |version| image:: https://img.shields.io/pypi/v/hummingbird-led-button.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/hummingbird-led-button

.. |wheel| image:: https://img.shields.io/pypi/wheel/hummingbird-led-button.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/hummingbird-led-button

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/hummingbird-led-button.svg
    :alt: Supported versions
    :target: https://pypi.org/project/hummingbird-led-button

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/hummingbird-led-button.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/hummingbird-led-button

.. |commits-since| image:: https://img.shields.io/github/commits-since/fmorton/hummingbird-led-button/v0.0.5.svg
    :alt: Commits since latest release
    :target: https://github.com/fmorton/hummingbird-led-button/compare/v0.0.5...main



.. end-badges

LED button support for Birdbrain Technologies Hummingbird

* Free software: MIT license

Installation
============

::

    pip install hummingbird-led-button

You can also install the in-development version with::

    pip install https://github.com/fmorton/hummingbird-led-button/archive/main.zip


Documentation
=============


https://hummingbird-led-button.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
