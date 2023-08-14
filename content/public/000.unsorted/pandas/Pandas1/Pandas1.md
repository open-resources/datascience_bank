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
    params_vars_field: Defense
    params_vars_code: df["Defense"].min()
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
      Name: Venipede
      Type 1: Bug
      Type 2: Poison
      Total: 260
      HP: '30'
      Attack: '45'
      Defense: '59'
      Sp. Atk: '30'
      Sp. Def: '39'
      Speed: nan
      Generation: 5
      Legendary: false
    - index: 1
      Name: Glalie
      Type 1: Ice
      Type 2: null
      Total: 480
      HP: nan
      Attack: '80'
      Defense: '80'
      Sp. Atk: '80'
      Sp. Def: '80'
      Speed: '80'
      Generation: 3
      Legendary: false
    - index: 2
      Name: GourgeistSmall Size
      Type 1: Ghost
      Type 2: Grass
      Total: 494
      HP: '55'
      Attack: '85'
      Defense: '122'
      Sp. Atk: '58'
      Sp. Def: '75'
      Speed: '99'
      Generation: 6
      Legendary: false
    - index: 3
      Name: Cottonee
      Type 1: Grass
      Type 2: Fairy
      Total: 280
      HP: nan
      Attack: nan
      Defense: '60'
      Sp. Atk: '37'
      Sp. Def: nan
      Speed: '66'
      Generation: 5
      Legendary: false
    - index: 4
      Name: Torchic
      Type 1: Fire
      Type 2: null
      Total: 310
      HP: '45'
      Attack: '60'
      Defense: nan
      Sp. Atk: nan
      Sp. Def: '50'
      Speed: '45'
      Generation: 3
      Legendary: false
    - index: 5
      Name: Leavanny
      Type 1: Bug
      Type 2: Grass
      Total: 500
      HP: '75'
      Attack: '103'
      Defense: '80'
      Sp. Atk: '70'
      Sp. Def: '80'
      Speed: '92'
      Generation: 5
      Legendary: false
    - index: 6
      Name: Shieldon
      Type 1: Rock
      Type 2: Steel
      Total: 350
      HP: '30'
      Attack: '42'
      Defense: '118'
      Sp. Atk: '42'
      Sp. Def: '88'
      Speed: nan
      Generation: 4
      Legendary: false
    - index: 7
      Name: Finneon
      Type 1: Water
      Type 2: null
      Total: 330
      HP: '49'
      Attack: nan
      Defense: '56'
      Sp. Atk: '49'
      Sp. Def: '61'
      Speed: '66'
      Generation: 4
      Legendary: false
    - index: 8
      Name: Golbat
      Type 1: Poison
      Type 2: Flying
      Total: 455
      HP: '75'
      Attack: '80'
      Defense: nan
      Sp. Atk: '65'
      Sp. Def: '75'
      Speed: '90'
      Generation: 1
      Legendary: false
    - index: 9
      Name: GardevoirMega Gardevoir
      Type 1: Psychic
      Type 2: Fairy
      Total: 618
      HP: '68'
      Attack: '85'
      Defense: '65'
      Sp. Atk: nan
      Sp. Def: nan
      Speed: '100'
      Generation: 3
      Legendary: false
    params_part1_ans1_value: '56.00'
    params_part1_ans1_feedback: Great job!
    params_part1_ans2_value: nan
    params_part1_ans2_feedback: Try again.
    params_part1_ans3_value: '80.00'
    params_part1_ans3_feedback: Close, but not quite! Try again.
    params_part1_ans4_value: '40.00'
    params_part1_ans4_feedback: Close, but not quite! Try again.
    params_part1_ans5_value: '5.00'
    params_part1_ans5_feedback: Close, but not quite! Try again.
    params_part1_ans6_value: '63.00'
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