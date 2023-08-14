---
title: Markdown Headings
topic: Markdown
author: Edwin Zhou
source: unknown
template_version: 1.4
attribution: standard
partialCredit: false
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.0
- 5.2.1.0
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
- test1
- EZ
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
    fixed-order: true
    number-answers: 3
myst:
  substitutions:
    params_vars_title: Markdown Headings
    params_vars_heading_number: H6
    params_vars_heading_level: '###### Heading level 6'
    params_part1_ans1_value: 'True'
    params_part1_ans1_feedback: Incorrect! `H6`, or `######` is the smallest font
      size available in a heading for a markdown document.
    params_part1_ans2_value: 'False'
    params_part1_ans2_feedback: Correct! `H6`, or `######` is the smallest font size
      available in a heading for a markdown document.
    params_part1_ans3_value: There is not enough information to determine.
    params_part1_ans3_feedback: Incorrect! There is enough information to determine
      the answer.
---
# Select the correct function

## Part 1

True or False?

**The largest font size available in a heading for a markdown document is `{{ params.vars.heading_number }}`, or `{{ params.vars.heading_level }}`.**

### Answer Section

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)