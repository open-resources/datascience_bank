---
title: Penguins 1
topic: Data Analysis
author: Edwin Zhou
source: unknown
template_version: 1.4
attribution: standard
partialCredit: false
singleVariant: false
showCorrectAnswer: false
outcomes:
- 6.4.11.0
- 7.3.1.0
- 7.3.2.3
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
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Penguins 1
    params_vars_rand_title_1: island
    params_vars_rand_title_2: bill_depth_mm
    params_vars_rand_title_3: bill_length_mm
    params_part1_ans1_value: The code above is currently dropping rows, rather than
      columns.
    params_part1_ans1_feedback: Good job!
    params_part1_ans2_value: There is a spelling mistake in the names of the columns
      we're trying to drop.
    params_part1_ans2_feedback: Try again!
    params_part1_ans3_value: The `.drop()` function requires a list of lists, rather
      than just a list when dropping multiple columns.
    params_part1_ans3_feedback: Try again!
    params_part1_ans4_value: The `.drop()` function cannot be used to drop more than
      one column at a time.
    params_part1_ans4_feedback: Try again!
    params_part1_ans5_value: None of these options.
    params_part1_ans5_feedback: Try again!
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

We would like to drop three columns from the dataframe: `{{ params.vars.rand_title_1 }}`, `{{ params.vars.rand_title_2 }}`, and
`{{ params.vars.rand_title_3 }}`.

The following code:

```
df.drop(['{{ params.vars.rand_title_1 }}','{{ params.vars.rand_title_2 }}','{{ params.vars.rand_title_3 }}'])
```

gives this error:

```
KeyError: "['{{ params.vars.rand_title_1 }}' '{{ params.vars.rand_title_2 }}' '{{ params.vars.rand_title_3 }}'] not found in axis".
```

Why is the error happening?

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}
- {{ params_part1_ans5_value }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)