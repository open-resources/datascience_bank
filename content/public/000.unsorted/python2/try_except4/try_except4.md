---
title: Try Except
topic: Programming
author: Bella Mendoza
source: 5.45
template_version: 1.4
attribution: standard
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 6.4.12.0
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
- BM
- test4
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
    none-of-the-above: true
myst:
  substitutions:
    params_vars_title: Try Except
    params_vars_a: 0
    params_vars_b: 2
    params_part1_ans1_value: A ZeroDivisionError occurred.
    params_part1_ans1_feedback: Try again! This occurs when we divide by 0
    params_part1_ans2_value: 'Output of: result'
    params_part1_ans2_feedback: Great job!
    params_part1_ans3_value: A ValueError occurred
    params_part1_ans3_feedback: Try again! Look at the divisor!
    params_part1_ans4_value: A NameError occurred
    params_part1_ans4_feedback: Try again! Look at the divisor!
---
# {{ params_vars_title }}

## Part 1

What is the output of the following code?

```
def divide_two_numbers(x, y):
    result = x / y
    return result
try:
    result = divide_two_numbers({{ params_vars_a }},{{ params_vars_b }})
    print(result)
except NameError:
    print("A NameError occurred.")
except ValueError:
    print("A ValueError occurred.")
except ZeroDivisionError:
    print("A ZeroDivisionError occurred.")
```

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)