Ranked Choice Voting Rules
==========================

This document defines various ranked choice voting rules and variations
that appear in the test cases.  It also defines string identifiers for
each of these variations that we use in the JSON files.

For the purposes of the project, we define two types of rules: "options"
and "styles."  An option is a variation that can be selectively applied to
different tabulation rules.  A style is a set of options that completely
defines the rules for tabulation.  For example, "batch elimination" is
an option, while "San Francisco RCV" is a style (which happens to
incorporate batch elimination).


Contents
--------

* Options
    * [`irv_batch_elimination`](#irv_batch_elimination)
* Styles
    * [`san_francisco_irv`](#san_francisco_irv)


Options
-------

### `irv_batch_elimination`

The batch-elimination IRV option means that if no candidate has a majority,
then a group of candidates is eliminated instead of just one.
The eliminated group is the maximal set of lowest candidates such that
the sum of the vote totals of the lowest candidates is strictly less
than the vote total of the next lowest candidate.

For example, if the vote totals of the candidates in a round are
10, 10, 30, 40, 400, 600, and 800; then the bottom four candidates are
eliminated.

Batch elimination does not affect the final-round vote totals since the
eliminated candidates would be eliminated in a later round anyways
if single-candidate elimination were used.


Styles
------

### `san_francisco_irv`

San Francisco IRV is IRV with the `irv_batch_elimination` option.
