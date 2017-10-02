# mochizukikotaro/gh

`gh` is a command line tool implemented in Go.

It enables you to jump to remote repository's GitHub page from terminal.

## Install via Homebrew

```bash
$ brew tap mochizukikotaro/gh
$ brew install gh
```

Uninstall

```bash
$ brew uninstall gh
$ brew untap mochizukikotaro/gh
```


## Usage

```bash
# Move to inside work tree
$ cd ~/path_to_project

# Jupm to GitHub page
$ gh

# If there are some remote names
#
# ex)
# $ git remote
# upstream
# origin
#
$ gh #=> Go to upstream repository (default remote name is 'upstream')
$ gh origin #=> Go to origin repository
```


