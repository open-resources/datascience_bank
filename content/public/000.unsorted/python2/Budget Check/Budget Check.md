---
title: Budget Check
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
- 6.4.8.0
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
    params_vars_title: Over Budget
    params_vars_fname: on_budget
    params_vars_outcomes_0: 'False'
    params_vars_outcomes_1: 'False'
    params_vars_outcomes_2: 'True'
    params_vars_outcomes_list:
    - false
    - false
    - true
    params_names_for_user: []
    params_names_from_user:
    - name: on_budget
---
# {{ params_vars_title }}

## Question Text

Create a function called `{{params_vars_fname}}` that has five parameters named `budget`, `food_bill`, `electricity_bill`, `internet_bill`, and `rent`. These parameters will always be positive integers.

Your function should return `{{params_vars_outcomes_0}}` if `budget` is less than the sum of the other four parameters.

Your function should return `{{params_vars_outcomes_1}}` if `budget` is greater than the sum of the other four parameters.

Your function should return `{{params_vars_outcomes_2}}` if `budget` is exactly equal to the sum of the other four parameters.

### Answer Section

### pl-submission-panel

<pl-external-grader-results></pl-external-grader-results>
<pl-file-preview></pl-file-preview>

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)