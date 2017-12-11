# `clean-branch-badge-hooks`

WIP. The code is ridiculously raw.

Until I get tests built, I wouldn't use this.

<!-- MarkdownTOC -->

- [Installation](#installation)
- [Usage](#usage)
- [TODO](#todo)

<!-- /MarkdownTOC -->


## Installation

Install the hooks via `install`. After installation, the hooks will automatically update branch-specific badges in the tracked files.

```bash
$ ./install --help
usage: install [-h] [-v] [-f] [-d HOOKS_DIR]

Installs this git tooling

optional arguments:
  -h, --help            show this help message and exit
  -v, --verbose         Increase output verbosity
  -f, --force           Force installation. Requires at least -v|--verbose,
                        although -vvv is recommended
  -d HOOKS_DIR, --hooks-dir HOOKS_DIR
                        git hooks directory (default </repo/path/>.git/hooks)
```

## Usage

TODO

## TODO

* expose tracked files
* write better README
* actually document the code
* polish code
