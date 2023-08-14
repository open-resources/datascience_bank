---
title: Penguins 2
topic: Data Visualization
author: Edwin Zhou
source: unknown
template_version: 1.4
attribution: standard
partialCredit: false
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.3.1.0
- 8.2.1.0
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
- test4
- EZ
assets:
- description.png
- penguins.png
- viz1.png
part1:
  type: checkbox
  pl-customizations:
    weight: 1
    partial-credit: true
    partial-credit-method: EDC
myst:
  substitutions:
    params_vars_title: Penguins 2
    params_part1_ans1_value: Generally, the Adelie penguins have smaller bill lengths
      than the other two species.
    params_part1_ans1_feedback: Good job!
    params_part1_ans2_value: Generally, the Gentoo penguins and the Chinstrap penguins
      have similar bill lengths.
    params_part1_ans2_feedback: Good job!
    params_part1_ans3_value: Generally, Chinstrap penguins have the largest bill length.
    params_part1_ans3_feedback: Try again!
    params_part1_ans4_value: Generally, Gentoo penguins have the second largest bill
      length.
    params_part1_ans4_feedback: Try again!
    params_part1_ans5_value: Generally, all penguin species have very similar bill
      lengths.
    params_part1_ans5_feedback: Try again!
    params_part1_ans6_value: Generally, all penguin species have bill lengths over
      55 mm.
    params_part1_ans6_feedback: Try again!
---
# {{ params_vars_title }}
In this quiz we will be looking at exploring the `penguins` dataset.

<img src="penguins.png" width="50%">

## Part 1

You can load the `penguins` dataset in `seaborn` using:

```
df = sns.load_dataset("penguins")
```

This dataset contains information about three species of penguins (Adelie, Gentoo, and Chinstrap), and various
characteristics including their bill_length, bill_depth, flipper_length, body_mass, and sex.

<img src="description.png" width="50%">
Credit: Artwork by [@allison_horst](https://www.allisonhorst.com).

Which of the following claims can you make from **only** the violin plot below:

<img src="viz1.png" width="50%">

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}
- {{ params_part1_ans5_value }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)