## git-bashrc

Useful configuration and aliases for git.

## Usage

- `gl`
Git log, pretty

- `gls`
Short git log

- `gs`
Git status

- `gbs`
Git branch, sorted by commit date

- `tag-next`
Makes the next sequential SEMVER tag; prompts user for which possible alternative (major, minor, patch, etc.) is desired.

- `tnq`
Tag Next quick and push. Makes the next sequential SEMVER tag and pushes it to the origin.

- `git-cleanup`
Delete all local branches that have been merged.

- `grep-branches`
Run a grep on all branches.

- `grep-all`
Run grep across all commits in the current branch.

- `clone-all`
Given a Github token and a Github org name, creates a local working copy of every project in that org.

- `pull-all`
Iterate over all local working copies that are immediate children of the current working directory, and run `git pull` on each.

## Automatic Configuration

At installation time, or whenever the `configure-git` script is executed, some basic git defaults will be set. See the script for details.

## Installation

```
$ cd $HOME/persistent/install/location
$ git clone https://github.com/g1a/git-bashrc.git
$ cd git-bashrc
$ source bashrc-install.sh
```

The `bashrc-install.sh` script will do some basic one-time git configuration, and install the git-bashrc file in your `$HOME/.bashrc` file.

## About

These aliases and scripts were originally part of the [Utiliscripts](https://github.com/greg-1-anderson/utiliscripts) project.
