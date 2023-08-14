---
title: Partial List
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
- 6.4.4.0
- 6.4.7.0
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
    params_vars_title: Partial List
    params_vars_mode: delete
    params_vars_action: remove
    params_vars_side: ending
    params_vars_type: even
    params_vars_direction: back
    params_vars_trigger: last
    params_vars_name: delete_ending_evens
    params_vars_instruction: then return the `input` list as it is
    params_vars_ex_out: '[5, 9, 11, 12, 13]'
    params_vars_ex_in: '[5, 9, 11, 12, 13, 16]'
    params_names_for_user: []
    params_names_from_user:
    - name: delete_ending_evens
    params_ref_vars_example:
    - 5
    - 9
    - 11
    - 12
    - 13
    - 16
---
# {{ params_vars_title }}

## Question Text

Write a function called `{{ params_vars_name }}()` that has a parameter named `input`, which is a list.
The function should {{ params_vars_action }} elements from the {{ params_vars_direction }} of `input` until the {{ params_vars_trigger }} number of the list is not an {{ params_vars_type }} number.
If the {{ params_vars_trigger }} number is not an **{{ params_vars_type }}** number, {{{ params_vars_instruction }}}.
You should **not** assume the list will only have numbers.
For example, the following code:

```python
input = {{ params.vars.ex_in }}
{{ params_vars_name }}(input)
```

should return `{{ params.vars.ex_out }}`.

### Answer Section

### pl-submission-panel

<pl-external-grader-results></pl-external-grader-results>
<pl-file-preview></pl-file-preview>

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)