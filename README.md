# gummy-hooks
Git Hooks + Gum => interactive Git workflows

# Usage

You should have git hook samples in `.git/hooks`, such as `pre-push.sample`. 
For more info on the basics, see https://www.atlassian.com/git/tutorials/git-hooks

Examples in this repository are in the [dot-git/hooks folder](./dot-git/hooks/) 

# Why

You might have CI checks like unit tests, linting, formatting, spell-checking, whatever.
If these can run quickly, you might prefer faster feedback of your IDE/terminal telling you about problems with the checks *before* you push your code.

# Tips

If possible, keep checks limited to changed files only - this will keep checks fast.
What you *don't* want is really slow checks that make it a pain to commit or push to git!
