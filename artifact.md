# Artifact Policy
All artifacts must be named, versioned, and retained in a repository.

## Purpose
A name and a semantic version allows artifacts to be located in a repository.
The name and a build version allows artifacts to be traced back to source code and potentially reproduced.  

## Procedures
### Releasable Artifacts
- Only releasable artifacts may be promoted to production environments.
- Releasable artifacts have a release [semantic version](./version.md) (without -SNAPSHOT, -alpha, or -beta suffix).
- Releasable artifacts are immutable.
- The source code for releasable artifacts must be tagged in source control.

### All Artifacts 
- Must be semantically versioned.
- Must be archived in a repository with the semantic version.

### In-House Artifacts
- Must be semantically and build versioned.
- Must have source code in source control.
- Must be queryable for their semantic version and dependency versions.
- Must be queryable for their build version, potentially a git hash code.

### Open Source Artifacts
- Must be immutable.
- Must be traceable.
- Must have source code available.
- Must have an appropriate [license](./license.md).

### Commercial Artifacts
- Must be immutable.

<p align="center">
  <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png"/></a>
  <br />
  This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
</p>

