---
title: Function Output 3
topic: Programming
author: Edwin Zhou
source: unknown
template_version: 1.4
attribution: standard
partialCredit: false
singleVariant: false
showCorrectAnswer: false
outcomes:
- 6.4.2.0
- 6.4.11.0
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
- test3
- EZ
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Function Output3
    params_vars_random_mass: 43
    params_vars_random_accel: 11.4
    params_part1_ans1_value: force(43, 11.4)
    params_part1_ans1_feedback: Try again!
    params_part1_ans2_value: force(11.4, 43)
    params_part1_ans2_feedback: Try again!
    params_part1_ans3_value: force(mass=43, 11.4)
    params_part1_ans3_feedback: Try again!
    params_part1_ans4_value: force(acceleration=43, 11.4)
    params_part1_ans4_feedback: Try again!
    params_part1_ans5_value: force(43, mass=11.4)
    params_part1_ans5_feedback: Try again!
---
# Select the correct function

## Part 1

What line of code will call the `force` function with a value of `{{ params.vars.random_mass }}` for mass and a value of `{{ params.vars.random_accel }}` for acceleration?

```
def force(mass, acceleration):
    force_val = mass*acceleration
    return force_val
```

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}
- {{ params_part1_ans5_value }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)