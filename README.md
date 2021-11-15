# git-plugins

A set of plugins adding functionality to git. See [here](https://www.atlassian.com/git/articles/extending-git) for more information on extending `git`.

## Install
1. Be sure any `plugins/git-*` files in this directory have `755` permissions.
    - `chmod 755 plugins/git-*`
1. Add the `plugins` directory to your `PATH`

## Plugins

Prunes local git repo branches to match active ones on the `origin`

```bash
❯ git clean-up
Local and Remote branches are now synced.

Local
* master

Remote
  origin/HEAD -> origin/master
  origin/master
```