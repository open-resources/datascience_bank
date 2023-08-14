---
title: Function Output
topic: Programming
author: Edwin Zhou
source: unknown
template_version: 1.4
attribution: standard
partialCredit: false
singleVariant: false
showCorrectAnswer: false
outcomes:
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
    params_vars_title: Function Output
    params_vars_quote_text: Time heals all wounds.
    params_vars_is_f_string: f
    params_vars_second_text: wounds.
    params_vars_variable: quote_text
    params_vars_first_text: '{quote_text}'
    params_part1_ans1_value: quote("Time heals all")
    params_part1_ans1_feedback: Nice job!
    params_part1_ans2_value: None of the listed options
    params_part1_ans2_feedback: Try again!
    params_part1_ans3_value: def quote("Time heals all")
    params_part1_ans3_feedback: Try again!
    params_part1_ans4_value: quote(Time heals all)
    params_part1_ans4_feedback: Try again!
    params_part1_ans5_value: quote()
    params_part1_ans5_feedback: Try again!
---
# Select the correct function

## Part 1

Given the following function,

```
def quote({{ params_vars_variable }}):
   print({{ params.vars.is_f_string }}"{{ params.vars.first_text }} {{ params.vars.second_text }}")
```

Which of the options below will produce the following output:

`"{{ params.vars.quote_text }}"`

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}
- {{ params_part1_ans5_value }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)