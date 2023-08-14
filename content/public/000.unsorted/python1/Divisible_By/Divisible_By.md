---
title: Divisible By
topic: Programming
author: Gavin Kendal-Freedman
source: original
template_version: 1.0
attribution: standard
partialCredit: true
singleVariant: false
showCorrectAnswer: false
externalGradingOptions:
  enabled: true
  image: prairielearn/grader-python
  entrypoint: /python_autograder/run.sh
  timeout: 20
outcomes:
- 6.4.4.0
- 6.4.11.0
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
- GKF
- test3
- autograder
assets: null
gradingMethod: External
autogradeTestFiles:
- ans.py
- setup_code.py
- starter_code.py
- test.py
part1:
  type: file-editor
  gradingMethod: External
  pl-customizations:
    file-name: user_code.py
    ace-mode: ace/mode/python
    source-file-name: tests/starter_code.py
myst:
  substitutions:
    params_vars_title: Divisible By
    params_vars_divisible_by: 3
    params_names_for_user: []
    params_names_from_user:
    - name: divisible_by_3
---
# {{ params_vars_title }}

## Question Text

Create a function called `divisible_by_{{ params.vars.divisible_by }}` that has **one** input variable. You can assume that the input variable will always be a **positive integer**.

The function should return `True` if the integer is divisible by `{{ params.vars.divisible_by }}`, and `False` otherwise. You can assume the function will only receive valid inputs. You are not required to include error handling.

*Hint: Consider using the modulo operator (`%`).*

You should consider testing your function with at least two different numbers (`test1` and `test2`), and use `assert` statements to confirm your function works correctly.

### Answer Section

### pl-submission-panel

<pl-external-grader-results></pl-external-grader-results>
<pl-file-preview></pl-file-preview>

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)