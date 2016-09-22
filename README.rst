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

.. |docs| image:: https://readthedocs.org/projects/python-ohaihaiku/badge/?style=flat
    :target: https://readthedocs.org/projects/python-ohaihaiku
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/jkahn/python-ohaihaiku.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/jkahn/python-ohaihaiku

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/jkahn/python-ohaihaiku?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/jkahn/python-ohaihaiku

.. |requires| image:: https://requires.io/github/jkahn/python-ohaihaiku/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/jkahn/python-ohaihaiku/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/jkahn/python-ohaihaiku/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/jkahn/python-ohaihaiku

.. |version| image:: https://img.shields.io/pypi/v/ohaihaiku.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/ohaihaiku

.. |downloads| image:: https://img.shields.io/pypi/dm/ohaihaiku.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/ohaihaiku

.. |wheel| image:: https://img.shields.io/pypi/wheel/ohaihaiku.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/ohaihaiku

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/ohaihaiku.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/ohaihaiku

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/ohaihaiku.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/ohaihaiku


.. end-badges

Manages the Ohaihaiku (Twitter) bot.

* Free software: BSD license

Installation
============

::

    pip install ohaihaiku

Documentation
=============

https://python-ohaihaiku.readthedocs.io/

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
