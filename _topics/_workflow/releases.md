# Releases

At SourceLair we [release early and we release often](https://en.wikipedia.org/wiki/Release_early,_release_often).

In more details, when working on a web application, we release and deploy to production whenever something new is ready, while we release regularly when we work on open source projects like [xterm.js](https://github.com/xtermjs/xterm.js) and [Ceryx](https://github.com/sourcelair/ceryx).

Since SourceLair interns work exclusively on open source projects, we will describe only the release process of these projects.

## Release Process

- We organise our releases with [milestones in GitHub](https://help.github.com/articles/about-milestones/)
- We discuss functionality and report bugs in [GitHub issues](https://help.github.com/articles/about-issues/)
- We maintain a [workflow for implementing new features and bug fixes](./new-features-and-bug-fixes.md)
- We release weekly for yet-unstable projects and monthly for stable, production-ready projects
- We version and tag our releases using [SemVer](https://semver.org/)
- We create a [Release in GitHub](https://help.github.com/articles/about-releases/) with the appropriate notes for each release

## FAQ

### Where can I see pending tasks for the current release?
By opening the page of each milestone in the corresponding GitHub repository (documentation: https://help.github.com/articles/viewing-your-milestone-s-progress/).

### What happens if we do not manage to ship all planned features in a release?
We remove them from the milestone and will reconsider future implementation in the next planning.
