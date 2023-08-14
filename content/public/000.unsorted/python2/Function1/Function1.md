---
title: Sum Values
topic: Programming
author: Gavin Kendal-Freedman
source: original
template_version: 1.0
attribution: standard
partialCredit: true
singleVariant: false
showCorrectAnswer: false
gradingMethod: External
externalGradingOptions:
  enabled: true
  image: prairielearn/grader-python
  entrypoint: /python_autograder/run.sh
  timeout: 60
outcomes:
- 6.4.3.0
- 6.4.9.0
- 6.4.10.0
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
- autograder
- test3
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
    params_vars_title: Sum Values
    params_vars_name: sum_values
    params_vars_parameter: my_dictionary
    params_vars_structure_name: dictionary
    params_vars_structure: dict
    params_vars_view: values
    params_names_for_user: []
    params_names_from_user:
    - name: sum_values
---
# {{ params_vars_title }}

## Question Text

Write a function named `{{ params_vars_name }}` that accepts a parameter named `{{ params_vars_parameter }}` (of type `{{ params_vars_structure }}`).
The function should return the `sum` of all the numeric {{ params_vars_view }} in the {{ params_vars_structure_name }}.
You may **not** assume all the values are numbers.

### Answer Section

### pl-submission-panel

<pl-external-grader-results></pl-external-grader-results>
<pl-file-preview></pl-file-preview>

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)