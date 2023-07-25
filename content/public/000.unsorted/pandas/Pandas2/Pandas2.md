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
    params_vars_code: df[0:10].dropna(how="all")
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
      Name: Frillish
      Type 1: Water
      Type 2: Ghost
      Total: 335
      HP: '55'
      Attack: '40'
      Defense: '50'
      Sp. Atk: '65'
      Sp. Def: '85'
      Speed: '40'
      Generation: 5
      Legendary: false
    - index: 1
      Name: Crawdaunt
      Type 1: Water
      Type 2: Dark
      Total: 468
      HP: nan
      Attack: '120'
      Defense: '85'
      Sp. Atk: '90'
      Sp. Def: '55'
      Speed: '55'
      Generation: 3
      Legendary: false
    - index: 2
      Name: Pangoro
      Type 1: Fighting
      Type 2: Dark
      Total: 495
      HP: '95'
      Attack: '124'
      Defense: nan
      Sp. Atk: nan
      Sp. Def: '71'
      Speed: '58'
      Generation: 6
      Legendary: false
    - index: 3
      Name: Loudred
      Type 1: Normal
      Type 2: null
      Total: 360
      HP: nan
      Attack: '71'
      Defense: nan
      Sp. Atk: '71'
      Sp. Def: nan
      Speed: nan
      Generation: 3
      Legendary: false
    - index: 4
      Name: MewtwoMega Mewtwo X
      Type 1: Psychic
      Type 2: Fighting
      Total: 780
      HP: '106'
      Attack: '190'
      Defense: '100'
      Sp. Atk: '154'
      Sp. Def: '100'
      Speed: nan
      Generation: 1
      Legendary: true
    - index: 5
      Name: Parasect
      Type 1: Bug
      Type 2: Grass
      Total: 405
      HP: '60'
      Attack: '95'
      Defense: '80'
      Sp. Atk: '60'
      Sp. Def: '80'
      Speed: '30'
      Generation: 1
      Legendary: false
    - index: 6
      Name: Golett
      Type 1: Ground
      Type 2: Ghost
      Total: 303
      HP: '59'
      Attack: '74'
      Defense: nan
      Sp. Atk: '35'
      Sp. Def: '50'
      Speed: '35'
      Generation: 5
      Legendary: false
    - index: 7
      Name: Ferrothorn
      Type 1: Grass
      Type 2: Steel
      Total: 489
      HP: nan
      Attack: '94'
      Defense: '131'
      Sp. Atk: '54'
      Sp. Def: '116'
      Speed: nan
      Generation: 5
      Legendary: false
    - index: 8
      Name: RotomFrost Rotom
      Type 1: Electric
      Type 2: Ice
      Total: 520
      HP: '50'
      Attack: '65'
      Defense: '107'
      Sp. Atk: '105'
      Sp. Def: '107'
      Speed: '86'
      Generation: 4
      Legendary: false
    - index: 9
      Name: Cherrim
      Type 1: Grass
      Type 2: null
      Total: 450
      HP: '70'
      Attack: nan
      Defense: nan
      Sp. Atk: nan
      Sp. Def: '78'
      Speed: '85'
      Generation: 4
      Legendary: false
    params_part1_ans1_value: 0 rows get dropped
    params_part1_ans1_feedback: Great job!
    params_part1_ans2_value: 1 rows get dropped
    params_part1_ans2_feedback: You should be able to determine how many get dropped.
    params_part1_ans3_value: 2 rows get dropped
    params_part1_ans3_feedback: You should be able to determine how many get dropped.
    params_part1_ans4_value: 3 rows get dropped
    params_part1_ans4_feedback: You should be able to determine how many get dropped.
    params_part1_ans5_value: 4 rows get dropped
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