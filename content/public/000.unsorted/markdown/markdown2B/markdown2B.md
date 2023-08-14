---
title: Markdown Images
topic: Markdown
author: Gavin Kendal-Freedman
source: 5.45
template_version: 1.4
attribution: standard
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.2.8.0
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
- test1
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Markdown Images
    params_vars_ext: '{EXT}'
    params_part1_ans1_value: '`[Accessible text](img2.{ext})!`'
    params_part1_ans1_feedback: Think about this one again, does it make sense to
      have the exclamation mark at the end?
    params_part1_ans2_value: '`[Accessible text](img2.{EXT})!`'
    params_part1_ans2_feedback: Think about this one again, does it make sense to
      have the exclamation mark at the end?
    params_part1_ans3_value: '`![Accessible text](img2.{ext}]`'
    params_part1_ans3_feedback: Think about this one again, does it make sense to
      have the brackets like this?
    params_part1_ans4_value: '`![Accessible text](img2.{ext})`'
    params_part1_ans4_feedback: Think about this one again, does it make sense to
      have the file extension lowercase?
    params_part1_ans5_value: '`![Accessible text](img2.{EXT})`'
    params_part1_ans5_feedback: Great! You got it.
    params_part1_ans6_value: '`[Accessible text]!(img2.{ext})`'
    params_part1_ans6_feedback: Think about this one again, does it make sense to
      have the exclamation mark in the middle?
    params_part1_ans7_value: '`[Accessible text]!(img2.{EXT})`'
    params_part1_ans7_feedback: Think about this one again, does it make sense to
      have the exclamation mark in the middle?
    params_part1_ans8_value: '`!![](img2.{ext})`'
    params_part1_ans8_feedback: Think about this one again, does it make sense to
      have two exclamation mark at the start, and no accessible text?
    params_part1_ans9_value: '`!![](img2.{EXT})`'
    params_part1_ans9_feedback: Think about this one again, does it make sense to
      have two exclamation mark at the start, and no accessible text?
---
# {{ params_vars_title }}

## Part 1

Which of the following options is the most correct way to display an image (named `img2.{{ params_vars_ext }}`) to a markdown file?

### Answer Section

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)