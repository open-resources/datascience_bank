---
title: Type Error 2
topic: Programming
author: Isabella Mendoza
source: undefined
template_version: 1.4
attribution: standard
partialCredit: false
singleVariant: false
showCorrectAnswer: false
outcomes:
- 6.4.7.0
- 6.4.12.0
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
- BM
- test2
assets: null
part1:
  type: checkbox
  pl-customizations:
    weight: 1
    partial-credit: true
    partial-credit-method: EDC
myst:
  substitutions:
    params_vars_title: Type Error 2
    params_vars_given: x[0]
    params_part1_ans1_value: str
    params_part1_ans1_feedback: Correct! Nice work!
    params_part1_ans2_value: list
    params_part1_ans2_feedback: Correct! Nice work!
    params_part1_ans3_value: tuple
    params_part1_ans3_feedback: Correct! Nice work!
    params_part1_ans4_value: dict
    params_part1_ans4_feedback: Correct! Nice work!
    params_part1_ans5_value: numpy array
    params_part1_ans5_feedback: Correct! Nice work!
    params_part1_ans6_value: pandas dataframe
    params_part1_ans6_feedback: Correct! Nice work!
    params_part1_ans7_value: set
    params_part1_ans7_feedback: Not quite, this data type is unordered! Try again!
    params_part1_ans8_value: int
    params_part1_ans8_feedback: Not quite, this data type is not a collection! Try
      again!
    params_part1_ans9_value: float
    params_part1_ans9_feedback: Not quite, this data type is not a collection! Try
      again!
    params_part1_ans10_value: bool
    params_part1_ans10_feedback: Not quite, this data type is not a collection! Try
      again!
    params_part1_ans11_value: range
    params_part1_ans11_feedback: Not quite, is not a data type! Try again!
---
# {{ params_vars_title }}

## Part 1

Assume a variable `x` is of unknown type.

For which variable types will the code `{{ params_vars_given }}` run successfully (assuming the variable is populated correctly)?

### Answer Section

Select all the choices that apply.

Note: You will be awarded full marks only if you select all the correct choices, and none of the incorrect choices. Choosing incorrect choices as well as not choosing correct choices will result in deductions.

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}
- {{ params_part1_ans5_value }}
- {{ params_part1_ans6_value }}
- {{ params_part1_ans7_value }}
- {{ params_part1_ans8_value }}
- {{ params_part1_ans9_value }}
- {{ params_part1_ans10_value }}
- {{ params_part1_ans11_value }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)