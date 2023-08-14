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
    params_vars_code: df[0:10].dropna(axis=1)
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
      Name: Duosion
      Type 1: Psychic
      Type 2: null
      Total: 370
      HP: nan
      Attack: nan
      Defense: '50'
      Sp. Atk: '125'
      Sp. Def: '60'
      Speed: '30'
      Generation: 5
      Legendary: false
    - index: 1
      Name: Ampharos
      Type 1: Electric
      Type 2: null
      Total: 510
      HP: '90'
      Attack: '75'
      Defense: '85'
      Sp. Atk: '115'
      Sp. Def: '90'
      Speed: nan
      Generation: 2
      Legendary: false
    - index: 2
      Name: Umbreon
      Type 1: Dark
      Type 2: null
      Total: 525
      HP: nan
      Attack: '65'
      Defense: '110'
      Sp. Atk: nan
      Sp. Def: '130'
      Speed: '65'
      Generation: 2
      Legendary: false
    - index: 3
      Name: Spritzee
      Type 1: Fairy
      Type 2: null
      Total: 341
      HP: nan
      Attack: '52'
      Defense: '60'
      Sp. Atk: '63'
      Sp. Def: '65'
      Speed: '23'
      Generation: 6
      Legendary: false
    - index: 4
      Name: RotomHeat Rotom
      Type 1: Electric
      Type 2: Fire
      Total: 520
      HP: '50'
      Attack: '65'
      Defense: nan
      Sp. Atk: '105'
      Sp. Def: '107'
      Speed: nan
      Generation: 4
      Legendary: false
    - index: 5
      Name: Bellossom
      Type 1: Grass
      Type 2: null
      Total: 490
      HP: '75'
      Attack: '80'
      Defense: '95'
      Sp. Atk: nan
      Sp. Def: '100'
      Speed: '50'
      Generation: 2
      Legendary: false
    - index: 6
      Name: DeoxysSpeed Forme
      Type 1: Psychic
      Type 2: null
      Total: 600
      HP: '50'
      Attack: '95'
      Defense: '90'
      Sp. Atk: nan
      Sp. Def: nan
      Speed: nan
      Generation: 3
      Legendary: true
    - index: 7
      Name: Espeon
      Type 1: Psychic
      Type 2: null
      Total: 525
      HP: '65'
      Attack: '65'
      Defense: '60'
      Sp. Atk: '130'
      Sp. Def: '95'
      Speed: nan
      Generation: 2
      Legendary: false
    - index: 8
      Name: Farfetch'd
      Type 1: Normal
      Type 2: Flying
      Total: 352
      HP: '52'
      Attack: nan
      Defense: '55'
      Sp. Atk: nan
      Sp. Def: '62'
      Speed: '60'
      Generation: 1
      Legendary: false
    - index: 9
      Name: Pineco
      Type 1: Bug
      Type 2: null
      Total: 290
      HP: '50'
      Attack: nan
      Defense: '90'
      Sp. Atk: '35'
      Sp. Def: nan
      Speed: '15'
      Generation: 2
      Legendary: false
    params_part1_ans1_value: 7 columns get dropped
    params_part1_ans1_feedback: Great job!
    params_part1_ans2_value: 5 columns get dropped
    params_part1_ans2_feedback: You should be able to determine how many get dropped.
    params_part1_ans3_value: 6 columns get dropped
    params_part1_ans3_feedback: You should be able to determine how many get dropped.
    params_part1_ans4_value: 8 columns get dropped
    params_part1_ans4_feedback: You should be able to determine how many get dropped.
    params_part1_ans5_value: 9 columns get dropped
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