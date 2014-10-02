Ranked Choice Voting Tests
==========================

The purpose of this repository is to make test cases publicly available
for ranked choice voting election software.

The test cases in this repository can be used to help check that new
implementations are correct, for example [OpenRCV][openrcv-github].


Test Details
------------

The tests are located in the file [`tests.json`](tests.json).


For Maintainers
---------------

To deploy a new version, bump the [`"version"`][version-number] number in
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


[openrcv-github]: https://github.com/cjerdonek/open-rcv
