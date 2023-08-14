---
title: Function Output 2
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
    params_vars_title: Function Output 2
    params_vars_random_time: 1
    params_vars_am_pm: AM
    params_vars_mood: quiet
    params_vars_question_time: '    '
    params_vars_question_mood: ''
    params_vars_question_end: ''
    params_vars_is_defined: 'def '
    params_part1_ans1_value: No Strings are printed
    params_part1_ans1_feedback: Try again!
    params_part1_ans2_value: 'One String is printed: "The current time is 1 AM"'
    params_part1_ans2_feedback: Nice job!
    params_part1_ans3_value: 'Two Strings are printed: "The current time is 1 AM","The
      mood is quiet"'
    params_part1_ans3_feedback: Try again!
    params_part1_ans4_value: 'Three Strings are printed: "The current time is 1 AM",
      "The mood is quiet", "End of report"'
    params_part1_ans4_feedback: Try again!
    params_part1_ans5_value: An error because the function is not defined correctly.
    params_part1_ans5_feedback: Try again!
---
# Select the correct function

## Part 1

Given the following code block, what happens if you call the `report()` function?

```python
time = "{{ params.vars.random_time }} {{ params.vars.am_pm }}"
mood = "{{ params_vars_mood }}"
{{ params.vars.is_defined }}report():
    report_time = time
    report_mood = mood
{{ params.vars.question_time }}print('The current time is ' + report_time)
{{ params.vars.question_mood }}print('The mood is ' + report_mood)
{{ params.vars.question_end }}print('End of report')

```

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}
- {{ params_part1_ans5_value }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)