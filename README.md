# Git Lesson

This lesson covers the basics of using git for version control.

To make a commit ("version" or "checkpoint") of your files, follow this procedure:

1. Make changes to your project that you would like to keep.
2. When you have your changes, tell git you are ready to create a checkpoint of the files by using `git add filename`
3. Create a checkpoint using `git commit -m "message about what you did"`

## Adding Features
Features should be developed on branches. To create and switch to a branch, use the command

`git switch -c new_branch_name`

To switch to an existing branch, use

`git switch branch_name`