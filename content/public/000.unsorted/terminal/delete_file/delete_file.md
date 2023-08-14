---
title: Delete File
topic: Terminal
author: Borna Shani
source: original
template_version: 1.0
attribution: standard
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 3.1.1.0
- 3.2.1.0
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
- BS
assets: null
part1:
  type: string-input
  pl-customizations:
    answers-name: ans
    display: block
    placeholder: '...'
    ignore-case: true
    label: Command
myst:
  substitutions:
    params_vars_to_delete: trashfile.py
    params_vars_title: Delete File
---
# {{ params_vars_title }}

## Question Text

The command to delete a file from the current directory called `{{ params.vars.to_delete }}` is:

\*\*Note: Enter the whole command as you would in a Terminal. Do not include any flags such as '-f' or '--force'. \*\*

### Answer Section

### pl-submission-panel

{{ feedback.ans }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)