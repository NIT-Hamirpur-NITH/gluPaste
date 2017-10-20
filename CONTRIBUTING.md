# How to contribute

This project is open to any pull requests. Here's a guideline on how
to contribute to it:

1. [Fork it](https://github.com/Nithmr/gluPaste/fork_select)
2. Make your changes
3. Submit a [pull request](https://help.github.com/articles/creating-a-pull-request)

Your work will then be reviewed as soon as possible (suggestions about some
changes, improvements or alternatives may be given).

Don't forget to follow the [coding standards](CONTRIBUTING.md#coding-standards)

## Help with Git

Once the repository is forked, you should track the upstream (original) one
using the following command:

    git remote add upstream https://github.com/Nithmr/gluPaste.git

Then you should create your own branch, following the
[branch naming policy](VERSIONING.md#branch-naming):

    git checkout -b <branch-name>

Once your changes are done (`git commit -am '<descriptive-message>'`), get the
upstream changes:

    git checkout master
    git pull --rebase origin master
    git pull --rebase upstream master
    git checkout <your-branch>
    git rebase master

Finally, publish your changes:

    git push -f origin <your-branch>

You should be now ready to make a pull request.

## Commit messages

The cleaner the git history is, the better.
A good commit message should short and precisely describe what changed.
