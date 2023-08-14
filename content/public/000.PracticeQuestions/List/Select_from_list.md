---
title: Select from a list
topic: Programming
author: Edwin Zhou
source: unknown
template_version: 1.4
attribution: standard
partialCredit: false
singleVariant: false
showCorrectAnswer: false
outcomes:
- undefined
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
- EZ
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Select from a list
    params_vars_mylist: '[79, 85, 64, 75, 74, 58, 76, 37, 68, 84, 28, 41, 53, 98,
      67]'
    params_vars_length: 15
    params_vars_select_num: 6
    params_vars_section: first
    params_vars_negate: ' everything but '
    params_part1_ans1_value: mylist[:6]
    params_part1_ans1_feedback: Try again! This selects the first elements of the
      list
    params_part1_ans2_value: mylist[-6:]
    params_part1_ans2_feedback: Try again! This selects the last elements of the list
    params_part1_ans3_value: mylist[4:10]
    params_part1_ans3_feedback: Try again! This selects the middle elements of the
      list
    params_part1_ans4_value: mylist[6:]
    params_part1_ans4_feedback: Good job!
    params_part1_ans5_value: mylist[:-6]
    params_part1_ans5_feedback: Try again! This selects everything but the last elements
      of the list
    params_part1_ans6_value: mylist[19:27]
    params_part1_ans6_feedback: Try again! This answer is incorrect
    params_part1_ans7_value: mylist[:7]
    params_part1_ans7_feedback: Try again! This answer is incorrect
    params_part1_ans8_value: mylist[-7:]
    params_part1_ans8_feedback: Try again! This answer is incorrect
    params_part1_ans9_value: mylist[3:11]
    params_part1_ans9_feedback: Try again! This answer is incorrect
    params_part1_ans10_value: None of them are correct
    params_part1_ans10_feedback: Try again! This answer is incorrect
---
# Select the correct function

## Part 1

Given that `mylist` of length `{{ params_vars_length }}` is defined as:

```
mylist = {{ params_vars_mylist }}
```

Which of the following code selects `{{ params_vars_negate }}` the `{{ params_vars_section }}` `{{ params.vars.select_num }}` elements of `mylist`?

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
- {{ params_part1_ans10_value }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)