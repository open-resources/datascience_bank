---
title: Markdown Links
topic: Markdown
author: Gavin Kendal-Freedman
source: 5.45
template_version: 1.4
attribution: standard
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.2.7.0
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
- GKF
- test1
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Markdown Links
    params_vars_prompt: embed a link to https://tsn.ca in the text "Touch here"
    params_part1_ans1_value: '`[Touch here(https://tsn.ca)] to visit the website.`'
    params_part1_ans1_feedback: Think about this one again, does it make sense to
      have the link combined like this?
    params_part1_ans2_value: '`Touch here&lt;https://tsn.ca&gt; to visit the website.`'
    params_part1_ans2_feedback: Close, but not quite.
    params_part1_ans3_value: '`[[Touch here[https://tsn.ca]]] to visit the website.`'
    params_part1_ans3_feedback: Think about this one again, does it make sense to
      have the brackets like this?
    params_part1_ans4_value: '`[Touch here](https://tsn.ca) to visit the website.`'
    params_part1_ans4_feedback: Great! You got it.
    params_part1_ans5_value: '`[Touch here]&lt;https://tsn.ca&gt; to visit the website.`'
    params_part1_ans5_feedback: Think about this one again, does it make sense to
      have the brackets like this?
    params_part1_ans6_value: '`[Touch here]|https://tsn.ca| to visit the website.`'
    params_part1_ans6_feedback: Think about this one again, does it make sense to
      have the brackets like this?
    params_part1_ans7_value: '`(Touch here)[https://tsn.ca] to visit the website.`'
    params_part1_ans7_feedback: Think about this one again, does it make sense to
      have the brackets like this?
---
# {{ params_vars_title }}

## Part 1

Which of the following options is the most correct way to {{ params_vars_prompt }}?

### Answer Section

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)