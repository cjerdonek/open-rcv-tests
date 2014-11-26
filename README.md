Ranked Choice Voting Tests
==========================

The purpose of this repository is to make test cases publicly available
for ranked choice voting election software.

The test cases in this repository can be used for automated testing
and to help check that different software implementations agree and
are correct.  [OpenRCV][openrcv_github] is an example of a project that
uses the tests in this repository.

TODO: mention rule descriptions.


Test Details
------------

The tests are located in the file [`contests.json`][test_data].


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
[semver]: http://semver.org/
[test_data]: contests.json
[version_number]: https://github.com/cjerdonek/open-rcv-tests/blob/master/tests.json#L2
