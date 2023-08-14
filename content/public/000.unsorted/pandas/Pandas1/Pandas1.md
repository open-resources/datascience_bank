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
    params_vars_field: HP
    params_vars_code: df["HP"].max(skipna=False)
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
      Name: Numel
      Type 1: Fire
      Type 2: Ground
      Total: 305
      HP: '60'
      Attack: '60'
      Defense: nan
      Sp. Atk: '65'
      Sp. Def: nan
      Speed: nan
      Generation: 3
      Legendary: false
    - index: 1
      Name: Gardevoir
      Type 1: Psychic
      Type 2: Fairy
      Total: 518
      HP: '68'
      Attack: '65'
      Defense: nan
      Sp. Atk: '125'
      Sp. Def: '115'
      Speed: '80'
      Generation: 3
      Legendary: false
    - index: 2
      Name: Xerneas
      Type 1: Fairy
      Type 2: null
      Total: 680
      HP: '126'
      Attack: nan
      Defense: '95'
      Sp. Atk: '131'
      Sp. Def: '98'
      Speed: '99'
      Generation: 6
      Legendary: true
    - index: 3
      Name: Hippowdon
      Type 1: Ground
      Type 2: null
      Total: 525
      HP: nan
      Attack: nan
      Defense: '118'
      Sp. Atk: '68'
      Sp. Def: '72'
      Speed: '47'
      Generation: 4
      Legendary: false
    - index: 4
      Name: Sceptile
      Type 1: Grass
      Type 2: null
      Total: 530
      HP: '70'
      Attack: '85'
      Defense: '65'
      Sp. Atk: '105'
      Sp. Def: '85'
      Speed: '120'
      Generation: 3
      Legendary: false
    - index: 5
      Name: Probopass
      Type 1: Rock
      Type 2: Steel
      Total: 525
      HP: '60'
      Attack: '55'
      Defense: '145'
      Sp. Atk: nan
      Sp. Def: '150'
      Speed: '40'
      Generation: 4
      Legendary: false
    - index: 6
      Name: Quagsire
      Type 1: Water
      Type 2: Ground
      Total: 430
      HP: '95'
      Attack: '85'
      Defense: '85'
      Sp. Atk: '65'
      Sp. Def: '65'
      Speed: '35'
      Generation: 2
      Legendary: false
    - index: 7
      Name: Shuppet
      Type 1: Ghost
      Type 2: null
      Total: 295
      HP: '44'
      Attack: '75'
      Defense: '35'
      Sp. Atk: '63'
      Sp. Def: nan
      Speed: '45'
      Generation: 3
      Legendary: false
    - index: 8
      Name: Carbink
      Type 1: Rock
      Type 2: Fairy
      Total: 500
      HP: nan
      Attack: '50'
      Defense: '150'
      Sp. Atk: nan
      Sp. Def: '150'
      Speed: nan
      Generation: 6
      Legendary: false
    - index: 9
      Name: Litleo
      Type 1: Fire
      Type 2: Normal
      Total: 369
      HP: '62'
      Attack: '50'
      Defense: '58'
      Sp. Atk: '73'
      Sp. Def: '54'
      Speed: '72'
      Generation: 6
      Legendary: false
    params_part1_ans1_value: '126.00'
    params_part1_ans1_feedback: Try again.
    params_part1_ans2_value: nan
    params_part1_ans2_feedback: Great job!
    params_part1_ans3_value: '68.00'
    params_part1_ans3_feedback: Close, but not quite! Try again.
    params_part1_ans4_value: '125.00'
    params_part1_ans4_feedback: Close, but not quite! Try again.
    params_part1_ans5_value: '60.00'
    params_part1_ans5_feedback: Close, but not quite! Try again.
    params_part1_ans6_value: '255.00'
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