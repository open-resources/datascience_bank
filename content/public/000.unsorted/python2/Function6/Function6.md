---
title: Edit List
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
    params_vars_title: Edit List
    params_vars_amount: double
    params_names_for_user: []
    params_names_from_user:
    - name: double_index
    params_ref_vars_numerical_amount: 2
    params_examples_numbers1: '[4, 5, 6, 7, 4]'
    params_examples_index1: 1
    params_examples_output1: '[4, 10, 6, 7, 4]'
    params_examples_numbers2: '[7, 6, 10, 5, 9]'
    params_examples_index2: -3
    params_examples_output2: '[7, 6, 20, 5, 9]'
---
# {{ params_vars_title }}

## Question Text

Create a function named `{{ params_vars_amount }}_index` that has two parameters named `numbers` and `index`.
The function should return a **new** list where all elements are the same as in `numbers` except for the element at `index`, which should be double its original value.
If `index` is not a valid index, the function should just return the original list. Negative indexes that are valid should work as well.

You do not need to validate the type and contents of the input list `numbers`, its guaranteed to be a list, and of types that support multiplication with integers, such as but not limited to `int` and `float`, but the length of the list is not guaranteed, and empty lists are valid inputs. Furthermore, `index` is guaranteed to be an integer, but the size and sign are not guaranteed.

Some example outputs to help you understand the problem:

1. `{{ params_vars_amount }}_index({{ params_examples_numbers1 }}, {{ params_examples_index1 }}) == {{ params_examples_output1 }}`
1. `{{ params_vars_amount }}_index({{ params_examples_numbers2 }}, {{ params_examples_index2 }}) == {{ params_examples_output2 }}`

### Answer Section

### pl-submission-panel

<pl-external-grader-results></pl-external-grader-results>
<pl-file-preview></pl-file-preview>

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)