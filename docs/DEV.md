
## Setup

We use git lfs to store artifacts. So probably you need to install it before: https://git-lfs.github.com/

Copy `*.aar` into libs.
Once sdk is ready, we need just to create git tag for the version.
```
git tag -a -m "5.11.0.6883" 5.11.0.6883 && git push --follow-tags
```
It is enough to start using library.
