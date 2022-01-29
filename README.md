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


## Brainstorming

#### Nathan's Ideas/Thoughts on Project Scope
My favorite programs to write are CLI applications. The other types that come to mind are web
applications, GUI applications, and libraries. On a cursory Google search, it looks like Rust's GUI
support is a little sparse; maybe not a good choice for beginners. A web application is part of
Rust's official documentation, so probably well-supported. I have cursory experience with web apps;
the thing that is most appealing to me about them is 1) it's easy to show people your work and 2)
It's easy to put a GUI on your work. Here are a few ideas of projects that might be fun to complete:

1. A journal entry program. A CLI interface that allows you to create and save new entries with
   persistence, browse and read old entries, browse via multiple sort mechanisms, and delete old
   entries.
1. A CLI that utilizes an external API or well-established library. For example, a Reddit bot or a
   Youtube to MP3 converter. Alternately something that retrieves the weather forecast based on your
   IP address location.
1. A web app that allows input of parameters and generates graphs for download. No persistence.
1. A web app that encodes text in many different codes/ciphers. Optionally including a tool
   that attempts to decode simple ciphers/codes.
