# git-CLI

This is a collection of various git-related CLI commands. To install, run

    > npm install -g git-lib-cli

For more information on each CLI package, please view said package's README by clicking on the link of the package below.

## Included Packages

* [`Checkout`](#checkout) (both local and remote)
* [`Commit`](#commit)
* [`Push`](#push)
* [`Merge`](#merge)
* [`Revert`](#revert)
* [`Branch`](#branch) (includes deletion of branches)

### [Checkout](https://github.com/joeyism/node-checkout-cli/README.md)

A command line tool that allows you to checkout to your other branches

    > checkout

And a prompt will appear to checkout your local branches. To checkout your remote branches as well, please run

    > checkout all

### [Commit](https://github.com/joeyism/node-commit-cli/README.md)

A command line tool that allows you to commit your local changes

    > commit

You can also recommit your last change

    > recommit

### [Push](https://github.com/joeyism/node-push-cli/README.md)

A command line tool that allows you to push to your remote git

    > push

### [Merge](https://github.com/joeyism/node-merge-cli/README.md)

A command line tool that allows you to merge from a selected branch into your current one

    > merge

### [Revert](https://github.com/joeyism/node-revert-cli/README.md)

A command line tool that allows you to revert/uncommit changes you've made to files back to your last commit

    > revert

### [Branch](https://github.com/joeyism/node-branch-cli/README.md)

A CLI tool that allows you to manipulate local git repository branch

    > branch

To **delete** a branch, run

    > branch delete

## Versions
**1.3.0**
* branch

**1.2.0**
* revert

**1.1.0**
* Recommit

**1.0.10**
* Fixed package.json bug

**1.0.9**
* Updated to commit-cli v2.0.0
* Added merge-cli

**1.0.4**
* Updated package.json

**1.0.3**
* Updated README

**1.0.2**
* Fixed package.json bug

**1.0.0**
* First
