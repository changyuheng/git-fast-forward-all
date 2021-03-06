# git-fast-forward-all

This small tool fast-forwards all your local branches upto corresponding remote tracking branches.
Inspired by [Can “git pull --all” update all my local branches?](https://stackoverflow.com/questions/4318161/can-git-pull-all-update-all-my-local-branches).

## Usage

```
git fast-forward-all
```

Example output:

```
Branch master
  fast-forwarded
Branch hotfix
  skipped: diverged
Branch pull-request-1
  skipped: upstream is absent
```

## Installation

Copy `git-fast-forward-all` to your `$PATH` (such as `~/bin`).

## Alternatives

1. [hub](https://github.com/github/hub). (hub doesn't support multiple remotes yet.)

## License

[Mozilla Public License Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/)
