========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |requires|
        | |coveralls| |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/nesta_official/badge/?style=flat
    :target: https://readthedocs.org/projects/nesta_official
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/georgerichardson/nesta_official.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/georgerichardson/nesta_official

.. |requires| image:: https://requires.io/github/georgerichardson/nesta_official/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/georgerichardson/nesta_official/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/georgerichardson/nesta_official/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/georgerichardson/nesta_official

.. |codecov| image:: https://codecov.io/github/georgerichardson/nesta_official/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/georgerichardson/nesta_official

.. |version| image:: https://img.shields.io/pypi/v/nesta-official.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/nesta-official

.. |commits-since| image:: https://img.shields.io/github/commits-since/georgerichardson/nesta_official/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/georgerichardson/nesta_official/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/nesta-official.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/nesta-official

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/nesta-official.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/nesta-official

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/nesta-official.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/nesta-official


.. end-badges

Test for Nesta Official repo.

* Free software: MIT license

Installation
============

::

    pip install nesta-official

Documentation
=============

https://nesta_official.readthedocs.io/

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
