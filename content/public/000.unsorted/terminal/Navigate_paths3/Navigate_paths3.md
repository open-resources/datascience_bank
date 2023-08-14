---
title: Navigate Paths 3
topic: File Systems
author: Aidan Murphy
source: 5.45
template_version: 1.4
attribution: standard
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 1.3.1.0
difficulty:
- moderate
randomization:
- level 2
taxonomy:
- undefined
span:
- undefined
length:
- 1
tags:
- APM
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Navigate paths
    params_target: test1
    params_part1_ans1_value: alpha/a_level3/magic
    params_part1_ans1_feedback: Awesome!
    params_part1_ans2_value: ../alpha/a_level3/magic
    params_part1_ans2_feedback: carefully consider the starting directory
    params_part1_ans3_value: ../a_level3/magic
    params_part1_ans3_feedback: carefully consider the starting directory
    params_part1_ans4_value: a_level3/magic
    params_part1_ans4_feedback: carefully consider the starting directory
---
# {{ params_vars_title }}
For this question, consider the following directory structure (output of tree) of the `test1` directory placed at the root of the directory.

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

## Part 1

You are currently in the `{{params_target}}` directory and want to create a subdirectory inside `a_level3` called `magic`.
What path would you provide as a parameter/option to the command that creates a directory?

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

### pl-submission-panel

### pl-answer-panel

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)