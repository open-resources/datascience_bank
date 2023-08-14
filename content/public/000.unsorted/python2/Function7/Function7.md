---
title: Slice List
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
- 6.4.5.0
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
    params_vars_title: Slice List
    params_vars_name: keep_middle
    params_vars_participle: exclusively kept
    params_vars_example: 8, 15, 16
    params_names_for_user: []
    params_names_from_user:
    - name: keep_middle
    params_ref_vars_action: keep
---
# {{ params_vars_title }}

## Question Text

Create a function named `{{ params_vars_name }}` which has three parameters named `lst`, `start`, and `end`; these variables will be a list, an integer and an integer respectively.
The function should return a list where all elements in `lst` with an index between `start` and `end` (inclusive) have been {{ params_vars_participle }}.

*You do not need to validate the type or contents of any parameters, but the parameter names must be exact.*

For example, the following code:

```python
lst = [4, 8 , 15, 16, 23, 42]
{{ params_vars_name }}(lst, start=1, end=3)
```

should return `[{{ params_vars_example }}]` because elements at indices 1, 2, and 3 have been {{ params_vars_participle }}.

### Answer Section

### pl-submission-panel

<pl-external-grader-results></pl-external-grader-results>
<pl-file-preview></pl-file-preview>

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)