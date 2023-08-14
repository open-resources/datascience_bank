---
title: Pandas 1
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
    params_vars_title: Pandas 1
    params_vars_field: Speed
    params_vars_code: df["Speed"].median()
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
      Name: Terrakion
      Type 1: Rock
      Type 2: Fighting
      Total: 580
      HP: '91'
      Attack: '129'
      Defense: nan
      Sp. Atk: '72'
      Sp. Def: '90'
      Speed: '108'
      Generation: 5
      Legendary: true
    - index: 1
      Name: GourgeistAverage Size
      Type 1: Ghost
      Type 2: Grass
      Total: 494
      HP: nan
      Attack: '90'
      Defense: '122'
      Sp. Atk: '58'
      Sp. Def: '75'
      Speed: '84'
      Generation: 6
      Legendary: false
    - index: 2
      Name: Buneary
      Type 1: Normal
      Type 2: null
      Total: 350
      HP: nan
      Attack: '66'
      Defense: '44'
      Sp. Atk: nan
      Sp. Def: '56'
      Speed: nan
      Generation: 4
      Legendary: false
    - index: 3
      Name: Dialga
      Type 1: Steel
      Type 2: Dragon
      Total: 680
      HP: '100'
      Attack: '120'
      Defense: '120'
      Sp. Atk: '150'
      Sp. Def: nan
      Speed: '90'
      Generation: 4
      Legendary: true
    - index: 4
      Name: Shiftry
      Type 1: Grass
      Type 2: Dark
      Total: 480
      HP: '90'
      Attack: nan
      Defense: '60'
      Sp. Atk: '90'
      Sp. Def: '60'
      Speed: nan
      Generation: 3
      Legendary: false
    - index: 5
      Name: Nidoran♀
      Type 1: Poison
      Type 2: null
      Total: 275
      HP: '55'
      Attack: '47'
      Defense: '52'
      Sp. Atk: nan
      Sp. Def: '40'
      Speed: '41'
      Generation: 1
      Legendary: false
    - index: 6
      Name: Finneon
      Type 1: Water
      Type 2: null
      Total: 330
      HP: '49'
      Attack: '49'
      Defense: nan
      Sp. Atk: '49'
      Sp. Def: nan
      Speed: '66'
      Generation: 4
      Legendary: false
    - index: 7
      Name: Spearow
      Type 1: Normal
      Type 2: Flying
      Total: 262
      HP: '40'
      Attack: '60'
      Defense: '30'
      Sp. Atk: '31'
      Sp. Def: '31'
      Speed: '70'
      Generation: 1
      Legendary: false
    - index: 8
      Name: Paras
      Type 1: Bug
      Type 2: Grass
      Total: 285
      HP: '35'
      Attack: '70'
      Defense: '55'
      Sp. Atk: '45'
      Sp. Def: '55'
      Speed: '25'
      Generation: 1
      Legendary: false
    - index: 9
      Name: Drilbur
      Type 1: Ground
      Type 2: null
      Total: 328
      HP: '60'
      Attack: nan
      Defense: '40'
      Sp. Atk: '30'
      Sp. Def: '45'
      Speed: '68'
      Generation: 5
      Legendary: false
    params_part1_ans1_value: '69.00'
    params_part1_ans1_feedback: Great job!
    params_part1_ans2_value: nan
    params_part1_ans2_feedback: Try again.
    params_part1_ans3_value: '68.28'
    params_part1_ans3_feedback: Close, but not quite! Try again.
    params_part1_ans4_value: '65.00'
    params_part1_ans4_feedback: Close, but not quite! Try again.
    params_part1_ans5_value: '75.00'
    params_part1_ans5_feedback: Close, but not quite! Try again.
    params_part1_ans6_value: '71.70'
    params_part1_ans6_feedback: Close, but not quite! Try again.
---
# {{ params_vars_title }}
This question uses 10 random rows from a modified version of the pokemon dataset (`df`):

<pl-dataframe params-name="df" show-dimensions="false" show-python=false></pl-dataframe>

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