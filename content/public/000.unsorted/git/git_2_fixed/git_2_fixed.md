---
title: Git 2
topic: Version Control
author: Edwin Zhou
source: unknown
template_version: 1.4
attribution: standard
partialCredit: false
singleVariant: false
showCorrectAnswer: false
outcomes:
- 4.2.1.0
- 4.5.1.0
difficulty:
- undefined
randomization:
- undefined
taxonomy:
- undefined
span:
- undefined
length:
- undefined
tags:
- EZ
- mcq
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Git 2
    params_part1_ans1_value: '`git pull; git add -A; git commit -m "new change"; git
      push`'
    params_part1_ans1_feedback: Correct! This sequence of commands ensures that your
      local repository is up-to-date with the remote repository before you stage,
      commit, and push your changes.
    params_part1_ans2_value: '`git fetch; git add -A; git commit -m "new change";
      git push`'
    params_part1_ans2_feedback: Incorrect. `git fetch` only downloads objects and
      refs from the remote repository but does not integrate any of the new data into
      your working files.
    params_part1_ans3_value: '`git add -A; git commit -m "new change"; git push`'
    params_part1_ans3_feedback: Incorrect. This sequence of commands does not ensure
      that your local repository is up-to-date with the remote repository before you
      stage, commit, and push your changes.
    params_part1_ans4_value: '`git push`'
    params_part1_ans4_feedback: Incorrect. `git push` only pushes committed changes
      to the remote repository. You need to stage and commit your changes before pushing
      them.
    params_part1_ans5_value: '`git pull`'
    params_part1_ans5_feedback: Incorrect. `git pull` only pulls changes from the
      remote repository and merges them into your local repository. You need to stage,
      commit, and push your changes after pulling them.
    params_part1_ans6_value: '`git clone <repo_url>, git add -A; git commit -m "new
      change"; git push`'
    params_part1_ans6_feedback: Incorrect. `git clone` creates a new local copy of
      a remote repository. This sequence of commands does not ensure that an existing
      local repository is up-to-date with the remote repository before you stage,
      commit, and push your changes.
    params_part1_ans7_value: '`git commit -m "new change"; git add -A; git push`'
    params_part1_ans7_feedback: Incorrect. You need to stage your changes before committing
      them.
    params_part1_ans8_value: '`git pull; git commit -m "new change"; git add -A; git
      push`'
    params_part1_ans8_feedback: Incorrect. You need to stage your changes before committing
      them.
    params_part1_ans9_value: '`git push; git pull; git commit -m "new change"; git
      add -A; git push`'
    params_part1_ans9_feedback: Incorrect. This sequence of commands does not ensure
      that your local repository is up-to-date with the remote repository before you
      stage, commit, and push your changes. Also, you need to stage your changes before
      committing them.
    params_part1_ans10_value: '`git commit; git add -a; git push`'
    params_part1_ans10_feedback: Incorrect. You need to stage your changes before
      committing them and specify a commit message when using `git commit`.
    params_part1_ans11_value: '`git commit; git add -a; git pull`'
    params_part1_ans11_feedback: Incorrect. You need to stage your changes before
      committing them and specify a commit message when using `git commit`. Also,
      this sequence of commands does not ensure that your local repository is up-to-date
      with the remote repository before you stage and commit your changes.
---
# Select the correct function

## Part 1

Given the following scenario, choose the set of commands you would use to ensure new local changes are aligned with the remote repository

1. You are working on a project with a partner.
1. You have already cloned the shared online repository, and then made a few changes to it locally.
1. You cannot be sure if your partner has made any changes to the repository.

Notes:

- For the purposes of this question, you may assume that any remote commits are not divergent, and pointers can be fast-forwarded.
- The commands below are separated by a `;`

### Answer Section

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)