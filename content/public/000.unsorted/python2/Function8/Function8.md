---
title: Item Frequency
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
    params_vars_title: Item Frequency
    params_vars_name: at_most_n
    params_vars_direction: at most
    params_vars_example: '`False`'
    params_vars_reason: does not appear
    params_names_for_user: []
    params_names_from_user:
    - name: at_most_n
    params_ref_vars_operator: le
    params_ref_vars_example: false
---
# {{ params_vars_title }}

## Question Text

Create a function named `{{ params_vars_name }}` that has three parameters named `lst`, `item`, and `n`.
The function should return `True` if `item` appears in the list {{ params_vars_direction }} `n` times.
The function should return `False` otherwise.
For example, the following code:

```python
lst = [5, 10 , 15, 15, 15, 20, 25, 30]
{{ params_vars_name }}(lst, item=15, n=2)
```

should return {{{ params_vars_example }}} because `15` {{ params_vars_reason }} in `lst` {{ params_vars_direction }} `n` times.

You do not need to worry about checking that inputs are valid, but the parameter names must be exact.

*Hint: You may use `lst.count(item)` in an `if` statement.*

### Answer Section

### pl-submission-panel

<pl-external-grader-results></pl-external-grader-results>
<pl-file-preview></pl-file-preview>

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)