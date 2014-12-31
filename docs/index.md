# Ranked Choice Voting (RCV) Tests

The tests are hosted and maintained on [GitHub][tests_github].
The GitHub page is also the project page.

All test data is coded as JSON.  For reproducibility, all JSON object
name-value pairs are ordered by name.


## Definitions

* "Test files" are the files containing test cases.


## Running Tests

All test files are in the project `tests` directory.  Each test file
contains multiple test cases.  Each test case is designed to be stand-alone.
Each one has an "input" attribute and an "output" attribute.  The output is
completely determined by the input data, together with some global
configuration data.

Currently, the only global data are the candidate names.  For readability
and discussion purposes, real names like "Ann" and "Bob" were chosen
rather than similar names like "Candidate 1" or "Candidate A".  The names
are alphabetical (one per letter) and are located in the `constants.json`
file at the top level of the project.


## Adding Tests

All test files are auto-generated from other files in the project, so
test files should never be edited by hand.  In particular, you do not
add a test case by manually editing a JSON test file.

TODO


[tests_github]: https://github.com/cjerdonek/open-rcv-tests
