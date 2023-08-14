---
title: Paths
topic: File Systems
author: Borna Shani
source: 5.45
template_version: 1.4
attribution: standard
partialCredit: true
singleVariant: true
showCorrectAnswer: false
outcomes:
- 1.2.1.0
- 1.4.1.0
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
- BS
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Local Paths
    params_part1_ans1_value: '`./test1/alpha/a_level3/file2.md`'
    params_part1_ans1_feedback: Try Again!
    params_part1_ans2_value: '`/test1/alpha/a_level3/file2.md`'
    params_part1_ans2_feedback: Great! You got it.
    params_part1_ans3_value: '`../test1/alpha/a_level3/file2.md`'
    params_part1_ans3_feedback: Try Again!
    params_part1_ans4_value: '`./file2.md`'
    params_part1_ans4_feedback: Try Again!
    params_part1_ans5_value: '`/c/alpha/a_level3/file2.md`'
    params_part1_ans5_feedback: Try Again!
    params_part1_ans6_value: '`/d/alpha/a_level3/file2.md`'
    params_part1_ans6_feedback: Try Again!
    params_part1_ans7_value: '`/f/alpha/a_level3/file2.md`'
    params_part1_ans7_feedback: Try Again!
---
# {{ params_vars_title }}

## Part 1

With the following directory structure (output of tree) of the `test1` directory placed at the root of the system, what is the **absolute path** of `file2.md` ?

```
test1
├── alpha
│   ├── a_level1
│   │   ├── file2.md
│   │   ├── file4.md
│   │   └── file5.md
│   ├── a_level2
│   │   └── file1.md
│   └── a_level3
│       └── file3.md
├── beta
│   ├── b_level1
│   │   └── file6.md
│   ├── b_level2
│   │   ├── file7.md
│   │   └── file8.md
│   └── b_level3
│       └── file9.md
├── epsilon
│   ├── e_level1
│   ├── e_level2
│   └── e_level3
└── gamma
    ├── g_level1
    ├── g_level2
    └── g_level3
```

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}
- {{ params_part1_ans5_value }}
- {{ params_part1_ans6_value }}
- {{ params_part1_ans7_value }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)