# git-assert

```
usage: git-assert [-h] [-V] [--branch BRANCH] [--no-unstaged-changes] [path]

Make assertions about a git repository.

For example, to assert that a repository is on the "master" branch run:
$ git-assert sample-project/ --branch=master

Failed assertions output to stderr and exit with code 1.

positional arguments:
  path                  path to local git repository

optional arguments:
  -h, --help            show this help message and exit
  -V, --version         display version number
  --branch BRANCH       branch name
  --no-unstaged-changes
                        check for unstaged changes
```
