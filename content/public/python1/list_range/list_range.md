---
title: List Range
topic: Programming
author: Theresa Xiao
source: original
template_version: 1.4
attribution: standard
partialCredit: false
singleVariant: false
showCorrectAnswer: false
outcomes:
- 6.4.10.0
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
- test2
- TX
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: List Range
    params_vars_start: '2'
    params_vars_end: '70'
    params_vars_start_p1: '3'
    params_vars_start_m1: '1'
    params_vars_end_p1: '71'
    params_vars_end_m1: '69'
    params_section: but not including
    params_part1_ans1_value: '`list(range(2, 70))`'
    params_part1_ans1_feedback: Good job!
    params_part1_ans2_value: '`list(range([2, 70]))`'
    params_part1_ans2_feedback: Try again! Is the range() function correctly used?
    params_part1_ans3_value: '`list(range(1, 70))`'
    params_part1_ans3_feedback: Try again! Did you select the correct start bound?
    params_part1_ans4_value: '`list(range(2, 71))`'
    params_part1_ans4_feedback: Good job!
    params_part1_ans5_value: '`list(range(1, 71))`'
    params_part1_ans5_feedback: Try again! Are your start and end bounds correct?
    params_part1_ans6_value: '`list(range(2, 69))`'
    params_part1_ans6_feedback: Try again! Did you select the correct end bound?
    params_part1_ans7_value: '`list(range(0, 70))`'
    params_part1_ans7_feedback: Try again! Did you select the correct start bound?
    params_part1_ans8_value: '`list(range(0, 69))`'
    params_part1_ans8_feedback: Try again! Are your start and end bounds correct?
    params_part1_ans9_value: '`list(range(3, 69))`'
    params_part1_ans9_feedback: Try again! Are your start and end bounds correct?
---
# {{ params_vars_title }}

## Part 1

Which of these commands would create a list of numbers starting at `{{ params_vars_start }}` and up to (`{{ params_section }}`) `{{ params_vars_end }}`?

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}
- {{ params_part1_ans5_value }}
- {{ params_part1_ans6_value }}
- {{ params_part1_ans7_value }}
- {{ params_part1_ans8_value }}
- {{ params_part1_ans9_value }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)