# Repository Policy
Write access to repositories must be limited.  All changes must be logged.  Versions within a
repository must be immutable.

## Purpose
Source and artifacts from repositories are relied upon to consistently build new artifacts.  If dependent
artifacts or source code changes can occur, then a build will not be reproducible.

## Procedures
All repositories must be immutable; a version of source or artifact cannot change or be removed.

### External Artifact Repositories
- Must be available at a public location (such as Maven Central).
- Must require cryptographic signatures.
- Must require source code with the artifacts.
- Must require metadata specifying license and project url.
- Must retain artifacts indefinitely.

## Discussion
There are two general types of repositories: source code, and binary artifact.  Source code repositories
are usually stored as a series of deltas with version numbers for each change set and tags to identify
particular semantic versions.  Binary artifact repositories store complete binaries in a directory
structure with a portion of the file path being the version.

<p align="center">
  <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png"/></a>
  <br />
  This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
</p>
