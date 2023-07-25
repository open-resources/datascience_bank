---
title: Python Conditionals
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
- 6.4.8.0
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
    params_vars_title: Python Conditionals
    params_vars_lower: -127
    params_vars_upper: 152
    params_vars_inclusive: exclusive
    params_vars_invert: even
    params_names_for_user: []
    params_names_from_user:
    - name: filter_num
      description: receives a single numerical input, returns if it should be filtered
      type: function
    params_ans_invert: 0
    params_ans_inclusive: false
    params_examples_num1: -82
    params_examples_output1: false
    params_examples_num2: -95
    params_examples_output2: true
    params_examples_num3: -172
    params_examples_output3: true
    params_examples_num4: 177
    params_examples_output4: false
---
# {{ params_vars_title }}

## Question Text

Create a function named `filter_num` that has one parameter named `num`. Using if/else statements, your variable `num`, and **all three operators** (or their variants) <code>></code>, <code>\<</code>, and <code>==</code> create a function that will return `True` when your number is between `{{ params_vars_lower }}` and `{{ params_vars_upper }}` (both {{ params_vars_inclusive }}), and `False` otherwise. However, if the number is `{{ params_vars_invert }}`, then the function should invert the otherwise expected output.

Your function will always be passed valid inputs and `num` will always be **an integer**.

You should consider testing your function with at least two different numbers (`test1` and `test2`), and use `assert` statements to confirm your function works correctly.

Some example outputs to help you understand the problem:

1. `filter_num({{ params_examples_num1 }}) == {{ params_examples_output1 }}`
1. `filter_num({{ params_examples_num2 }}) == {{ params_examples_output2 }}`
1. `filter_num({{ params_examples_num3 }}) == {{ params_examples_output3 }}`
1. `filter_num({{ params_examples_num4 }}) == {{ params_examples_output4 }}`

### Answer Section

### pl-submission-panel

<pl-external-grader-results></pl-external-grader-results>
<pl-file-preview></pl-file-preview>

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)