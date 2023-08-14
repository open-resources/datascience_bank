---
title: Larger Than
topic: Programming
author: Aidan Murphy
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
- 6.4.11.0
difficulty:
- moderate
randomization:
- basic
taxonomy:
- undefined
span:
- undefined
length:
- 1
tags:
- APM
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
    params_vars_title: Larger Than
    params_vars_multiple: 3
    params_vars_fname: higher_than
    params_names_for_user: []
    params_names_from_user:
    - name: higher_than
---
# {{ params_vars_title }}

## Question Text

Define a function called `{{ params_vars_fname }}()` that has **two** input variables: `first` and `second`, `first` should be the first input variable, and `second` the second. You can assume that both input variables will only be integers.

The function should return `True` if `first` is more than {{ params_vars_multiple }} times the value of `second`, and `False` otherwise. You can assume the function will only receive valid inputs. You are not required to include error handling.

### Answer Section

### pl-submission-panel

<pl-external-grader-results></pl-external-grader-results>
<pl-file-preview></pl-file-preview>

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)