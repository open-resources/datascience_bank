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
      Name: Slakoth
      Type 1: Normal
      Type 2: null
      Total: 280
      HP: nan
      Attack: nan
      Defense: '60'
      Sp. Atk: '35'
      Sp. Def: '35'
      Speed: '30'
      Generation: 3
      Legendary: false
    - index: 1
      Name: Shellder
      Type 1: Water
      Type 2: null
      Total: 305
      HP: '30'
      Attack: '65'
      Defense: '100'
      Sp. Atk: '45'
      Sp. Def: '25'
      Speed: '40'
      Generation: 1
      Legendary: false
    - index: 2
      Name: Sunflora
      Type 1: Grass
      Type 2: null
      Total: 425
      HP: '75'
      Attack: '75'
      Defense: '55'
      Sp. Atk: '105'
      Sp. Def: '85'
      Speed: nan
      Generation: 2
      Legendary: false
    - index: 3
      Name: Bunnelby
      Type 1: Normal
      Type 2: null
      Total: 237
      HP: '38'
      Attack: '36'
      Defense: nan
      Sp. Atk: nan
      Sp. Def: nan
      Speed: '57'
      Generation: 6
      Legendary: false
    - index: 4
      Name: Cofagrigus
      Type 1: Ghost
      Type 2: null
      Total: 483
      HP: '58'
      Attack: '50'
      Defense: '145'
      Sp. Atk: nan
      Sp. Def: nan
      Speed: nan
      Generation: 5
      Legendary: false
    - index: 5
      Name: Lillipup
      Type 1: Normal
      Type 2: null
      Total: 275
      HP: '45'
      Attack: '60'
      Defense: '45'
      Sp. Atk: '25'
      Sp. Def: '45'
      Speed: '55'
      Generation: 5
      Legendary: false
    - index: 6
      Name: Noivern
      Type 1: Flying
      Type 2: Dragon
      Total: 535
      HP: '85'
      Attack: nan
      Defense: '80'
      Sp. Atk: '97'
      Sp. Def: '80'
      Speed: '123'
      Generation: 6
      Legendary: false
    - index: 7
      Name: Hitmontop
      Type 1: Fighting
      Type 2: null
      Total: 455
      HP: '50'
      Attack: nan
      Defense: nan
      Sp. Atk: nan
      Sp. Def: '110'
      Speed: '70'
      Generation: 2
      Legendary: false
    - index: 8
      Name: Diancie
      Type 1: Rock
      Type 2: Fairy
      Total: 600
      HP: '50'
      Attack: nan
      Defense: '150'
      Sp. Atk: nan
      Sp. Def: '150'
      Speed: '50'
      Generation: 6
      Legendary: true
    - index: 9
      Name: Entei
      Type 1: Fire
      Type 2: null
      Total: 580
      HP: '115'
      Attack: '115'
      Defense: '85'
      Sp. Atk: '90'
      Sp. Def: nan
      Speed: nan
      Generation: 2
      Legendary: true
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