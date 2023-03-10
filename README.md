# git-repl

A git REPL (read-eval-print loop) courtesy of [rlwrap](https://github.com/hanslub42/rlwrap).

## Requirements

* git
* rlwrap
* bash

## Quick Start

Clone and run:

```
git clone https://github.com/jcsalterego/git-repl.git
cd git-repl/
./git-repl
git>
```

Run `status` subcommand:

```
git> status
On branch main
```

Double-tab to list all subcommands:

```
git> <TAB><TAB>
Display all 146 possibilities? (y or n)
.git                filter-branch       push
README.md           fmt-merge-msg       quiltimport
add                 for-each-ref        range-diff
am                  for-each-repo       read-tree
annotate            format-patch        rebase
```

## Installation

### Add to your PATH

Add `git-repl/` to your `$PATH`:

```
export PATH="/path/to/git-repl:$PATH"
```

### Add as Alias

Add git alias:

```
git config --global alias.repl '!bash -c "/path/to/git-repl/git-repl"'
```
