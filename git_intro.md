# git {data-background="images/dark-git.png"}

## Why git?

  * Distributed
  * Cryptographic integrity
  * Robust branching and merging
  * Rebase, rebase, rebase


## Workflows

  [Distributed Workflows](https://git-scm.com/book/en/v2/Distributed-Git-Distributed-Workflows)

  * Centralized
    * No forking
    * Everyone commits to central repo
  * Integration Manager
    * Each developer has their own repo


## HEAD

  * You are here
  * HEAD is a pointer to the commit you are currently located at

## Branching/Merging

[Branching](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)

  * git makes branching easy
  * location of HEAD determines root commit of branch
  * merging puts the final commit of the branch at the tip of the parent


## Rebase, Rebase, Rebase

[Rebasing](https://git-scm.com/book/en/v2/Git-Branching-Rebasing)

  * rebase is git's killer feature
  * rewrites history
  * allows you to commit frequently and clean up afterwards


## Configure git

Minimum

~~~~
git config --global user.email "john@example.com"
git config --global user.name "John Doe"
git config --global color.ui true
git config --global branch.autosetuprebase always
~~~~

Bonus

~~~~
git config --global user.signkey "54B8BE2C"
git config --global commit.gpgsign true
git config --global hub.protocol git
~~~~


# Links {data-background="images/dark-git.png"}

## Books

  * [git book](https://git-scm.com)
  * [Pro git](https://gitbookio.gitbooks.io/progit/content/en/)

## Tasks

  * [Distributed Workflows](https://git-scm.com/book/en/v2/Distributed-Git-Distributed-Workflows)
  * [Branching](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
  * [Rebasing](https://git-scm.com/book/en/v2/Git-Branching-Rebasing)

## Tutorials/Resources

  * [RyPress](http://rypress.com/tutorials/git/index)
  * [Interactive cheatsheet](http://ndpsoftware.com/git-cheatsheet.html)
