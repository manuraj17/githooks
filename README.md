# GIT HOOKS

Git hooks that I use across various projects.

## Commit Message
Append task number to commit messages, inferring from branch name.
Having branch name like this `<TASK-ID>-mini-info` will create commit messages  
of the format `[TASK-ID] Message`


## Pre Push
Prevents push to master, adds a dialogue if branch being pushed is master.
