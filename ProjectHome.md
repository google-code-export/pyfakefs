# Installation #

The pyfakefs project is hosted on [PyPi](https://pypi.python.org/pypi/pyfakefs) and can be installed:

pip install pyfakefs

# Motivation #

Many [Python](http://python.org) scripts deal with direct file manipulation; testing such code normally requires a ton of testdata files (a real PITA) or lots of mocking using a layer over the raw I/O modules. Even working with a mocking layer might not be desirable considering that mocking every call which does file manipulation in a Python script would be tedious and repetitive.

# History #

`pyfakefs.py` was developed initially as a modest fake implementation of core Python modules to support moderately complex file system interactions, and was introduced Google-wide via [Testing on the Toilet](http://googletesting.blogspot.com/search/label/TotT) in September 2006. Since then, it has received many (well-tested) contributions to extend its functionality and usefulness, and is used in over 2,000 Google Python tests.

# Contributing #

See the [Contributing wiki page](http://code.google.com/p/pyfakefs/wiki/Contributing) for details on how to submit patches for review.