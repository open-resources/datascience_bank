---
title: Modify List
topic: Programming
author: Gavin Kendal-Freedman
source: undefined
template_version: 1.4
attribution: standard
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 6.4.10.0
- 6.4.3.0
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
- GKF
part1:
  type: checkbox
  pl-customizations:
    weight: 1
    partial-credit: true
    partial-credit-method: EDC
myst:
  substitutions:
    params_vars_title: Modify List
    params_vars_starting_provinces: Yukon Territory, Manitoba, and Saskatchewan
    params_vars_direction: remove
    params_vars_num_starting: three
    params_vars_to_from: from
    params_vars_prov1: Saskatchewan
    params_vars_prov2: Manitoba
    params_vars_pluralization: s
    params_vars_additional: ''
    params_part1_ans1_value: provinces = [i for i in provinces if i not in ["Saskatchewan",
      "Manitoba"]]
    params_part1_ans1_feedback: Good job!
    params_part1_ans2_value: provinces = [i for i in provinces if i in ["Saskatchewan",
      "Manitoba"]]
    params_part1_ans2_feedback: This is not quite right.
    params_part1_ans3_value: provinces.remove("Manitoba"); provinces.remove("Saskatchewan")
    params_part1_ans3_feedback: Good job!
    params_part1_ans4_value: provinces = provinces - ["Saskatchewan", "Manitoba"]
    params_part1_ans4_feedback: This is not quite right.
    params_part1_ans5_value: provinces.remove(["Saskatchewan", "Manitoba"])
    params_part1_ans5_feedback: This is not quite right.
    params_part1_ans6_value: provinces = list(set(provinces) - ('{prov1}', '{prov2}'))
    params_part1_ans6_feedback: Good job!
    params_part1_ans7_value: provinces.remove("Saskatchewan","Manitoba")
    params_part1_ans7_feedback: This is not quite right.
    params_part1_ans8_value: provinces.difference(["Saskatchewan", "Manitoba"])
    params_part1_ans8_feedback: This is not quite right.
---
# {{ params_vars_title }}
Imagine there is a list called `provinces` that has {{ params.vars.num_starting }} province{{ params_vars_pluralization }}, {{ params.vars.starting_provinces }} in it.

## Part 1

Which of the following would allow us to `{{ params_vars_direction }}` "{{ params_vars_prov1 }}" and "{{ params_vars_prov2 }}" {{ params.vars.to_from }} the `provinces` list{{{ params_vars_additional }}}?

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}
- {{ params_part1_ans5_value }}
- {{ params_part1_ans6_value }}
- {{ params_part1_ans7_value }}
- {{ params_part1_ans8_value }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)