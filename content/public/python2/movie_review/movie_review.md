---
title: Movie Review
topic: Programming
author: Theresa Xiao
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
- 6.4.11.0
- 6.4.6.0
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
- TX
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
    params_vars_title: Movie Review
    params_vars_lower: 3
    params_vars_upper: 7
    params_names_for_user: []
    params_names_from_user:
    - name: movie_review
      description: receives a single numerical input, returns if it should be filtered
      type: function
    params_examples_num1: 5
    params_examples_output1: This one was fun.
    params_examples_num2: 0
    params_examples_output2: Avoid at all costs!
    params_examples_num3: 10
    params_examples_output3: Outstanding!
    params_examples_num4: 7
    params_examples_output4: Outstanding!
    params_examples_num5: 3
    params_examples_output5: Avoid at all costs!
---
# {{ params_vars_title }}

## Question Text

Create a function named `movie_review` that has one parameter named `rating`.

If `rating` is less than or equal to `{{ params_vars_lower }}`, return "Avoid at all costs!".
If `rating` is between `{{ params_vars_lower }}` and `{{ params_vars_upper }}` (exclusive), return "This one was fun.".
If `rating` is `{{ params_vars_upper }}` or above, return "Outstanding!".

Your function will always be passed valid inputs and `rating` will always be **an integer**.

You should consider testing your function with at least two different ratings (`test1` and `test2`), and use `assert` statements to confirm your function works correctly.

Some example outputs to help you understand the problem:

1. `movie_review({{ params_examples_num1 }}) == {{ params_examples_output1 }}`
1. `movie_review({{ params_examples_num2 }}) == {{ params_examples_output2 }}`
1. `movie_review({{ params_examples_num3 }}) == {{ params_examples_output3 }}`
1. `movie_review({{ params_examples_num4 }}) == {{ params_examples_output4 }}`
1. `movie_review({{ params_examples_num5 }}) == {{ params_examples_output5 }}`

### Answer Section

### pl-submission-panel

<pl-external-grader-results></pl-external-grader-results>
<pl-file-preview></pl-file-preview>

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)