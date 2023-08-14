---
title: Function Output 4
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
    params_vars_title: Function Output 4
    params_vars_var1: numComplete
    params_vars_var2: totalSales
    params_vars_question_variant: ''
    params_vars_question_variant1: |2-

          {-_-}
    params_part1_ans1_value: Just numComplete
    params_part1_ans1_feedback: Try again!
    params_part1_ans2_value: Both numComplete and totalSales
    params_part1_ans2_feedback: Nice job!
    params_part1_ans3_value: Just totalSales
    params_part1_ans3_feedback: Try again!
    params_part1_ans4_value: Neither numComplete nor totalSales
    params_part1_ans4_feedback: Try again!
---
# Select the correct function

## Part 1

Which variables can be called in the spot marked by `{-_-}` in the following code.

*Hint: pay attention to the indenting.*

```
{{ params_vars_var1 }} = 0

def update():
    {{ params_vars_var2 }} = {{ params_vars_var1 }} + 1{{ params.vars.question_variant1 }}
    return {{ params_vars_var2 }}{{ params.vars.question_variant }}
```

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)