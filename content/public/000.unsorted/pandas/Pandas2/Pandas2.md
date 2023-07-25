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
    params_vars_code: df[0:10].dropna(axis=1, thresh=5)
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
      Name: Poochyena
      Type 1: Dark
      Type 2: null
      Total: 220
      HP: '35'
      Attack: '55'
      Defense: '35'
      Sp. Atk: nan
      Sp. Def: '30'
      Speed: '35'
      Generation: 3
      Legendary: false
    - index: 1
      Name: RotomMow Rotom
      Type 1: Electric
      Type 2: Grass
      Total: 520
      HP: '50'
      Attack: '65'
      Defense: '107'
      Sp. Atk: nan
      Sp. Def: '107'
      Speed: nan
      Generation: 4
      Legendary: false
    - index: 2
      Name: PumpkabooSuper Size
      Type 1: Ghost
      Type 2: Grass
      Total: 335
      HP: nan
      Attack: '66'
      Defense: '70'
      Sp. Atk: nan
      Sp. Def: '55'
      Speed: '41'
      Generation: 6
      Legendary: false
    - index: 3
      Name: Togekiss
      Type 1: Fairy
      Type 2: Flying
      Total: 545
      HP: '85'
      Attack: '50'
      Defense: '95'
      Sp. Atk: '120'
      Sp. Def: '115'
      Speed: '80'
      Generation: 4
      Legendary: false
    - index: 4
      Name: Garbodor
      Type 1: Poison
      Type 2: null
      Total: 474
      HP: '80'
      Attack: '95'
      Defense: nan
      Sp. Atk: '60'
      Sp. Def: '82'
      Speed: '75'
      Generation: 5
      Legendary: false
    - index: 5
      Name: Machamp
      Type 1: Fighting
      Type 2: null
      Total: 505
      HP: '90'
      Attack: '130'
      Defense: '80'
      Sp. Atk: '65'
      Sp. Def: '85'
      Speed: nan
      Generation: 1
      Legendary: false
    - index: 6
      Name: Goomy
      Type 1: Dragon
      Type 2: null
      Total: 300
      HP: '45'
      Attack: '50'
      Defense: '35'
      Sp. Atk: '55'
      Sp. Def: '75'
      Speed: '40'
      Generation: 6
      Legendary: false
    - index: 7
      Name: Archen
      Type 1: Rock
      Type 2: Flying
      Total: 401
      HP: '55'
      Attack: '112'
      Defense: '45'
      Sp. Atk: nan
      Sp. Def: nan
      Speed: '70'
      Generation: 5
      Legendary: false
    - index: 8
      Name: Fraxure
      Type 1: Dragon
      Type 2: null
      Total: 410
      HP: nan
      Attack: nan
      Defense: '70'
      Sp. Atk: '40'
      Sp. Def: '50'
      Speed: '67'
      Generation: 5
      Legendary: false
    - index: 9
      Name: Sudowoodo
      Type 1: Rock
      Type 2: null
      Total: 410
      HP: '70'
      Attack: nan
      Defense: '115'
      Sp. Atk: '30'
      Sp. Def: '65'
      Speed: nan
      Generation: 2
      Legendary: false
    params_part1_ans1_value: 1 columns get dropped
    params_part1_ans1_feedback: Great job!
    params_part1_ans2_value: 0 columns get dropped
    params_part1_ans2_feedback: You should be able to determine how many get dropped.
    params_part1_ans3_value: 2 columns get dropped
    params_part1_ans3_feedback: You should be able to determine how many get dropped.
    params_part1_ans4_value: 3 columns get dropped
    params_part1_ans4_feedback: You should be able to determine how many get dropped.
    params_part1_ans5_value: 4 columns get dropped
    params_part1_ans5_feedback: You should be able to determine how many get dropped.
    params_part1_ans6_value: Unable to determine how many columns get dropped
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