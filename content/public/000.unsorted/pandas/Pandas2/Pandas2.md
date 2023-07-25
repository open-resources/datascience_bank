---
title: Pandas 2
topic: Data Analysis
author: Gavin Kendal-Freedman
source: unknown
template_version: 1.4
attribution: standard
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.3.1.0
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
- test3
assets:
- pokemon.csv
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Pandas 2
    params_vars_code: df[0:10].dropna()
    params_df__type: dataframe_v2
    params_df__value_schema_fields:
    - name: index
      type: integer
    - name: Name
      type: string
    - name: Type 1
      type: string
    - name: Type 2
      type: string
    - name: Total
      type: integer
    - name: HP
      type: string
    - name: Attack
      type: string
    - name: Defense
      type: string
    - name: Sp. Atk
      type: string
    - name: Sp. Def
      type: string
    - name: Speed
      type: string
    - name: Generation
      type: integer
    - name: Legendary
      type: boolean
    params_df__value_schema_primaryKey:
    - index
    params_df__value_schema_pandas_version: 1.4.0
    params_df__value_data:
    - index: 0
      Name: Crobat
      Type 1: Poison
      Type 2: Flying
      Total: 535
      HP: '85'
      Attack: '90'
      Defense: '80'
      Sp. Atk: nan
      Sp. Def: nan
      Speed: '130'
      Generation: 2
      Legendary: false
    - index: 1
      Name: RotomFan Rotom
      Type 1: Electric
      Type 2: Flying
      Total: 520
      HP: '50'
      Attack: '65'
      Defense: '107'
      Sp. Atk: nan
      Sp. Def: nan
      Speed: nan
      Generation: 4
      Legendary: false
    - index: 2
      Name: Zoroark
      Type 1: Dark
      Type 2: null
      Total: 510
      HP: '60'
      Attack: '105'
      Defense: '60'
      Sp. Atk: '120'
      Sp. Def: nan
      Speed: '105'
      Generation: 5
      Legendary: false
    - index: 3
      Name: Weavile
      Type 1: Dark
      Type 2: Ice
      Total: 510
      HP: '70'
      Attack: '120'
      Defense: '65'
      Sp. Atk: '45'
      Sp. Def: '85'
      Speed: '125'
      Generation: 4
      Legendary: false
    - index: 4
      Name: Hypno
      Type 1: Psychic
      Type 2: null
      Total: 483
      HP: nan
      Attack: '73'
      Defense: '70'
      Sp. Atk: '73'
      Sp. Def: '115'
      Speed: '67'
      Generation: 1
      Legendary: false
    - index: 5
      Name: Wynaut
      Type 1: Psychic
      Type 2: null
      Total: 260
      HP: '95'
      Attack: '23'
      Defense: '48'
      Sp. Atk: '23'
      Sp. Def: '48'
      Speed: '23'
      Generation: 3
      Legendary: false
    - index: 6
      Name: Florges
      Type 1: Fairy
      Type 2: null
      Total: 552
      HP: nan
      Attack: '65'
      Defense: nan
      Sp. Atk: '112'
      Sp. Def: '154'
      Speed: '75'
      Generation: 6
      Legendary: false
    - index: 7
      Name: Wobbuffet
      Type 1: Psychic
      Type 2: null
      Total: 405
      HP: '190'
      Attack: '33'
      Defense: '58'
      Sp. Atk: '33'
      Sp. Def: '58'
      Speed: '33'
      Generation: 2
      Legendary: false
    - index: 8
      Name: Joltik
      Type 1: Bug
      Type 2: Electric
      Total: 319
      HP: '50'
      Attack: '47'
      Defense: '50'
      Sp. Atk: '57'
      Sp. Def: '50'
      Speed: '65'
      Generation: 5
      Legendary: false
    - index: 9
      Name: Drifloon
      Type 1: Ghost
      Type 2: Flying
      Total: 348
      HP: nan
      Attack: nan
      Defense: nan
      Sp. Atk: nan
      Sp. Def: '44'
      Speed: nan
      Generation: 4
      Legendary: false
    params_part1_ans1_value: 8 rows get dropped
    params_part1_ans1_feedback: Great job!
    params_part1_ans2_value: 6 rows get dropped
    params_part1_ans2_feedback: You should be able to determine how many get dropped.
    params_part1_ans3_value: 7 rows get dropped
    params_part1_ans3_feedback: You should be able to determine how many get dropped.
    params_part1_ans4_value: 9 rows get dropped
    params_part1_ans4_feedback: You should be able to determine how many get dropped.
    params_part1_ans5_value: 10 rows get dropped
    params_part1_ans5_feedback: You should be able to determine how many get dropped.
    params_part1_ans6_value: Unable to determine how many rows get dropped
    params_part1_ans6_feedback: You should be able to determine how many get dropped.
---
# {{ params_vars_title }}
This question uses 10 random rows from a modified version of the pokemon dataset (`df`):

<pl-dataframe params-name="df" show-dimensions=true show-python=false></pl-dataframe>

## Part 1

Based on the table above, what is the output of the following code:

```python
{{{ params_vars_code }}}
```

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}
- {{ params_part1_ans5_value }}
- {{ params_part1_ans6_value }}

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)