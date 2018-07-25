# New features and bug fixes

At SourceLair we follow the GitHub Flow to develop our software and release regularly. You can read more about the GitHub flow and also see it visualised at https://guides.github.com/introduction/flow/.

Below we provide you with the required steps for starting work on a new feature or bug fix in your project.

## Steps

1. **Save your current changes** (if any). You can either [commit them](https://help.sourcelair.com/git/committing-your-files/) or [stash them](https://git-scm.com/docs/git-stash).
2. **[Checkout](https://help.sourcelair.com/git/checking-out-a-branch/) the `master` branch locally**.
3. **[Pull from the `upstream` remote](https://help.sourcelair.com/git/pulling-from-a-remote/)** to synchronise your local `master` branch with `upstream`.
4. **[Push to the `origin` remote](https://help.sourcelair.com/git/pushing-to-a-remote/)** to synchronise your personal fork with `upstream`.
5. **[Create a new branch](https://help.sourcelair.com/git/creating-a-branch/)** for your upcoming work.
6. **Write and commit your code**.
7. **Open a new [Pull Request](https://help.github.com/articles/about-pull-requests/) in GitHub** 

## FAQ

### After I open a Pull Request, do I need to open a new one when I push updates?

No, Pull Requests will be updated automatically when pushing to the same branch.

### What should be the goal and contents of each Pull Request?

Each Pull Request should attempt to resolve a single issue. More particualrly, the best practice is resolving one and only one GitHub issue with each Pull Request (issues documentation: https://help.github.com/articles/about-issues/). You should avoid opening a single Pull Request to resolve multiple unrelated issues 🙏.
