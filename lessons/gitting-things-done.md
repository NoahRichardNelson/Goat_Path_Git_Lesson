# Gitting things done
In this lesson, we will learn about:
- git repositories
- local vs. remote repositories
- creating a local repository
- how to organize and track your changes with git

## Repositories
Git uses some special terminology that can be confusing for first-timers. First up is the term **repository**. "Repository" is the term used to refer to a directory (folder) that holds content that git can keep track of.

*Conceptually*, a repository is like a database or a digital warehouse. Working on a set of files that you want to keep track of using git? Put them in a repository!

*Technically*, a git repository is any directory that contains a special `.git/` directory inside of it. That `.git/` directory is what handles the operations of git that make the directory function as a repository (by tracking changes) instead of a normal directory (which tracks nothing).

Repositories are often referred to by a shorhand term, **repo**. There is no difference between these terms.

### Local vs. Remote Repositories
There are two "kinds" of repository, **local** repositories and **remote** repositories. The technical difference is nuanced, so I'm instead going to tell you how we will use the terms:

- **Local repository** -- any repository on somebody's *local machine* (e.g., personal laptop, laboratory workstation).
- **Remote repository** -- any repository on *GitHub* or a similar online platform.

You can use git on either a local or a remote repository, without needing the other one. Usually, however, you use both *linked together*. We will talk more about this later, when we turn to remote repositories. For now, we will learn the basics of git using *local repositories only*.

# Guides and Resources

[First Time Git Setup Guide](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

# Terminological Reference

**repository** -- what we call the thing that tracks changes to our files. You might think of it like a database, an invoice, or a receipt of every change you have ever saved.

**repo** -- short for repository.

**to commit (v.)** -- to save the state of all of your files in the repository.

_I committed the changes to the repository._

**commit (n.)** -- an individual instance of a committing event. A snapshot of the repository in time.

_The last commit introduced a bug in the program._

**changeset** -- a set of changes which should be treated as an indivisible group.

**index** -- this is a list of all commits.

**to stage (v.)** -- to bundle files together *in preparation* of a commit (i.e., saving the state to the repo).

**staging area (n.)** -- the digital "space" where staging takes place. Changes must first be added to the staging area before you can commit them.

# Git Command Reference

* `git init` - Start a Git repository
* `git config` - Configure Git and the Git configuration options
* `git status` - Check for changed files
* `git diff` - See the differences
* `git add` - Stage files whose changes you want to track
* `git commit -m 'message'` - Commit the changes to the Git repository
* `git log` - See a log of committed changes
