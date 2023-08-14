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
    params_vars_field: Attack
    params_vars_code: df["Attack"].median(skipna=False)
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
      Name: Sealeo
      Type 1: Ice
      Type 2: Water
      Total: 410
      HP: '90'
      Attack: nan
      Defense: '70'
      Sp. Atk: nan
      Sp. Def: '70'
      Speed: '45'
      Generation: 3
      Legendary: false
    - index: 1
      Name: GiratinaAltered Forme
      Type 1: Ghost
      Type 2: Dragon
      Total: 680
      HP: '150'
      Attack: nan
      Defense: '120'
      Sp. Atk: '100'
      Sp. Def: '120'
      Speed: '90'
      Generation: 4
      Legendary: true
    - index: 2
      Name: Fletchling
      Type 1: Normal
      Type 2: Flying
      Total: 278
      HP: nan
      Attack: '50'
      Defense: nan
      Sp. Atk: '40'
      Sp. Def: '38'
      Speed: '62'
      Generation: 6
      Legendary: false
    - index: 3
      Name: Chikorita
      Type 1: Grass
      Type 2: null
      Total: 318
      HP: '45'
      Attack: '49'
      Defense: '65'
      Sp. Atk: '49'
      Sp. Def: '65'
      Speed: '45'
      Generation: 2
      Legendary: false
    - index: 4
      Name: Purugly
      Type 1: Normal
      Type 2: null
      Total: 452
      HP: '71'
      Attack: '82'
      Defense: nan
      Sp. Atk: '64'
      Sp. Def: '59'
      Speed: '112'
      Generation: 4
      Legendary: false
    - index: 5
      Name: Gyarados
      Type 1: Water
      Type 2: Flying
      Total: 540
      HP: '95'
      Attack: '125'
      Defense: '79'
      Sp. Atk: '60'
      Sp. Def: '100'
      Speed: '81'
      Generation: 1
      Legendary: false
    - index: 6
      Name: Bronzor
      Type 1: Steel
      Type 2: Psychic
      Total: 300
      HP: '57'
      Attack: '24'
      Defense: '86'
      Sp. Atk: '24'
      Sp. Def: nan
      Speed: nan
      Generation: 4
      Legendary: false
    - index: 7
      Name: Pineco
      Type 1: Bug
      Type 2: null
      Total: 290
      HP: nan
      Attack: '65'
      Defense: '90'
      Sp. Atk: '35'
      Sp. Def: '35'
      Speed: nan
      Generation: 2
      Legendary: false
    - index: 8
      Name: Musharna
      Type 1: Psychic
      Type 2: null
      Total: 487
      HP: '116'
      Attack: '55'
      Defense: '85'
      Sp. Atk: '107'
      Sp. Def: nan
      Speed: '29'
      Generation: 5
      Legendary: false
    - index: 9
      Name: Wailmer
      Type 1: Water
      Type 2: null
      Total: 400
      HP: '130'
      Attack: '70'
      Defense: '35'
      Sp. Atk: nan
      Sp. Def: '35'
      Speed: '60'
      Generation: 3
      Legendary: false
    params_part1_ans1_value: '60.00'
    params_part1_ans1_feedback: Try again.
    params_part1_ans2_value: nan
    params_part1_ans2_feedback: Great job!
    params_part1_ans3_value: '65.00'
    params_part1_ans3_feedback: Close, but not quite! Try again.
    params_part1_ans4_value: '75.00'
    params_part1_ans4_feedback: Close, but not quite! Try again.
    params_part1_ans5_value: '62.50'
    params_part1_ans5_feedback: Close, but not quite! Try again.
    params_part1_ans6_value: '68.00'
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