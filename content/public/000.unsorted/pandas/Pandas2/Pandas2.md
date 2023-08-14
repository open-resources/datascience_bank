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
    params_vars_code: df[0:10].dropna(how="all", axis=1)
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
      Name: Koffing
      Type 1: Poison
      Type 2: null
      Total: 340
      HP: nan
      Attack: '65'
      Defense: '95'
      Sp. Atk: '60'
      Sp. Def: '45'
      Speed: '35'
      Generation: 1
      Legendary: false
    - index: 1
      Name: Woobat
      Type 1: Psychic
      Type 2: Flying
      Total: 313
      HP: '55'
      Attack: nan
      Defense: nan
      Sp. Atk: nan
      Sp. Def: '43'
      Speed: '72'
      Generation: 5
      Legendary: false
    - index: 2
      Name: GyaradosMega Gyarados
      Type 1: Water
      Type 2: Dark
      Total: 640
      HP: '95'
      Attack: '155'
      Defense: nan
      Sp. Atk: '70'
      Sp. Def: nan
      Speed: '81'
      Generation: 1
      Legendary: false
    - index: 3
      Name: Porygon
      Type 1: Normal
      Type 2: null
      Total: 395
      HP: '65'
      Attack: '60'
      Defense: '70'
      Sp. Atk: nan
      Sp. Def: nan
      Speed: nan
      Generation: 1
      Legendary: false
    - index: 4
      Name: Carbink
      Type 1: Rock
      Type 2: Fairy
      Total: 500
      HP: nan
      Attack: nan
      Defense: '150'
      Sp. Atk: '50'
      Sp. Def: '150'
      Speed: '50'
      Generation: 6
      Legendary: false
    - index: 5
      Name: Poochyena
      Type 1: Dark
      Type 2: null
      Total: 220
      HP: '35'
      Attack: '55'
      Defense: nan
      Sp. Atk: '30'
      Sp. Def: nan
      Speed: '35'
      Generation: 3
      Legendary: false
    - index: 6
      Name: Infernape
      Type 1: Fire
      Type 2: Fighting
      Total: 534
      HP: '76'
      Attack: '104'
      Defense: '71'
      Sp. Atk: '104'
      Sp. Def: '71'
      Speed: '108'
      Generation: 4
      Legendary: false
    - index: 7
      Name: Lotad
      Type 1: Water
      Type 2: Grass
      Total: 220
      HP: '40'
      Attack: '30'
      Defense: nan
      Sp. Atk: nan
      Sp. Def: '50'
      Speed: '30'
      Generation: 3
      Legendary: false
    - index: 8
      Name: Pansage
      Type 1: Grass
      Type 2: null
      Total: 316
      HP: '50'
      Attack: nan
      Defense: '48'
      Sp. Atk: nan
      Sp. Def: nan
      Speed: '64'
      Generation: 5
      Legendary: false
    - index: 9
      Name: Mankey
      Type 1: Fighting
      Type 2: null
      Total: 305
      HP: '40'
      Attack: '80'
      Defense: '35'
      Sp. Atk: '35'
      Sp. Def: '45'
      Speed: '70'
      Generation: 1
      Legendary: false
    params_part1_ans1_value: 0 columns get dropped
    params_part1_ans1_feedback: Great job!
    params_part1_ans2_value: 1 columns get dropped
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