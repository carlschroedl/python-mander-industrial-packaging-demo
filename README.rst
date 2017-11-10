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
        |
        | |codacy|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-mander/badge/?style=flat
    :target: https://readthedocs.org/projects/python-mander
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/carlschroedl/python-mander.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/carlschroedl/python-mander

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/carlschroedl/python-mander?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/carlschroedl/python-mander

.. |requires| image:: https://requires.io/github/carlschroedl/python-mander/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/carlschroedl/python-mander/requirements/?branch=master

.. |codacy| image:: https://img.shields.io/codacy/REPLACE_WITH_PROJECT_ID.svg
    :target: https://www.codacy.com/app/carlschroedl/python-mander
    :alt: Codacy Code Quality Status

.. |version| image:: https://img.shields.io/pypi/v/python-mander.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/python-mander

.. |commits-since| image:: https://img.shields.io/github/commits-since/carlschroedl/python-mander/v1.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/carlschroedl/python-mander/compare/v1.0.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/python-mander.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/python-mander

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/python-mander.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/python-mander

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/python-mander.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/python-mander


.. end-badges

Python package for calculating metrics on political district proposals.

* Free software: MIT license

Installation
============

::

    pip install python-mander

Documentation
=============

https://python-mander.readthedocs.io/

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
