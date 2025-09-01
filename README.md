# Homework Assignments

This repository contains all of your homework assignments.
You will submit your work by creating a Pull Request (PR) to this repository on GitHub.

## Due dates

* HW1 25 September
* HW2 9 October
* HW3 6 November
* HW4 27 November

## Process

* First, you must `clone` this repo to your machine. You only need to do this once. The easiest way is with an RStudio Project. File > New Project > Version Control > Git. Then copy the url into the first field. You can save anywhere you like on your machine.

* Now you're ready to go. So you want to start working...

* The below is the same as at [Stat-406/Computing](https://ubc-stat.github.io/stat-406/computing/)

**If you are confused or concerned,** SAVE YOUR WORK and then post to Slack for help.

### Workflow in an RStudio Project

1. Make sure you are on `main` (Check the git tab.) Pull with the Blue Arrow.
1. Create a new branch (name it anything you like).
1. Work on your documents and save frequently.
1. Stage your changes by clicking the check boxes.
1. Commit your changes by clicking **Commit**.
1. Repeat 3-5 as necessary.
1. Push to Github with the Green Arrow.
1. When done, go to Github and open a PR. Be sure to Request Review from the TAs.
1. Use the dropdown menu to go back to `main` and avoid future headaches.

### Workflow from the command line

1. Make sure you are on `main`: `git branch -v`. Pull in any remote changes: `git pull`
1. Create a new branch `git branch -b <name-of-branch>`
1. Work on your documents and save frequently.
1. Stage your changes `git add <name-of-document1>` repeat for each changed document. `git add .` stages all changed documents.
1. Commit your changes `git commit -m "some message that is meaningful"`
1. Repeat 3-5 as necessary.
1. Push to Github `git push`. It may suggest a longer form of this command, obey.
1. When done, go to Github and open a PR. Request review from the TAs.
1. Switch back to `main` to avoid future headaches. `git checkout main`.
