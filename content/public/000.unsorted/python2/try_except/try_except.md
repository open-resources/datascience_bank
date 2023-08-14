---
title: Try Except
topic: Programming
author: Isabella Mendoza
source: undefined
template_version: 1.4
attribution: standard
partialCredit: false
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
- test2
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    none-of-the-above: true
    weight: 1
myst:
  substitutions:
    params_vars_title: Try Except
    params_vars_num: three
    params_part1_ans1_value: 'Prints three lines: hi! huh? ok'
    params_part1_ans1_feedback: Correct! Nice work!
    params_part1_ans2_value: 'Prints two lines: huh? ok'
    params_part1_ans2_feedback: Not quite - try again! Does the first print statement
      run?
    params_part1_ans3_value: 'Prints three lines: hi! nope huh?'
    params_part1_ans3_feedback: Not quite - try again! Check your operands!
    params_part1_ans4_value: 'Prints two lines: hi! huh?'
    params_part1_ans4_feedback: Not quite - try again! Does finally run?
---
# {{ params_vars_title }}

## Part 1

What is the output of the following code?

```
try:
    print("hi!")
    num = '{{ params_vars_num }}'
    if num % 3 != 0 :
        print("nope")
    else:
        print("yep")
except:
    print("huh?")
finally:
    print("ok")
```

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)