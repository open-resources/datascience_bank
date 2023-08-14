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
    params_vars_code: df[0:10].dropna(thresh=10)
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
      Name: Noibat
      Type 1: Flying
      Type 2: Dragon
      Total: 245
      HP: '40'
      Attack: '30'
      Defense: nan
      Sp. Atk: nan
      Sp. Def: '40'
      Speed: '55'
      Generation: 6
      Legendary: false
    - index: 1
      Name: Gulpin
      Type 1: Poison
      Type 2: null
      Total: 302
      HP: '70'
      Attack: '43'
      Defense: nan
      Sp. Atk: '43'
      Sp. Def: '53'
      Speed: nan
      Generation: 3
      Legendary: false
    - index: 2
      Name: Cryogonal
      Type 1: Ice
      Type 2: null
      Total: 485
      HP: nan
      Attack: '50'
      Defense: '30'
      Sp. Atk: nan
      Sp. Def: '135'
      Speed: '105'
      Generation: 5
      Legendary: false
    - index: 3
      Name: Woobat
      Type 1: Psychic
      Type 2: Flying
      Total: 313
      HP: '55'
      Attack: '45'
      Defense: '43'
      Sp. Atk: '55'
      Sp. Def: '43'
      Speed: '72'
      Generation: 5
      Legendary: false
    - index: 4
      Name: Magcargo
      Type 1: Fire
      Type 2: Rock
      Total: 410
      HP: '50'
      Attack: nan
      Defense: '120'
      Sp. Atk: '80'
      Sp. Def: nan
      Speed: '30'
      Generation: 2
      Legendary: false
    - index: 5
      Name: Caterpie
      Type 1: Bug
      Type 2: null
      Total: 195
      HP: '45'
      Attack: '30'
      Defense: nan
      Sp. Atk: nan
      Sp. Def: '20'
      Speed: '45'
      Generation: 1
      Legendary: false
    - index: 6
      Name: Magneton
      Type 1: Electric
      Type 2: Steel
      Total: 465
      HP: '50'
      Attack: '60'
      Defense: '95'
      Sp. Atk: '120'
      Sp. Def: nan
      Speed: '70'
      Generation: 1
      Legendary: false
    - index: 7
      Name: Spearow
      Type 1: Normal
      Type 2: Flying
      Total: 262
      HP: nan
      Attack: '60'
      Defense: nan
      Sp. Atk: '31'
      Sp. Def: '31'
      Speed: '70'
      Generation: 1
      Legendary: false
    - index: 8
      Name: Scolipede
      Type 1: Bug
      Type 2: Poison
      Total: 485
      HP: nan
      Attack: '100'
      Defense: '89'
      Sp. Atk: '55'
      Sp. Def: '69'
      Speed: '112'
      Generation: 5
      Legendary: false
    - index: 9
      Name: WormadamSandy Cloak
      Type 1: Bug
      Type 2: Ground
      Total: 424
      HP: nan
      Attack: '79'
      Defense: '105'
      Sp. Atk: '59'
      Sp. Def: '85'
      Speed: '36'
      Generation: 4
      Legendary: false
    params_part1_ans1_value: 3 rows get dropped
    params_part1_ans1_feedback: Great job!
    params_part1_ans2_value: 1 rows get dropped
    params_part1_ans2_feedback: You should be able to determine how many get dropped.
    params_part1_ans3_value: 2 rows get dropped
    params_part1_ans3_feedback: You should be able to determine how many get dropped.
    params_part1_ans4_value: 4 rows get dropped
    params_part1_ans4_feedback: You should be able to determine how many get dropped.
    params_part1_ans5_value: 5 rows get dropped
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