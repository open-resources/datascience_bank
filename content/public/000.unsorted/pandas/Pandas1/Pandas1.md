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
    params_vars_code: df["Speed"].max()
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
      Name: Sableye
      Type 1: Dark
      Type 2: Ghost
      Total: 380
      HP: '50'
      Attack: '75'
      Defense: '75'
      Sp. Atk: nan
      Sp. Def: '65'
      Speed: '50'
      Generation: 3
      Legendary: false
    - index: 1
      Name: Pelipper
      Type 1: Water
      Type 2: Flying
      Total: 430
      HP: '60'
      Attack: nan
      Defense: '100'
      Sp. Atk: '85'
      Sp. Def: '70'
      Speed: '65'
      Generation: 3
      Legendary: false
    - index: 2
      Name: SharpedoMega Sharpedo
      Type 1: Water
      Type 2: Dark
      Total: 560
      HP: '70'
      Attack: nan
      Defense: '70'
      Sp. Atk: '110'
      Sp. Def: '65'
      Speed: nan
      Generation: 3
      Legendary: false
    - index: 3
      Name: Pachirisu
      Type 1: Electric
      Type 2: null
      Total: 405
      HP: '60'
      Attack: '45'
      Defense: nan
      Sp. Atk: '45'
      Sp. Def: nan
      Speed: '95'
      Generation: 4
      Legendary: false
    - index: 4
      Name: Buneary
      Type 1: Normal
      Type 2: null
      Total: 350
      HP: '55'
      Attack: '66'
      Defense: '44'
      Sp. Atk: '44'
      Sp. Def: '56'
      Speed: '85'
      Generation: 4
      Legendary: false
    - index: 5
      Name: Garbodor
      Type 1: Poison
      Type 2: null
      Total: 474
      HP: '80'
      Attack: '95'
      Defense: '82'
      Sp. Atk: '60'
      Sp. Def: '82'
      Speed: '75'
      Generation: 5
      Legendary: false
    - index: 6
      Name: Yanma
      Type 1: Bug
      Type 2: Flying
      Total: 390
      HP: nan
      Attack: '65'
      Defense: nan
      Sp. Atk: '75'
      Sp. Def: '45'
      Speed: '95'
      Generation: 2
      Legendary: false
    - index: 7
      Name: Bonsly
      Type 1: Rock
      Type 2: null
      Total: 290
      HP: '50'
      Attack: '80'
      Defense: '95'
      Sp. Atk: nan
      Sp. Def: '45'
      Speed: '10'
      Generation: 4
      Legendary: false
    - index: 8
      Name: Nidoran♂
      Type 1: Poison
      Type 2: null
      Total: 273
      HP: nan
      Attack: '57'
      Defense: '40'
      Sp. Atk: '40'
      Sp. Def: nan
      Speed: '50'
      Generation: 1
      Legendary: false
    - index: 9
      Name: Metapod
      Type 1: Bug
      Type 2: null
      Total: 205
      HP: '50'
      Attack: '20'
      Defense: nan
      Sp. Atk: '25'
      Sp. Def: nan
      Speed: nan
      Generation: 1
      Legendary: false
    params_part1_ans1_value: '95.00'
    params_part1_ans1_feedback: Great job!
    params_part1_ans2_value: nan
    params_part1_ans2_feedback: Try again.
    params_part1_ans3_value: '65.00'
    params_part1_ans3_feedback: Close, but not quite! Try again.
    params_part1_ans4_value: '180.00'
    params_part1_ans4_feedback: Close, but not quite! Try again.
    params_part1_ans5_value: '60.00'
    params_part1_ans5_feedback: Close, but not quite! Try again.
    params_part1_ans6_value: '105.00'
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