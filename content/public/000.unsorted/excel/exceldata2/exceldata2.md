---
title: Excel Data 2
topic: Data Analysis
author: Aidan Murphy
source: 5.45
template_version: 1.4
attribution: standard
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
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
- undefined
tags:
- APM
assets:
- data.png
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Excel Data 2
    params_target: =AND(C6=A8, B4<B14)
    params_part1_ans1_value: 'False'
    params_part1_ans1_feedback: Awesome!
    params_part1_ans2_value: 'True'
    params_part1_ans2_feedback: you might need to check both conditions!
    params_part1_ans3_value: Unable to determine without the formulas
    params_part1_ans3_feedback: this question does not require the formulas
    params_part1_ans4_value: Need to see more rows to determine definitively
    params_part1_ans4_feedback: we can see an empty row signifying the end of the
      data
---
# {{ params_vars_title }}
Use the image of the data below to answer this question about Microsoft Excel.

## Part 1

If the conditional format rule in cell C7 is: <code>{{params_target}}</code>, the format will be applied.

<pl-figure file-name="data.png" directory="clientFilesQuestion" width="300"></pl-figure>

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

### pl-submission-panel

Everything here will get inserted directly into the pl-submission-panel element at the end of the `question.html`.
Please remove this section if it is not application for this question.

### pl-answer-panel

Everything here will get inserted directly into an pl-answer-panel element at the end of the `question.html`.
Please remove this section if it is not application for this question.

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)