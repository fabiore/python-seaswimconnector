========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/python-seaswimconnector/badge/?style=flat
    :target: https://readthedocs.org/projects/python-seaswimconnector
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/flabe81/python-seaswimconnector.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/flabe81/python-seaswimconnector

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/flabe81/python-seaswimconnector?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/flabe81/python-seaswimconnector

.. |requires| image:: https://requires.io/github/flabe81/python-seaswimconnector/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/flabe81/python-seaswimconnector/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/flabe81/python-seaswimconnector/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/flabe81/python-seaswimconnector

.. |version| image:: https://img.shields.io/pypi/v/seaswimconnector.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/seaswimconnector

.. |downloads| image:: https://img.shields.io/pypi/dm/seaswimconnector.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/seaswimconnector

.. |wheel| image:: https://img.shields.io/pypi/wheel/seaswimconnector.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/seaswimconnector

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/seaswimconnector.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/seaswimconnector

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/seaswimconnector.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/seaswimconnector


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD license

Installation
============

::

    pip install seaswimconnector

Documentation
=============

https://python-seaswimconnector.readthedocs.org/

Development
===========

To run the all tests run::

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
