---
title: Excel Data 5
topic: Data Analysis
author: Aidan Murphy
source: original
template_version: 1.4
attribution: standard
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.6.1.0
- 7.6.2.0
difficulty:
- undefined
randomization:
- undefined
taxonomy:
- undefined
span:
- undefined
length:
- 2
tags:
- APM
assets:
- data.png
part1:
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: true
    label: $ans1= $
    suffix: null
part2:
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: true
    label: $ans2= $
    suffix: null
myst:
  substitutions:
    params_vars_title: Excel Data 5
    params_target1: =D15+D5&B9
    params_target2: =D17+D5&B7
---
# {{ params_vars_title }}
Use the image of the data below to answer this question about Microsoft Excel.

<pl-figure file-name="data.png" directory="clientFilesQuestion" width="300"></pl-figure>

## Part 1

What is the value of <code>{{params_target1}}</code>?

### Answer Section

Please enter your numerical answer.

### pl-submission-panel

{{ feedback.part1_ans }}

## Part 2

What is the value of <code>{{params_target2}}</code>?

### Answer Section

Please enter your numerical answer.

### pl-submission-panel

{{ feedback.part1_ans }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)