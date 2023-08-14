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
    params_vars_code: df["HP"].min(skipna=False)
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
      Name: WormadamPlant Cloak
      Type 1: Bug
      Type 2: Grass
      Total: 424
      HP: '60'
      Attack: '59'
      Defense: '85'
      Sp. Atk: '79'
      Sp. Def: nan
      Speed: nan
      Generation: 4
      Legendary: false
    - index: 1
      Name: Scrafty
      Type 1: Dark
      Type 2: Fighting
      Total: 488
      HP: '65'
      Attack: '90'
      Defense: '115'
      Sp. Atk: '45'
      Sp. Def: '115'
      Speed: '58'
      Generation: 5
      Legendary: false
    - index: 2
      Name: Psyduck
      Type 1: Water
      Type 2: null
      Total: 320
      HP: '50'
      Attack: '52'
      Defense: '48'
      Sp. Atk: '65'
      Sp. Def: '50'
      Speed: '55'
      Generation: 1
      Legendary: false
    - index: 3
      Name: GourgeistSuper Size
      Type 1: Ghost
      Type 2: Grass
      Total: 494
      HP: nan
      Attack: nan
      Defense: '122'
      Sp. Atk: '58'
      Sp. Def: '75'
      Speed: '54'
      Generation: 6
      Legendary: false
    - index: 4
      Name: Raichu
      Type 1: Electric
      Type 2: null
      Total: 485
      HP: nan
      Attack: '90'
      Defense: '55'
      Sp. Atk: nan
      Sp. Def: '80'
      Speed: nan
      Generation: 1
      Legendary: false
    - index: 5
      Name: Kecleon
      Type 1: Normal
      Type 2: null
      Total: 440
      HP: '60'
      Attack: '90'
      Defense: '70'
      Sp. Atk: '60'
      Sp. Def: nan
      Speed: '40'
      Generation: 3
      Legendary: false
    - index: 6
      Name: ScizorMega Scizor
      Type 1: Bug
      Type 2: Steel
      Total: 600
      HP: '70'
      Attack: nan
      Defense: '140'
      Sp. Atk: nan
      Sp. Def: '100'
      Speed: '75'
      Generation: 2
      Legendary: false
    - index: 7
      Name: Jellicent
      Type 1: Water
      Type 2: Ghost
      Total: 480
      HP: '100'
      Attack: '60'
      Defense: nan
      Sp. Atk: '85'
      Sp. Def: '105'
      Speed: '60'
      Generation: 5
      Legendary: false
    - index: 8
      Name: Magikarp
      Type 1: Water
      Type 2: null
      Total: 200
      HP: '20'
      Attack: '10'
      Defense: nan
      Sp. Atk: '15'
      Sp. Def: '20'
      Speed: '80'
      Generation: 1
      Legendary: false
    - index: 9
      Name: Furret
      Type 1: Normal
      Type 2: null
      Total: 415
      HP: '85'
      Attack: '76'
      Defense: '64'
      Sp. Atk: '45'
      Sp. Def: '55'
      Speed: '90'
      Generation: 2
      Legendary: false
    params_part1_ans1_value: '20.00'
    params_part1_ans1_feedback: Try again.
    params_part1_ans2_value: nan
    params_part1_ans2_feedback: Great job!
    params_part1_ans3_value: '65.00'
    params_part1_ans3_feedback: Close, but not quite! Try again.
    params_part1_ans4_value: '60.00'
    params_part1_ans4_feedback: Close, but not quite! Try again.
    params_part1_ans5_value: '21.00'
    params_part1_ans5_feedback: Close, but not quite! Try again.
    params_part1_ans6_value: '1.00'
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