# git-assert

Make assertions about the condition of one or more local git repositories.

```
usage: git-assert [-h] [-V] [--branch BRANCH] [--unstaged-changes]
                  [path [path ...]]

Make assertions about one or more git repositories. For example, to assert
that a repository is on the "master" branch run "git-assert --branch=master
sample-project/". Failed assertions output to stderr and exit with code 1.

positional arguments:
  path                path to local git repository (use "-" to read from
                      stdin)

optional arguments:
  -h, --help          show this help message and exit
  -V, --version       display version number
  --branch BRANCH     branch name
  --unstaged-changes  check for unstaged changes
```
