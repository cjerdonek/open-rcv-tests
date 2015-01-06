rcv-tests
=========

[![Documentation Status](https://readthedocs.org/projects/rcv-tests/badge/?version=latest)](https://readthedocs.org/projects/rcv-tests/?badge=latest)

The `rcv-tests` project is a publicly available collection of ranked choice
voting test cases.

The test cases cover many variations of [instant runoff voting][wiki_irv]
and the [single transferable vote][wiki_stv].  The test cases are intended
for testing ranked choice voting election software (e.g.
[OpenRCV][openrcv_github]).

Some key links:

* [Project page and tests][rcv_tests_github] (GitHub)
* [Documentation][rcv_tests_docs] (rcv-tests.readthedocs.org)

**Project status: not yet ready but actively being worked on.**


For Maintainers
---------------

To deploy a new version, bump the [`"version"`][version_number] number in
`tests.json`, and tag the release with a [SemVer][semver]
Git tag (it is okay to add a prefix of "v").  For example--

    $ git tag v0.2.0
    $ git push origin v0.2.0


License
-------

The contents of this repository are licensed under a permissive MIT license.
See the [LICENSE](LICENSE) file for the actual wording.


Author
------

Chris Jerdonek (<chris.jerdonek@gmail.com>)


[openrcv_github]: https://github.com/cjerdonek/open-rcv
[rcv_tests_docs]: http://rcv-tests.readthedocs.org/en/latest/
[rcv_tests_github]: https://github.com/cjerdonek/open-rcv-tests
[semver]: http://semver.org/
[version_number]: https://github.com/cjerdonek/open-rcv-tests/blob/master/tests.json#L2
[wiki_irv]: http://en.wikipedia.org/wiki/Instant-runoff_voting
[wiki_stv]: http://en.wikipedia.org/wiki/Single_transferable_vote
