# Git

Git is the version control tool I used to keep track of changes in a project. The Git Basics exercise helped me understand its workflow by creating a small repository and making changes step by step.

## Creating a repository

I started by creating a project folder and running:

```bash
git init
```

This initialises a Git repository in the current folder. I then set the name and email that Git records with my commits:

```bash
git config user.name "Your Name"
git config user.email "you@example.com"
```

## From editing to committing

One important thing I learned is that saving a file does not automatically save it in Git history. There are three main stages:

1. Make changes in the working directory.
2. Use `git add` to stage the changes I want to keep.
3. Use `git commit` to record those staged changes.

For example:

```bash
git status
git add readme.txt
git commit -m "Add readme file"
```

`git status` shows which files are untracked, modified or staged. I also used `git diff` to review changes before committing them.

## Reviewing and undoing changes

The exercise helped me understand the difference between a few commands:

- `git restore filename` discards unstaged changes in a file and restores it to the version in the index.
- `git revert <commit>` creates a new commit that reverses an earlier commit, while keeping the earlier commit in the history.
- `git checkout <commit>` can move the working directory and `HEAD` to an earlier snapshot. Checking out a commit directly can put Git in a detached `HEAD` state.

I used `git log` and `git log --oneline` to review commit history. I also learned to check the branch name before switching. In the exercise, the repository used `master`, so `git checkout main` did not work there.

## Branches and remote repositories

Branches let me work on changes separately before bringing them together. Remote commands connect a local repository to a hosted copy, such as one on GitHub.

```bash
git branch
git switch -c feature-name
git merge feature-name
git remote -v
git push
git pull
```

For a grouped list of commands, see the [Git commands reference](commands.md).

## What I learned

The most useful distinction for me was between `add`, `commit` and `push`: `add` stages changes, `commit` records them locally, and `push` sends commits to a remote repository. Checking `git status` regularly also makes it easier to understand what Git is about to do.

## Practical work

[`Assignment_8_Git_Basics.pdf`](Assignment_8_Git_Basics.pdf) contains the step-by-step exercise and the commands used with the sample project.



