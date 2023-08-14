---
title: Function Return
topic: Programming
author: Theresa Xiao
source: original
template_version: 1.4
attribution: standard
partialCredit: false
singleVariant: true
showCorrectAnswer: false
outcomes:
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
- TX
- test3
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Function Return
    params_part1_ans1_value: '`return inner_var`'
    params_part1_ans1_feedback: Great job! The return statement is exactly what we
      want in this case.
    params_part1_ans2_value: '`inner_var = None`'
    params_part1_ans2_feedback: Are we trying to change the value of inner_var?
    params_part1_ans3_value: '`def inner_var`'
    params_part1_ans3_feedback: What does the def keyword do?
    params_part1_ans4_value: '`print(inner_var)`'
    params_part1_ans4_feedback: What does the print() function do?
    params_part1_ans5_value: '`Last line of the function should be inner_var`'
    params_part1_ans5_feedback: Are we doing anything to the variable just by stating
      it?
---
# {{ params_vars_title }}

## Part 1

Which of the options below should be used to pass a variable `inner_var` that exists inside a function, back to where the function was called (i.e. outside the function)?

### Answer Section

- {{ params_part1_ans1_value }} {{ params.vars.units}}
- {{ params_part1_ans2_value }} {{ params.vars.units}}
- {{ params_part1_ans3_value }} {{ params.vars.units}}
- {{ params_part1_ans4_value }} {{ params.vars.units}}
- {{ params_part1_ans5_value }} {{ params.vars.units}}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)