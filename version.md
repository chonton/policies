# Version Policy
All artifacts must be named and versioned.

## Purpose
A semantic version allows a client to understand the compatibility of an artifact.
A build version supports tracing an artifact back to the source code used to build the artifact.

## Procedures
- Semantic version must follow the rules at [SemVer](semver.org)
- Build version must uniquely identify the source code that built the artifact.  This can be a git hash or tag.
- Releasable versions are those without -SNAPSHOT, -alpha, or -beta suffixes.

## Discussion
A version can either be a semantic version, a build version, or both.  A version specification which
is both a semantic version and a build version is made by placing the build version in the metadata;
e.g. 4.9.1+99108cf44966c1969cb9c01c8b28e0139900fb53

<p align="center">
  <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png"/></a>
  <br />
  This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
</p>

