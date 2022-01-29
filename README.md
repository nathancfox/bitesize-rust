# bitesize-rust
A tiny project written in Rust as a collaborative effort between Nathan Fox and David Grossman.
Intended to be small in scope, fun, and educational.


## Developer's Guide
#### Versioning
Use the Semantic Versioning system described at [semver.org](https://semver.org)
```
Given a version number MAJOR.MINOR.PATCH, increment the:

    1. MAJOR version when you make incompatible API changes,
    2. MINOR version when you add functionality in a backwards compatible manner, and
    3. PATCH version when you make backwards compatible bug fixes.

Additional labels for pre-release and build metadata are available as extensions to the
MAJOR.MINOR.PATCH format.
```

#### Committing
All work related to a version change, e.g. code, documentation, issues, bugfixes, must happen on a
topic branch. These changes should only be committed to main via reviewed pull requests. PRs should
be committed to main as "squash and merge" PRs, to keep the commit history clean. If main moves
ahead of a topic branch, rebasing is suggested to avoid forks in the commit history. All PRs should
include a version bump and an entry in the CHANGELOG.

All other work, e.g. typo fixes, updates to the README, a change in LICENSE, an isolated change to
the gitignore, can be committed directly to main.

