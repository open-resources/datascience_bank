---
title: Penguins 3
topic: Data Visualization
author: Aidan Murphy
source: 5.45
template_version: 1.4
attribution: standard
partialCredit: true
singleVariant: true
showCorrectAnswer: false
outcomes:
- 8.2.1.0
difficulty:
- low
randomization:
- none
taxonomy:
- undefined
span:
- undefined
length:
- 1
tags:
- APM
assets:
- description.png
- penguins.png
- viz2.png
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Penguins 3
    params_part1_ans1_value: Yes, the plot is overplotted.
    params_part1_ans1_feedback: Correct, this plot is too elaborate
    params_part1_ans2_value: No, the plot is not overplotted.
    params_part1_ans2_feedback: The plot is too crowded to provide clear insight
    params_part1_ans3_value: It is not possible to determine
    params_part1_ans3_feedback: If you are uncertain, the plot is probably too complex
---
# {{ params_vars_title }}
In this quiz we will be looking at exploring the `penguins` dataset.

<img src="penguins.png" width="50%">

You can load the `penguins` dataset in `seaborn` using:

```
df = sns.load_dataset("penguins")
```

This dataset contains information about three species of penguins (Adelie, Gentoo, and Chinstrap), and various
characteristics including their bill_length, bill_depth, flipper_length, body_mass, and sex.

<img src="description.png" width="50%">

Credit: Artwork by [@allison_horst](https://www.allisonhorst.com).

Consider the following plot of the `penguins` dataset:

<img src="viz2.png">

## Part 1

__Is this plot overplotted?__

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}

### pl-submission-panel

### pl-answer-panel

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)