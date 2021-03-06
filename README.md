[![GitHub version](https://badge.fury.io/gh/Niourf%2Frecsys.svg)](https://badge.fury.io/gh/Niourf%2Frecsys)
[![Doc](https://img.shields.io/badge/Read-Doc-blue.svg)](http://recsys.readthedocs.io/en/latest/index.html)
[![Build Status](https://travis-ci.org/Niourf/RecSys.svg?branch=master)](https://travis-ci.org/Niourf/RecSys)
[![python_versions](https://img.shields.io/badge/python-2.7%2C%203.4%2C%203.5-blue.svg)]
(https://pypi.python.org/pypi/recsys/)
[![license](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://github.com/Niourf/RecSys/blob/master/LICENSE.md)


RecSys
======

author: Nicolas Hug

Overview
--------

RecSys is an open source Python package that provides with tools to build and
evaluate the performance of many recommender system prediction algorithms. Its
goal is to make life easy(-ier) for reseachers and students who want to play
around with new recommender algorithm ideas.

A strong emphasis is laid on
[documentation](http://recsys.readthedocs.io/en/latest/index.html), which we
have tried to make as clear and precise as possible by pointing out every
detail of the algorithms, in order for the practitioner to have perfect
control over his experiments.

Features
--------

- A great [doc](http://recsys.readthedocs.io/en/latest/index.html)! (we hope)
- Dataset handling is made easy.
- Various ready-to-use prediction algorithms.
- Easy to implement new algorithm ideas.
- Evaluate, analyse and compare the algorithms performance.

Installation / Usage
--------------------

Please, use a [virtual env](
http://docs.python-guide.org/en/latest/dev/virtualenvs/)

To install from [PyPI](https://pypi.python.org/pypi/recsys/), use pip
(recommended):

    $ pip install recsys

Or clone the repo and build from the sources (you'll need Cython and numpy
first):

    $ git clone https://github.com/Niourf/recsys.git
    $ python setup.py install


Documentation, Getting Started
------------------------------

The documentation with many usage examples is available
[online](http://recsys.readthedocs.io/en/latest/index.html) on ReadTheDocs.

License
-------

This project is licensed under the GPLv3 license - see the LICENSE.md file for
details.

Acknowledgements:
----------------

- [Pierre-François Gimenez](https://github.com/PFgimenez), for his valuable
  insights on software design.
