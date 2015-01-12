.. rcv-tests documentation master file, created by
   sphinx-quickstart on Mon Jan 12 08:35:26 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

rcv-tests
=========

This is the documentation for OpenRCV Tests, which is a publicly
available collection of test cases for ranked-choice voting algorithms.

The project page is on [GitHub][tests_github], where the tests are also
hosted and maintained.

All test data is coded as JSON.  For reproducibility, all name-value pairs
in the JSON files are ordered alphabetically by name.


## Definitions

* "Test files" are the files containing the actual test cases.


## Running Tests

All data needed to run the tests is in the project `tests` directory.

Each test file contains multiple test cases.

Each test has an "input"
attribute and an "output" attribute.  The output is completely determined
by the input data, together with some global configuration data.

[tests_github]: https://github.com/cjerdonek/open-rcv-tests

Contents:

.. toctree::
   :maxdepth: 2



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

