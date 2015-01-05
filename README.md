`rcv-tests` (Ranked Choice Voting Tests)
========================================

The `rcv-tests` project is a publicly available collection of test cases
for ranked choice voting methods.

The test cases are intended to be used for testing ranked choice voting
election software.  [OpenRCV][openrcv_github] is an example of a project
that uses the tests in this repository.

The project page and source code are on [GitHub][openrcv_github].  Project
documentation is located at [rcv-tests.readthedocs.org][rcv_tests_docs].

TODO: mention rule descriptions.


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
[semver]: http://semver.org/
[version_number]: https://github.com/cjerdonek/open-rcv-tests/blob/master/tests.json#L2
