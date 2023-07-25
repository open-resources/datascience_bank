---
title: Groupby 2
topic: Data Analysis
author: Gavin Kendal-Freedman
source: original
template_version: 1.0
attribution: standard
partialCredit: true
singleVariant: false
showCorrectAnswer: false
gradingMethod: External
externalGradingOptions:
  enabled: true
  image: prairielearn/grader-python
  entrypoint: /python_autograder/run.sh
  timeout: 60
outcomes:
- 7.3.2.4
- 6.4.4.0
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
- autograded
assets:
- description.png
- penguins.png
autogradeTestFiles:
- ans.py
- setup_code.py
- starter_code.py
- test.py
part1:
  type: string-input
  gradingMethod: Internal
  pl-customizations:
    answers-name: grouped_df
    label: 'grouped_df = '
    display: block
    remove-spaces: true
    placeholder: '...'
myst:
  substitutions:
    params_vars_title: Groupby 2
    params_vars_func: min
    params_vars_left: island
    params_vars_right: species
    params_expected__type: dataframe_v2
    params_expected__value_schema_fields:
    - name: index
      type: integer
    - name: island
      type: string
    - name: species
      type: string
    - name: bill_length_mm
      type: number
    - name: bill_depth_mm
      type: number
    - name: flipper_length_mm
      type: number
    - name: body_mass_g
      type: number
    params_expected__value_schema_primaryKey:
    - index
    params_expected__value_schema_pandas_version: 1.4.0
    params_expected__value_data:
    - index: 0
      island: Biscoe
      species: Adelie
      bill_length_mm: 34.5
      bill_depth_mm: 16.0
      flipper_length_mm: 172.0
      body_mass_g: 2850.0
    - index: 1
      island: Biscoe
      species: Gentoo
      bill_length_mm: 40.9
      bill_depth_mm: 13.1
      flipper_length_mm: 203.0
      body_mass_g: 3950.0
    - index: 2
      island: Dream
      species: Adelie
      bill_length_mm: 32.1
      bill_depth_mm: 15.5
      flipper_length_mm: 178.0
      body_mass_g: 2900.0
    - index: 3
      island: Dream
      species: Chinstrap
      bill_length_mm: 40.9
      bill_depth_mm: 16.4
      flipper_length_mm: 178.0
      body_mass_g: 2700.0
    - index: 4
      island: Torgersen
      species: Adelie
      bill_length_mm: 33.5
      bill_depth_mm: 15.9
      flipper_length_mm: 176.0
      body_mass_g: 2900.0
    params_pengiuns__type: dataframe_v2
    params_pengiuns__value_schema_fields:
    - name: index
      type: integer
    - name: species
      type: string
    - name: island
      type: string
    - name: bill_length_mm
      type: number
    - name: bill_depth_mm
      type: number
    - name: flipper_length_mm
      type: number
    - name: body_mass_g
      type: number
    - name: sex
      type: string
    params_pengiuns__value_schema_primaryKey:
    - index
    params_pengiuns__value_schema_pandas_version: 1.4.0
    params_pengiuns__value_data:
    - index: 0
      species: Adelie
      island: Torgersen
      bill_length_mm: 39.1
      bill_depth_mm: 18.7
      flipper_length_mm: 181.0
      body_mass_g: 3750.0
      sex: MALE
    - index: 1
      species: Adelie
      island: Torgersen
      bill_length_mm: 39.5
      bill_depth_mm: 17.4
      flipper_length_mm: 186.0
      body_mass_g: 3800.0
      sex: FEMALE
    - index: 2
      species: Adelie
      island: Torgersen
      bill_length_mm: 40.3
      bill_depth_mm: 18.0
      flipper_length_mm: 195.0
      body_mass_g: 3250.0
      sex: FEMALE
    - index: 3
      species: Adelie
      island: Torgersen
      bill_length_mm: null
      bill_depth_mm: null
      flipper_length_mm: null
      body_mass_g: null
      sex: null
    - index: 4
      species: Adelie
      island: Torgersen
      bill_length_mm: 36.7
      bill_depth_mm: 19.3
      flipper_length_mm: 193.0
      body_mass_g: 3450.0
      sex: FEMALE
    - index: 5
      species: Adelie
      island: Torgersen
      bill_length_mm: 39.3
      bill_depth_mm: 20.6
      flipper_length_mm: 190.0
      body_mass_g: 3650.0
      sex: MALE
    - index: 6
      species: Adelie
      island: Torgersen
      bill_length_mm: 38.9
      bill_depth_mm: 17.8
      flipper_length_mm: 181.0
      body_mass_g: 3625.0
      sex: FEMALE
    - index: 7
      species: Adelie
      island: Torgersen
      bill_length_mm: 39.2
      bill_depth_mm: 19.6
      flipper_length_mm: 195.0
      body_mass_g: 4675.0
      sex: MALE
    - index: 8
      species: Adelie
      island: Torgersen
      bill_length_mm: 34.1
      bill_depth_mm: 18.1
      flipper_length_mm: 193.0
      body_mass_g: 3475.0
      sex: null
    - index: 9
      species: Adelie
      island: Torgersen
      bill_length_mm: 42.0
      bill_depth_mm: 20.2
      flipper_length_mm: 190.0
      body_mass_g: 4250.0
      sex: null
    - index: 10
      species: Adelie
      island: Torgersen
      bill_length_mm: 37.8
      bill_depth_mm: 17.1
      flipper_length_mm: 186.0
      body_mass_g: 3300.0
      sex: null
    - index: 11
      species: Adelie
      island: Torgersen
      bill_length_mm: 37.8
      bill_depth_mm: 17.3
      flipper_length_mm: 180.0
      body_mass_g: 3700.0
      sex: null
    - index: 12
      species: Adelie
      island: Torgersen
      bill_length_mm: 41.1
      bill_depth_mm: 17.6
      flipper_length_mm: 182.0
      body_mass_g: 3200.0
      sex: FEMALE
    - index: 13
      species: Adelie
      island: Torgersen
      bill_length_mm: 38.6
      bill_depth_mm: 21.2
      flipper_length_mm: 191.0
      body_mass_g: 3800.0
      sex: MALE
    - index: 14
      species: Adelie
      island: Torgersen
      bill_length_mm: 34.6
      bill_depth_mm: 21.1
      flipper_length_mm: 198.0
      body_mass_g: 4400.0
      sex: MALE
    - index: 15
      species: Adelie
      island: Torgersen
      bill_length_mm: 36.6
      bill_depth_mm: 17.8
      flipper_length_mm: 185.0
      body_mass_g: 3700.0
      sex: FEMALE
    - index: 16
      species: Adelie
      island: Torgersen
      bill_length_mm: 38.7
      bill_depth_mm: 19.0
      flipper_length_mm: 195.0
      body_mass_g: 3450.0
      sex: FEMALE
    - index: 17
      species: Adelie
      island: Torgersen
      bill_length_mm: 42.5
      bill_depth_mm: 20.7
      flipper_length_mm: 197.0
      body_mass_g: 4500.0
      sex: MALE
    - index: 18
      species: Adelie
      island: Torgersen
      bill_length_mm: 34.4
      bill_depth_mm: 18.4
      flipper_length_mm: 184.0
      body_mass_g: 3325.0
      sex: FEMALE
    - index: 19
      species: Adelie
      island: Torgersen
      bill_length_mm: 46.0
      bill_depth_mm: 21.5
      flipper_length_mm: 194.0
      body_mass_g: 4200.0
      sex: MALE
    - index: 20
      species: Adelie
      island: Biscoe
      bill_length_mm: 37.8
      bill_depth_mm: 18.3
      flipper_length_mm: 174.0
      body_mass_g: 3400.0
      sex: FEMALE
    - index: 21
      species: Adelie
      island: Biscoe
      bill_length_mm: 37.7
      bill_depth_mm: 18.7
      flipper_length_mm: 180.0
      body_mass_g: 3600.0
      sex: MALE
    - index: 22
      species: Adelie
      island: Biscoe
      bill_length_mm: 35.9
      bill_depth_mm: 19.2
      flipper_length_mm: 189.0
      body_mass_g: 3800.0
      sex: FEMALE
    - index: 23
      species: Adelie
      island: Biscoe
      bill_length_mm: 38.2
      bill_depth_mm: 18.1
      flipper_length_mm: 185.0
      body_mass_g: 3950.0
      sex: MALE
    - index: 24
      species: Adelie
      island: Biscoe
      bill_length_mm: 38.8
      bill_depth_mm: 17.2
      flipper_length_mm: 180.0
      body_mass_g: 3800.0
      sex: MALE
    - index: 25
      species: Adelie
      island: Biscoe
      bill_length_mm: 35.3
      bill_depth_mm: 18.9
      flipper_length_mm: 187.0
      body_mass_g: 3800.0
      sex: FEMALE
    - index: 26
      species: Adelie
      island: Biscoe
      bill_length_mm: 40.6
      bill_depth_mm: 18.6
      flipper_length_mm: 183.0
      body_mass_g: 3550.0
      sex: MALE
    - index: 27
      species: Adelie
      island: Biscoe
      bill_length_mm: 40.5
      bill_depth_mm: 17.9
      flipper_length_mm: 187.0
      body_mass_g: 3200.0
      sex: FEMALE
    - index: 28
      species: Adelie
      island: Biscoe
      bill_length_mm: 37.9
      bill_depth_mm: 18.6
      flipper_length_mm: 172.0
      body_mass_g: 3150.0
      sex: FEMALE
    - index: 29
      species: Adelie
      island: Biscoe
      bill_length_mm: 40.5
      bill_depth_mm: 18.9
      flipper_length_mm: 180.0
      body_mass_g: 3950.0
      sex: MALE
    - index: 30
      species: Adelie
      island: Dream
      bill_length_mm: 39.5
      bill_depth_mm: 16.7
      flipper_length_mm: 178.0
      body_mass_g: 3250.0
      sex: FEMALE
    - index: 31
      species: Adelie
      island: Dream
      bill_length_mm: 37.2
      bill_depth_mm: 18.1
      flipper_length_mm: 178.0
      body_mass_g: 3900.0
      sex: MALE
    - index: 32
      species: Adelie
      island: Dream
      bill_length_mm: 39.5
      bill_depth_mm: 17.8
      flipper_length_mm: 188.0
      body_mass_g: 3300.0
      sex: FEMALE
    - index: 33
      species: Adelie
      island: Dream
      bill_length_mm: 40.9
      bill_depth_mm: 18.9
      flipper_length_mm: 184.0
      body_mass_g: 3900.0
      sex: MALE
    - index: 34
      species: Adelie
      island: Dream
      bill_length_mm: 36.4
      bill_depth_mm: 17.0
      flipper_length_mm: 195.0
      body_mass_g: 3325.0
      sex: FEMALE
    - index: 35
      species: Adelie
      island: Dream
      bill_length_mm: 39.2
      bill_depth_mm: 21.1
      flipper_length_mm: 196.0
      body_mass_g: 4150.0
      sex: MALE
    - index: 36
      species: Adelie
      island: Dream
      bill_length_mm: 38.8
      bill_depth_mm: 20.0
      flipper_length_mm: 190.0
      body_mass_g: 3950.0
      sex: MALE
    - index: 37
      species: Adelie
      island: Dream
      bill_length_mm: 42.2
      bill_depth_mm: 18.5
      flipper_length_mm: 180.0
      body_mass_g: 3550.0
      sex: FEMALE
    - index: 38
      species: Adelie
      island: Dream
      bill_length_mm: 37.6
      bill_depth_mm: 19.3
      flipper_length_mm: 181.0
      body_mass_g: 3300.0
      sex: FEMALE
    - index: 39
      species: Adelie
      island: Dream
      bill_length_mm: 39.8
      bill_depth_mm: 19.1
      flipper_length_mm: 184.0
      body_mass_g: 4650.0
      sex: MALE
    - index: 40
      species: Adelie
      island: Dream
      bill_length_mm: 36.5
      bill_depth_mm: 18.0
      flipper_length_mm: 182.0
      body_mass_g: 3150.0
      sex: FEMALE
    - index: 41
      species: Adelie
      island: Dream
      bill_length_mm: 40.8
      bill_depth_mm: 18.4
      flipper_length_mm: 195.0
      body_mass_g: 3900.0
      sex: MALE
    - index: 42
      species: Adelie
      island: Dream
      bill_length_mm: 36.0
      bill_depth_mm: 18.5
      flipper_length_mm: 186.0
      body_mass_g: 3100.0
      sex: FEMALE
    - index: 43
      species: Adelie
      island: Dream
      bill_length_mm: 44.1
      bill_depth_mm: 19.7
      flipper_length_mm: 196.0
      body_mass_g: 4400.0
      sex: MALE
    - index: 44
      species: Adelie
      island: Dream
      bill_length_mm: 37.0
      bill_depth_mm: 16.9
      flipper_length_mm: 185.0
      body_mass_g: 3000.0
      sex: FEMALE
    - index: 45
      species: Adelie
      island: Dream
      bill_length_mm: 39.6
      bill_depth_mm: 18.8
      flipper_length_mm: 190.0
      body_mass_g: 4600.0
      sex: MALE
    - index: 46
      species: Adelie
      island: Dream
      bill_length_mm: 41.1
      bill_depth_mm: 19.0
      flipper_length_mm: 182.0
      body_mass_g: 3425.0
      sex: MALE
    - index: 47
      species: Adelie
      island: Dream
      bill_length_mm: 37.5
      bill_depth_mm: 18.9
      flipper_length_mm: 179.0
      body_mass_g: 2975.0
      sex: null
    - index: 48
      species: Adelie
      island: Dream
      bill_length_mm: 36.0
      bill_depth_mm: 17.9
      flipper_length_mm: 190.0
      body_mass_g: 3450.0
      sex: FEMALE
    - index: 49
      species: Adelie
      island: Dream
      bill_length_mm: 42.3
      bill_depth_mm: 21.2
      flipper_length_mm: 191.0
      body_mass_g: 4150.0
      sex: MALE
    - index: 50
      species: Adelie
      island: Biscoe
      bill_length_mm: 39.6
      bill_depth_mm: 17.7
      flipper_length_mm: 186.0
      body_mass_g: 3500.0
      sex: FEMALE
    - index: 51
      species: Adelie
      island: Biscoe
      bill_length_mm: 40.1
      bill_depth_mm: 18.9
      flipper_length_mm: 188.0
      body_mass_g: 4300.0
      sex: MALE
    - index: 52
      species: Adelie
      island: Biscoe
      bill_length_mm: 35.0
      bill_depth_mm: 17.9
      flipper_length_mm: 190.0
      body_mass_g: 3450.0
      sex: FEMALE
    - index: 53
      species: Adelie
      island: Biscoe
      bill_length_mm: 42.0
      bill_depth_mm: 19.5
      flipper_length_mm: 200.0
      body_mass_g: 4050.0
      sex: MALE
    - index: 54
      species: Adelie
      island: Biscoe
      bill_length_mm: 34.5
      bill_depth_mm: 18.1
      flipper_length_mm: 187.0
      body_mass_g: 2900.0
      sex: FEMALE
    - index: 55
      species: Adelie
      island: Biscoe
      bill_length_mm: 41.4
      bill_depth_mm: 18.6
      flipper_length_mm: 191.0
      body_mass_g: 3700.0
      sex: MALE
    - index: 56
      species: Adelie
      island: Biscoe
      bill_length_mm: 39.0
      bill_depth_mm: 17.5
      flipper_length_mm: 186.0
      body_mass_g: 3550.0
      sex: FEMALE
    - index: 57
      species: Adelie
      island: Biscoe
      bill_length_mm: 40.6
      bill_depth_mm: 18.8
      flipper_length_mm: 193.0
      body_mass_g: 3800.0
      sex: MALE
    - index: 58
      species: Adelie
      island: Biscoe
      bill_length_mm: 36.5
      bill_depth_mm: 16.6
      flipper_length_mm: 181.0
      body_mass_g: 2850.0
      sex: FEMALE
    - index: 59
      species: Adelie
      island: Biscoe
      bill_length_mm: 37.6
      bill_depth_mm: 19.1
      flipper_length_mm: 194.0
      body_mass_g: 3750.0
      sex: MALE
    - index: 60
      species: Adelie
      island: Biscoe
      bill_length_mm: 35.7
      bill_depth_mm: 16.9
      flipper_length_mm: 185.0
      body_mass_g: 3150.0
      sex: FEMALE
    - index: 61
      species: Adelie
      island: Biscoe
      bill_length_mm: 41.3
      bill_depth_mm: 21.1
      flipper_length_mm: 195.0
      body_mass_g: 4400.0
      sex: MALE
    - index: 62
      species: Adelie
      island: Biscoe
      bill_length_mm: 37.6
      bill_depth_mm: 17.0
      flipper_length_mm: 185.0
      body_mass_g: 3600.0
      sex: FEMALE
    - index: 63
      species: Adelie
      island: Biscoe
      bill_length_mm: 41.1
      bill_depth_mm: 18.2
      flipper_length_mm: 192.0
      body_mass_g: 4050.0
      sex: MALE
    - index: 64
      species: Adelie
      island: Biscoe
      bill_length_mm: 36.4
      bill_depth_mm: 17.1
      flipper_length_mm: 184.0
      body_mass_g: 2850.0
      sex: FEMALE
    - index: 65
      species: Adelie
      island: Biscoe
      bill_length_mm: 41.6
      bill_depth_mm: 18.0
      flipper_length_mm: 192.0
      body_mass_g: 3950.0
      sex: MALE
    - index: 66
      species: Adelie
      island: Biscoe
      bill_length_mm: 35.5
      bill_depth_mm: 16.2
      flipper_length_mm: 195.0
      body_mass_g: 3350.0
      sex: FEMALE
    - index: 67
      species: Adelie
      island: Biscoe
      bill_length_mm: 41.1
      bill_depth_mm: 19.1
      flipper_length_mm: 188.0
      body_mass_g: 4100.0
      sex: MALE
    - index: 68
      species: Adelie
      island: Torgersen
      bill_length_mm: 35.9
      bill_depth_mm: 16.6
      flipper_length_mm: 190.0
      body_mass_g: 3050.0
      sex: FEMALE
    - index: 69
      species: Adelie
      island: Torgersen
      bill_length_mm: 41.8
      bill_depth_mm: 19.4
      flipper_length_mm: 198.0
      body_mass_g: 4450.0
      sex: MALE
    - index: 70
      species: Adelie
      island: Torgersen
      bill_length_mm: 33.5
      bill_depth_mm: 19.0
      flipper_length_mm: 190.0
      body_mass_g: 3600.0
      sex: FEMALE
    - index: 71
      species: Adelie
      island: Torgersen
      bill_length_mm: 39.7
      bill_depth_mm: 18.4
      flipper_length_mm: 190.0
      body_mass_g: 3900.0
      sex: MALE
    - index: 72
      species: Adelie
      island: Torgersen
      bill_length_mm: 39.6
      bill_depth_mm: 17.2
      flipper_length_mm: 196.0
      body_mass_g: 3550.0
      sex: FEMALE
    - index: 73
      species: Adelie
      island: Torgersen
      bill_length_mm: 45.8
      bill_depth_mm: 18.9
      flipper_length_mm: 197.0
      body_mass_g: 4150.0
      sex: MALE
    - index: 74
      species: Adelie
      island: Torgersen
      bill_length_mm: 35.5
      bill_depth_mm: 17.5
      flipper_length_mm: 190.0
      body_mass_g: 3700.0
      sex: FEMALE
    - index: 75
      species: Adelie
      island: Torgersen
      bill_length_mm: 42.8
      bill_depth_mm: 18.5
      flipper_length_mm: 195.0
      body_mass_g: 4250.0
      sex: MALE
    - index: 76
      species: Adelie
      island: Torgersen
      bill_length_mm: 40.9
      bill_depth_mm: 16.8
      flipper_length_mm: 191.0
      body_mass_g: 3700.0
      sex: FEMALE
    - index: 77
      species: Adelie
      island: Torgersen
      bill_length_mm: 37.2
      bill_depth_mm: 19.4
      flipper_length_mm: 184.0
      body_mass_g: 3900.0
      sex: MALE
    - index: 78
      species: Adelie
      island: Torgersen
      bill_length_mm: 36.2
      bill_depth_mm: 16.1
      flipper_length_mm: 187.0
      body_mass_g: 3550.0
      sex: FEMALE
    - index: 79
      species: Adelie
      island: Torgersen
      bill_length_mm: 42.1
      bill_depth_mm: 19.1
      flipper_length_mm: 195.0
      body_mass_g: 4000.0
      sex: MALE
    - index: 80
      species: Adelie
      island: Torgersen
      bill_length_mm: 34.6
      bill_depth_mm: 17.2
      flipper_length_mm: 189.0
      body_mass_g: 3200.0
      sex: FEMALE
    - index: 81
      species: Adelie
      island: Torgersen
      bill_length_mm: 42.9
      bill_depth_mm: 17.6
      flipper_length_mm: 196.0
      body_mass_g: 4700.0
      sex: MALE
    - index: 82
      species: Adelie
      island: Torgersen
      bill_length_mm: 36.7
      bill_depth_mm: 18.8
      flipper_length_mm: 187.0
      body_mass_g: 3800.0
      sex: FEMALE
    - index: 83
      species: Adelie
      island: Torgersen
      bill_length_mm: 35.1
      bill_depth_mm: 19.4
      flipper_length_mm: 193.0
      body_mass_g: 4200.0
      sex: MALE
    - index: 84
      species: Adelie
      island: Dream
      bill_length_mm: 37.3
      bill_depth_mm: 17.8
      flipper_length_mm: 191.0
      body_mass_g: 3350.0
      sex: FEMALE
    - index: 85
      species: Adelie
      island: Dream
      bill_length_mm: 41.3
      bill_depth_mm: 20.3
      flipper_length_mm: 194.0
      body_mass_g: 3550.0
      sex: MALE
    - index: 86
      species: Adelie
      island: Dream
      bill_length_mm: 36.3
      bill_depth_mm: 19.5
      flipper_length_mm: 190.0
      body_mass_g: 3800.0
      sex: MALE
    - index: 87
      species: Adelie
      island: Dream
      bill_length_mm: 36.9
      bill_depth_mm: 18.6
      flipper_length_mm: 189.0
      body_mass_g: 3500.0
      sex: FEMALE
    - index: 88
      species: Adelie
      island: Dream
      bill_length_mm: 38.3
      bill_depth_mm: 19.2
      flipper_length_mm: 189.0
      body_mass_g: 3950.0
      sex: MALE
    - index: 89
      species: Adelie
      island: Dream
      bill_length_mm: 38.9
      bill_depth_mm: 18.8
      flipper_length_mm: 190.0
      body_mass_g: 3600.0
      sex: FEMALE
    - index: 90
      species: Adelie
      island: Dream
      bill_length_mm: 35.7
      bill_depth_mm: 18.0
      flipper_length_mm: 202.0
      body_mass_g: 3550.0
      sex: FEMALE
    - index: 91
      species: Adelie
      island: Dream
      bill_length_mm: 41.1
      bill_depth_mm: 18.1
      flipper_length_mm: 205.0
      body_mass_g: 4300.0
      sex: MALE
    - index: 92
      species: Adelie
      island: Dream
      bill_length_mm: 34.0
      bill_depth_mm: 17.1
      flipper_length_mm: 185.0
      body_mass_g: 3400.0
      sex: FEMALE
    - index: 93
      species: Adelie
      island: Dream
      bill_length_mm: 39.6
      bill_depth_mm: 18.1
      flipper_length_mm: 186.0
      body_mass_g: 4450.0
      sex: MALE
    - index: 94
      species: Adelie
      island: Dream
      bill_length_mm: 36.2
      bill_depth_mm: 17.3
      flipper_length_mm: 187.0
      body_mass_g: 3300.0
      sex: FEMALE
    - index: 95
      species: Adelie
      island: Dream
      bill_length_mm: 40.8
      bill_depth_mm: 18.9
      flipper_length_mm: 208.0
      body_mass_g: 4300.0
      sex: MALE
    - index: 96
      species: Adelie
      island: Dream
      bill_length_mm: 38.1
      bill_depth_mm: 18.6
      flipper_length_mm: 190.0
      body_mass_g: 3700.0
      sex: FEMALE
    - index: 97
      species: Adelie
      island: Dream
      bill_length_mm: 40.3
      bill_depth_mm: 18.5
      flipper_length_mm: 196.0
      body_mass_g: 4350.0
      sex: MALE
    - index: 98
      species: Adelie
      island: Dream
      bill_length_mm: 33.1
      bill_depth_mm: 16.1
      flipper_length_mm: 178.0
      body_mass_g: 2900.0
      sex: FEMALE
    - index: 99
      species: Adelie
      island: Dream
      bill_length_mm: 43.2
      bill_depth_mm: 18.5
      flipper_length_mm: 192.0
      body_mass_g: 4100.0
      sex: MALE
    - index: 100
      species: Adelie
      island: Biscoe
      bill_length_mm: 35.0
      bill_depth_mm: 17.9
      flipper_length_mm: 192.0
      body_mass_g: 3725.0
      sex: FEMALE
    - index: 101
      species: Adelie
      island: Biscoe
      bill_length_mm: 41.0
      bill_depth_mm: 20.0
      flipper_length_mm: 203.0
      body_mass_g: 4725.0
      sex: MALE
    - index: 102
      species: Adelie
      island: Biscoe
      bill_length_mm: 37.7
      bill_depth_mm: 16.0
      flipper_length_mm: 183.0
      body_mass_g: 3075.0
      sex: FEMALE
    - index: 103
      species: Adelie
      island: Biscoe
      bill_length_mm: 37.8
      bill_depth_mm: 20.0
      flipper_length_mm: 190.0
      body_mass_g: 4250.0
      sex: MALE
    - index: 104
      species: Adelie
      island: Biscoe
      bill_length_mm: 37.9
      bill_depth_mm: 18.6
      flipper_length_mm: 193.0
      body_mass_g: 2925.0
      sex: FEMALE
    - index: 105
      species: Adelie
      island: Biscoe
      bill_length_mm: 39.7
      bill_depth_mm: 18.9
      flipper_length_mm: 184.0
      body_mass_g: 3550.0
      sex: MALE
    - index: 106
      species: Adelie
      island: Biscoe
      bill_length_mm: 38.6
      bill_depth_mm: 17.2
      flipper_length_mm: 199.0
      body_mass_g: 3750.0
      sex: FEMALE
    - index: 107
      species: Adelie
      island: Biscoe
      bill_length_mm: 38.2
      bill_depth_mm: 20.0
      flipper_length_mm: 190.0
      body_mass_g: 3900.0
      sex: MALE
    - index: 108
      species: Adelie
      island: Biscoe
      bill_length_mm: 38.1
      bill_depth_mm: 17.0
      flipper_length_mm: 181.0
      body_mass_g: 3175.0
      sex: FEMALE
    - index: 109
      species: Adelie
      island: Biscoe
      bill_length_mm: 43.2
      bill_depth_mm: 19.0
      flipper_length_mm: 197.0
      body_mass_g: 4775.0
      sex: MALE
    - index: 110
      species: Adelie
      island: Biscoe
      bill_length_mm: 38.1
      bill_depth_mm: 16.5
      flipper_length_mm: 198.0
      body_mass_g: 3825.0
      sex: FEMALE
    - index: 111
      species: Adelie
      island: Biscoe
      bill_length_mm: 45.6
      bill_depth_mm: 20.3
      flipper_length_mm: 191.0
      body_mass_g: 4600.0
      sex: MALE
    - index: 112
      species: Adelie
      island: Biscoe
      bill_length_mm: 39.7
      bill_depth_mm: 17.7
      flipper_length_mm: 193.0
      body_mass_g: 3200.0
      sex: FEMALE
    - index: 113
      species: Adelie
      island: Biscoe
      bill_length_mm: 42.2
      bill_depth_mm: 19.5
      flipper_length_mm: 197.0
      body_mass_g: 4275.0
      sex: MALE
    - index: 114
      species: Adelie
      island: Biscoe
      bill_length_mm: 39.6
      bill_depth_mm: 20.7
      flipper_length_mm: 191.0
      body_mass_g: 3900.0
      sex: FEMALE
    - index: 115
      species: Adelie
      island: Biscoe
      bill_length_mm: 42.7
      bill_depth_mm: 18.3
      flipper_length_mm: 196.0
      body_mass_g: 4075.0
      sex: MALE
    - index: 116
      species: Adelie
      island: Torgersen
      bill_length_mm: 38.6
      bill_depth_mm: 17.0
      flipper_length_mm: 188.0
      body_mass_g: 2900.0
      sex: FEMALE
    - index: 117
      species: Adelie
      island: Torgersen
      bill_length_mm: 37.3
      bill_depth_mm: 20.5
      flipper_length_mm: 199.0
      body_mass_g: 3775.0
      sex: MALE
    - index: 118
      species: Adelie
      island: Torgersen
      bill_length_mm: 35.7
      bill_depth_mm: 17.0
      flipper_length_mm: 189.0
      body_mass_g: 3350.0
      sex: FEMALE
    - index: 119
      species: Adelie
      island: Torgersen
      bill_length_mm: 41.1
      bill_depth_mm: 18.6
      flipper_length_mm: 189.0
      body_mass_g: 3325.0
      sex: MALE
    - index: 120
      species: Adelie
      island: Torgersen
      bill_length_mm: 36.2
      bill_depth_mm: 17.2
      flipper_length_mm: 187.0
      body_mass_g: 3150.0
      sex: FEMALE
    - index: 121
      species: Adelie
      island: Torgersen
      bill_length_mm: 37.7
      bill_depth_mm: 19.8
      flipper_length_mm: 198.0
      body_mass_g: 3500.0
      sex: MALE
    - index: 122
      species: Adelie
      island: Torgersen
      bill_length_mm: 40.2
      bill_depth_mm: 17.0
      flipper_length_mm: 176.0
      body_mass_g: 3450.0
      sex: FEMALE
    - index: 123
      species: Adelie
      island: Torgersen
      bill_length_mm: 41.4
      bill_depth_mm: 18.5
      flipper_length_mm: 202.0
      body_mass_g: 3875.0
      sex: MALE
    - index: 124
      species: Adelie
      island: Torgersen
      bill_length_mm: 35.2
      bill_depth_mm: 15.9
      flipper_length_mm: 186.0
      body_mass_g: 3050.0
      sex: FEMALE
    - index: 125
      species: Adelie
      island: Torgersen
      bill_length_mm: 40.6
      bill_depth_mm: 19.0
      flipper_length_mm: 199.0
      body_mass_g: 4000.0
      sex: MALE
    - index: 126
      species: Adelie
      island: Torgersen
      bill_length_mm: 38.8
      bill_depth_mm: 17.6
      flipper_length_mm: 191.0
      body_mass_g: 3275.0
      sex: FEMALE
    - index: 127
      species: Adelie
      island: Torgersen
      bill_length_mm: 41.5
      bill_depth_mm: 18.3
      flipper_length_mm: 195.0
      body_mass_g: 4300.0
      sex: MALE
    - index: 128
      species: Adelie
      island: Torgersen
      bill_length_mm: 39.0
      bill_depth_mm: 17.1
      flipper_length_mm: 191.0
      body_mass_g: 3050.0
      sex: FEMALE
    - index: 129
      species: Adelie
      island: Torgersen
      bill_length_mm: 44.1
      bill_depth_mm: 18.0
      flipper_length_mm: 210.0
      body_mass_g: 4000.0
      sex: MALE
    - index: 130
      species: Adelie
      island: Torgersen
      bill_length_mm: 38.5
      bill_depth_mm: 17.9
      flipper_length_mm: 190.0
      body_mass_g: 3325.0
      sex: FEMALE
    - index: 131
      species: Adelie
      island: Torgersen
      bill_length_mm: 43.1
      bill_depth_mm: 19.2
      flipper_length_mm: 197.0
      body_mass_g: 3500.0
      sex: MALE
    - index: 132
      species: Adelie
      island: Dream
      bill_length_mm: 36.8
      bill_depth_mm: 18.5
      flipper_length_mm: 193.0
      body_mass_g: 3500.0
      sex: FEMALE
    - index: 133
      species: Adelie
      island: Dream
      bill_length_mm: 37.5
      bill_depth_mm: 18.5
      flipper_length_mm: 199.0
      body_mass_g: 4475.0
      sex: MALE
    - index: 134
      species: Adelie
      island: Dream
      bill_length_mm: 38.1
      bill_depth_mm: 17.6
      flipper_length_mm: 187.0
      body_mass_g: 3425.0
      sex: FEMALE
    - index: 135
      species: Adelie
      island: Dream
      bill_length_mm: 41.1
      bill_depth_mm: 17.5
      flipper_length_mm: 190.0
      body_mass_g: 3900.0
      sex: MALE
    - index: 136
      species: Adelie
      island: Dream
      bill_length_mm: 35.6
      bill_depth_mm: 17.5
      flipper_length_mm: 191.0
      body_mass_g: 3175.0
      sex: FEMALE
    - index: 137
      species: Adelie
      island: Dream
      bill_length_mm: 40.2
      bill_depth_mm: 20.1
      flipper_length_mm: 200.0
      body_mass_g: 3975.0
      sex: MALE
    - index: 138
      species: Adelie
      island: Dream
      bill_length_mm: 37.0
      bill_depth_mm: 16.5
      flipper_length_mm: 185.0
      body_mass_g: 3400.0
      sex: FEMALE
    - index: 139
      species: Adelie
      island: Dream
      bill_length_mm: 39.7
      bill_depth_mm: 17.9
      flipper_length_mm: 193.0
      body_mass_g: 4250.0
      sex: MALE
    - index: 140
      species: Adelie
      island: Dream
      bill_length_mm: 40.2
      bill_depth_mm: 17.1
      flipper_length_mm: 193.0
      body_mass_g: 3400.0
      sex: FEMALE
    - index: 141
      species: Adelie
      island: Dream
      bill_length_mm: 40.6
      bill_depth_mm: 17.2
      flipper_length_mm: 187.0
      body_mass_g: 3475.0
      sex: MALE
    - index: 142
      species: Adelie
      island: Dream
      bill_length_mm: 32.1
      bill_depth_mm: 15.5
      flipper_length_mm: 188.0
      body_mass_g: 3050.0
      sex: FEMALE
    - index: 143
      species: Adelie
      island: Dream
      bill_length_mm: 40.7
      bill_depth_mm: 17.0
      flipper_length_mm: 190.0
      body_mass_g: 3725.0
      sex: MALE
    - index: 144
      species: Adelie
      island: Dream
      bill_length_mm: 37.3
      bill_depth_mm: 16.8
      flipper_length_mm: 192.0
      body_mass_g: 3000.0
      sex: FEMALE
    - index: 145
      species: Adelie
      island: Dream
      bill_length_mm: 39.0
      bill_depth_mm: 18.7
      flipper_length_mm: 185.0
      body_mass_g: 3650.0
      sex: MALE
    - index: 146
      species: Adelie
      island: Dream
      bill_length_mm: 39.2
      bill_depth_mm: 18.6
      flipper_length_mm: 190.0
      body_mass_g: 4250.0
      sex: MALE
    - index: 147
      species: Adelie
      island: Dream
      bill_length_mm: 36.6
      bill_depth_mm: 18.4
      flipper_length_mm: 184.0
      body_mass_g: 3475.0
      sex: FEMALE
    - index: 148
      species: Adelie
      island: Dream
      bill_length_mm: 36.0
      bill_depth_mm: 17.8
      flipper_length_mm: 195.0
      body_mass_g: 3450.0
      sex: FEMALE
    - index: 149
      species: Adelie
      island: Dream
      bill_length_mm: 37.8
      bill_depth_mm: 18.1
      flipper_length_mm: 193.0
      body_mass_g: 3750.0
      sex: MALE
    - index: 150
      species: Adelie
      island: Dream
      bill_length_mm: 36.0
      bill_depth_mm: 17.1
      flipper_length_mm: 187.0
      body_mass_g: 3700.0
      sex: FEMALE
    - index: 151
      species: Adelie
      island: Dream
      bill_length_mm: 41.5
      bill_depth_mm: 18.5
      flipper_length_mm: 201.0
      body_mass_g: 4000.0
      sex: MALE
    - index: 152
      species: Chinstrap
      island: Dream
      bill_length_mm: 46.5
      bill_depth_mm: 17.9
      flipper_length_mm: 192.0
      body_mass_g: 3500.0
      sex: FEMALE
    - index: 153
      species: Chinstrap
      island: Dream
      bill_length_mm: 50.0
      bill_depth_mm: 19.5
      flipper_length_mm: 196.0
      body_mass_g: 3900.0
      sex: MALE
    - index: 154
      species: Chinstrap
      island: Dream
      bill_length_mm: 51.3
      bill_depth_mm: 19.2
      flipper_length_mm: 193.0
      body_mass_g: 3650.0
      sex: MALE
    - index: 155
      species: Chinstrap
      island: Dream
      bill_length_mm: 45.4
      bill_depth_mm: 18.7
      flipper_length_mm: 188.0
      body_mass_g: 3525.0
      sex: FEMALE
    - index: 156
      species: Chinstrap
      island: Dream
      bill_length_mm: 52.7
      bill_depth_mm: 19.8
      flipper_length_mm: 197.0
      body_mass_g: 3725.0
      sex: MALE
    - index: 157
      species: Chinstrap
      island: Dream
      bill_length_mm: 45.2
      bill_depth_mm: 17.8
      flipper_length_mm: 198.0
      body_mass_g: 3950.0
      sex: FEMALE
    - index: 158
      species: Chinstrap
      island: Dream
      bill_length_mm: 46.1
      bill_depth_mm: 18.2
      flipper_length_mm: 178.0
      body_mass_g: 3250.0
      sex: FEMALE
    - index: 159
      species: Chinstrap
      island: Dream
      bill_length_mm: 51.3
      bill_depth_mm: 18.2
      flipper_length_mm: 197.0
      body_mass_g: 3750.0
      sex: MALE
    - index: 160
      species: Chinstrap
      island: Dream
      bill_length_mm: 46.0
      bill_depth_mm: 18.9
      flipper_length_mm: 195.0
      body_mass_g: 4150.0
      sex: FEMALE
    - index: 161
      species: Chinstrap
      island: Dream
      bill_length_mm: 51.3
      bill_depth_mm: 19.9
      flipper_length_mm: 198.0
      body_mass_g: 3700.0
      sex: MALE
    - index: 162
      species: Chinstrap
      island: Dream
      bill_length_mm: 46.6
      bill_depth_mm: 17.8
      flipper_length_mm: 193.0
      body_mass_g: 3800.0
      sex: FEMALE
    - index: 163
      species: Chinstrap
      island: Dream
      bill_length_mm: 51.7
      bill_depth_mm: 20.3
      flipper_length_mm: 194.0
      body_mass_g: 3775.0
      sex: MALE
    - index: 164
      species: Chinstrap
      island: Dream
      bill_length_mm: 47.0
      bill_depth_mm: 17.3
      flipper_length_mm: 185.0
      body_mass_g: 3700.0
      sex: FEMALE
    - index: 165
      species: Chinstrap
      island: Dream
      bill_length_mm: 52.0
      bill_depth_mm: 18.1
      flipper_length_mm: 201.0
      body_mass_g: 4050.0
      sex: MALE
    - index: 166
      species: Chinstrap
      island: Dream
      bill_length_mm: 45.9
      bill_depth_mm: 17.1
      flipper_length_mm: 190.0
      body_mass_g: 3575.0
      sex: FEMALE
    - index: 167
      species: Chinstrap
      island: Dream
      bill_length_mm: 50.5
      bill_depth_mm: 19.6
      flipper_length_mm: 201.0
      body_mass_g: 4050.0
      sex: MALE
    - index: 168
      species: Chinstrap
      island: Dream
      bill_length_mm: 50.3
      bill_depth_mm: 20.0
      flipper_length_mm: 197.0
      body_mass_g: 3300.0
      sex: MALE
    - index: 169
      species: Chinstrap
      island: Dream
      bill_length_mm: 58.0
      bill_depth_mm: 17.8
      flipper_length_mm: 181.0
      body_mass_g: 3700.0
      sex: FEMALE
    - index: 170
      species: Chinstrap
      island: Dream
      bill_length_mm: 46.4
      bill_depth_mm: 18.6
      flipper_length_mm: 190.0
      body_mass_g: 3450.0
      sex: FEMALE
    - index: 171
      species: Chinstrap
      island: Dream
      bill_length_mm: 49.2
      bill_depth_mm: 18.2
      flipper_length_mm: 195.0
      body_mass_g: 4400.0
      sex: MALE
    - index: 172
      species: Chinstrap
      island: Dream
      bill_length_mm: 42.4
      bill_depth_mm: 17.3
      flipper_length_mm: 181.0
      body_mass_g: 3600.0
      sex: FEMALE
    - index: 173
      species: Chinstrap
      island: Dream
      bill_length_mm: 48.5
      bill_depth_mm: 17.5
      flipper_length_mm: 191.0
      body_mass_g: 3400.0
      sex: MALE
    - index: 174
      species: Chinstrap
      island: Dream
      bill_length_mm: 43.2
      bill_depth_mm: 16.6
      flipper_length_mm: 187.0
      body_mass_g: 2900.0
      sex: FEMALE
    - index: 175
      species: Chinstrap
      island: Dream
      bill_length_mm: 50.6
      bill_depth_mm: 19.4
      flipper_length_mm: 193.0
      body_mass_g: 3800.0
      sex: MALE
    - index: 176
      species: Chinstrap
      island: Dream
      bill_length_mm: 46.7
      bill_depth_mm: 17.9
      flipper_length_mm: 195.0
      body_mass_g: 3300.0
      sex: FEMALE
    - index: 177
      species: Chinstrap
      island: Dream
      bill_length_mm: 52.0
      bill_depth_mm: 19.0
      flipper_length_mm: 197.0
      body_mass_g: 4150.0
      sex: MALE
    - index: 178
      species: Chinstrap
      island: Dream
      bill_length_mm: 50.5
      bill_depth_mm: 18.4
      flipper_length_mm: 200.0
      body_mass_g: 3400.0
      sex: FEMALE
    - index: 179
      species: Chinstrap
      island: Dream
      bill_length_mm: 49.5
      bill_depth_mm: 19.0
      flipper_length_mm: 200.0
      body_mass_g: 3800.0
      sex: MALE
    - index: 180
      species: Chinstrap
      island: Dream
      bill_length_mm: 46.4
      bill_depth_mm: 17.8
      flipper_length_mm: 191.0
      body_mass_g: 3700.0
      sex: FEMALE
    - index: 181
      species: Chinstrap
      island: Dream
      bill_length_mm: 52.8
      bill_depth_mm: 20.0
      flipper_length_mm: 205.0
      body_mass_g: 4550.0
      sex: MALE
    - index: 182
      species: Chinstrap
      island: Dream
      bill_length_mm: 40.9
      bill_depth_mm: 16.6
      flipper_length_mm: 187.0
      body_mass_g: 3200.0
      sex: FEMALE
    - index: 183
      species: Chinstrap
      island: Dream
      bill_length_mm: 54.2
      bill_depth_mm: 20.8
      flipper_length_mm: 201.0
      body_mass_g: 4300.0
      sex: MALE
    - index: 184
      species: Chinstrap
      island: Dream
      bill_length_mm: 42.5
      bill_depth_mm: 16.7
      flipper_length_mm: 187.0
      body_mass_g: 3350.0
      sex: FEMALE
    - index: 185
      species: Chinstrap
      island: Dream
      bill_length_mm: 51.0
      bill_depth_mm: 18.8
      flipper_length_mm: 203.0
      body_mass_g: 4100.0
      sex: MALE
    - index: 186
      species: Chinstrap
      island: Dream
      bill_length_mm: 49.7
      bill_depth_mm: 18.6
      flipper_length_mm: 195.0
      body_mass_g: 3600.0
      sex: MALE
    - index: 187
      species: Chinstrap
      island: Dream
      bill_length_mm: 47.5
      bill_depth_mm: 16.8
      flipper_length_mm: 199.0
      body_mass_g: 3900.0
      sex: FEMALE
    - index: 188
      species: Chinstrap
      island: Dream
      bill_length_mm: 47.6
      bill_depth_mm: 18.3
      flipper_length_mm: 195.0
      body_mass_g: 3850.0
      sex: FEMALE
    - index: 189
      species: Chinstrap
      island: Dream
      bill_length_mm: 52.0
      bill_depth_mm: 20.7
      flipper_length_mm: 210.0
      body_mass_g: 4800.0
      sex: MALE
    - index: 190
      species: Chinstrap
      island: Dream
      bill_length_mm: 46.9
      bill_depth_mm: 16.6
      flipper_length_mm: 192.0
      body_mass_g: 2700.0
      sex: FEMALE
    - index: 191
      species: Chinstrap
      island: Dream
      bill_length_mm: 53.5
      bill_depth_mm: 19.9
      flipper_length_mm: 205.0
      body_mass_g: 4500.0
      sex: MALE
    - index: 192
      species: Chinstrap
      island: Dream
      bill_length_mm: 49.0
      bill_depth_mm: 19.5
      flipper_length_mm: 210.0
      body_mass_g: 3950.0
      sex: MALE
    - index: 193
      species: Chinstrap
      island: Dream
      bill_length_mm: 46.2
      bill_depth_mm: 17.5
      flipper_length_mm: 187.0
      body_mass_g: 3650.0
      sex: FEMALE
    - index: 194
      species: Chinstrap
      island: Dream
      bill_length_mm: 50.9
      bill_depth_mm: 19.1
      flipper_length_mm: 196.0
      body_mass_g: 3550.0
      sex: MALE
    - index: 195
      species: Chinstrap
      island: Dream
      bill_length_mm: 45.5
      bill_depth_mm: 17.0
      flipper_length_mm: 196.0
      body_mass_g: 3500.0
      sex: FEMALE
    - index: 196
      species: Chinstrap
      island: Dream
      bill_length_mm: 50.9
      bill_depth_mm: 17.9
      flipper_length_mm: 196.0
      body_mass_g: 3675.0
      sex: FEMALE
    - index: 197
      species: Chinstrap
      island: Dream
      bill_length_mm: 50.8
      bill_depth_mm: 18.5
      flipper_length_mm: 201.0
      body_mass_g: 4450.0
      sex: MALE
    - index: 198
      species: Chinstrap
      island: Dream
      bill_length_mm: 50.1
      bill_depth_mm: 17.9
      flipper_length_mm: 190.0
      body_mass_g: 3400.0
      sex: FEMALE
    - index: 199
      species: Chinstrap
      island: Dream
      bill_length_mm: 49.0
      bill_depth_mm: 19.6
      flipper_length_mm: 212.0
      body_mass_g: 4300.0
      sex: MALE
    - index: 200
      species: Chinstrap
      island: Dream
      bill_length_mm: 51.5
      bill_depth_mm: 18.7
      flipper_length_mm: 187.0
      body_mass_g: 3250.0
      sex: MALE
    - index: 201
      species: Chinstrap
      island: Dream
      bill_length_mm: 49.8
      bill_depth_mm: 17.3
      flipper_length_mm: 198.0
      body_mass_g: 3675.0
      sex: FEMALE
    - index: 202
      species: Chinstrap
      island: Dream
      bill_length_mm: 48.1
      bill_depth_mm: 16.4
      flipper_length_mm: 199.0
      body_mass_g: 3325.0
      sex: FEMALE
    - index: 203
      species: Chinstrap
      island: Dream
      bill_length_mm: 51.4
      bill_depth_mm: 19.0
      flipper_length_mm: 201.0
      body_mass_g: 3950.0
      sex: MALE
    - index: 204
      species: Chinstrap
      island: Dream
      bill_length_mm: 45.7
      bill_depth_mm: 17.3
      flipper_length_mm: 193.0
      body_mass_g: 3600.0
      sex: FEMALE
    - index: 205
      species: Chinstrap
      island: Dream
      bill_length_mm: 50.7
      bill_depth_mm: 19.7
      flipper_length_mm: 203.0
      body_mass_g: 4050.0
      sex: MALE
    - index: 206
      species: Chinstrap
      island: Dream
      bill_length_mm: 42.5
      bill_depth_mm: 17.3
      flipper_length_mm: 187.0
      body_mass_g: 3350.0
      sex: FEMALE
    - index: 207
      species: Chinstrap
      island: Dream
      bill_length_mm: 52.2
      bill_depth_mm: 18.8
      flipper_length_mm: 197.0
      body_mass_g: 3450.0
      sex: MALE
    - index: 208
      species: Chinstrap
      island: Dream
      bill_length_mm: 45.2
      bill_depth_mm: 16.6
      flipper_length_mm: 191.0
      body_mass_g: 3250.0
      sex: FEMALE
    - index: 209
      species: Chinstrap
      island: Dream
      bill_length_mm: 49.3
      bill_depth_mm: 19.9
      flipper_length_mm: 203.0
      body_mass_g: 4050.0
      sex: MALE
    - index: 210
      species: Chinstrap
      island: Dream
      bill_length_mm: 50.2
      bill_depth_mm: 18.8
      flipper_length_mm: 202.0
      body_mass_g: 3800.0
      sex: MALE
    - index: 211
      species: Chinstrap
      island: Dream
      bill_length_mm: 45.6
      bill_depth_mm: 19.4
      flipper_length_mm: 194.0
      body_mass_g: 3525.0
      sex: FEMALE
    - index: 212
      species: Chinstrap
      island: Dream
      bill_length_mm: 51.9
      bill_depth_mm: 19.5
      flipper_length_mm: 206.0
      body_mass_g: 3950.0
      sex: MALE
    - index: 213
      species: Chinstrap
      island: Dream
      bill_length_mm: 46.8
      bill_depth_mm: 16.5
      flipper_length_mm: 189.0
      body_mass_g: 3650.0
      sex: FEMALE
    - index: 214
      species: Chinstrap
      island: Dream
      bill_length_mm: 45.7
      bill_depth_mm: 17.0
      flipper_length_mm: 195.0
      body_mass_g: 3650.0
      sex: FEMALE
    - index: 215
      species: Chinstrap
      island: Dream
      bill_length_mm: 55.8
      bill_depth_mm: 19.8
      flipper_length_mm: 207.0
      body_mass_g: 4000.0
      sex: MALE
    - index: 216
      species: Chinstrap
      island: Dream
      bill_length_mm: 43.5
      bill_depth_mm: 18.1
      flipper_length_mm: 202.0
      body_mass_g: 3400.0
      sex: FEMALE
    - index: 217
      species: Chinstrap
      island: Dream
      bill_length_mm: 49.6
      bill_depth_mm: 18.2
      flipper_length_mm: 193.0
      body_mass_g: 3775.0
      sex: MALE
    - index: 218
      species: Chinstrap
      island: Dream
      bill_length_mm: 50.8
      bill_depth_mm: 19.0
      flipper_length_mm: 210.0
      body_mass_g: 4100.0
      sex: MALE
    - index: 219
      species: Chinstrap
      island: Dream
      bill_length_mm: 50.2
      bill_depth_mm: 18.7
      flipper_length_mm: 198.0
      body_mass_g: 3775.0
      sex: FEMALE
    - index: 220
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.1
      bill_depth_mm: 13.2
      flipper_length_mm: 211.0
      body_mass_g: 4500.0
      sex: FEMALE
    - index: 221
      species: Gentoo
      island: Biscoe
      bill_length_mm: 50.0
      bill_depth_mm: 16.3
      flipper_length_mm: 230.0
      body_mass_g: 5700.0
      sex: MALE
    - index: 222
      species: Gentoo
      island: Biscoe
      bill_length_mm: 48.7
      bill_depth_mm: 14.1
      flipper_length_mm: 210.0
      body_mass_g: 4450.0
      sex: FEMALE
    - index: 223
      species: Gentoo
      island: Biscoe
      bill_length_mm: 50.0
      bill_depth_mm: 15.2
      flipper_length_mm: 218.0
      body_mass_g: 5700.0
      sex: MALE
    - index: 224
      species: Gentoo
      island: Biscoe
      bill_length_mm: 47.6
      bill_depth_mm: 14.5
      flipper_length_mm: 215.0
      body_mass_g: 5400.0
      sex: MALE
    - index: 225
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.5
      bill_depth_mm: 13.5
      flipper_length_mm: 210.0
      body_mass_g: 4550.0
      sex: FEMALE
    - index: 226
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.4
      bill_depth_mm: 14.6
      flipper_length_mm: 211.0
      body_mass_g: 4800.0
      sex: FEMALE
    - index: 227
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.7
      bill_depth_mm: 15.3
      flipper_length_mm: 219.0
      body_mass_g: 5200.0
      sex: MALE
    - index: 228
      species: Gentoo
      island: Biscoe
      bill_length_mm: 43.3
      bill_depth_mm: 13.4
      flipper_length_mm: 209.0
      body_mass_g: 4400.0
      sex: FEMALE
    - index: 229
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.8
      bill_depth_mm: 15.4
      flipper_length_mm: 215.0
      body_mass_g: 5150.0
      sex: MALE
    - index: 230
      species: Gentoo
      island: Biscoe
      bill_length_mm: 40.9
      bill_depth_mm: 13.7
      flipper_length_mm: 214.0
      body_mass_g: 4650.0
      sex: FEMALE
    - index: 231
      species: Gentoo
      island: Biscoe
      bill_length_mm: 49.0
      bill_depth_mm: 16.1
      flipper_length_mm: 216.0
      body_mass_g: 5550.0
      sex: MALE
    - index: 232
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.5
      bill_depth_mm: 13.7
      flipper_length_mm: 214.0
      body_mass_g: 4650.0
      sex: FEMALE
    - index: 233
      species: Gentoo
      island: Biscoe
      bill_length_mm: 48.4
      bill_depth_mm: 14.6
      flipper_length_mm: 213.0
      body_mass_g: 5850.0
      sex: MALE
    - index: 234
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.8
      bill_depth_mm: 14.6
      flipper_length_mm: 210.0
      body_mass_g: 4200.0
      sex: FEMALE
    - index: 235
      species: Gentoo
      island: Biscoe
      bill_length_mm: 49.3
      bill_depth_mm: 15.7
      flipper_length_mm: 217.0
      body_mass_g: 5850.0
      sex: MALE
    - index: 236
      species: Gentoo
      island: Biscoe
      bill_length_mm: 42.0
      bill_depth_mm: 13.5
      flipper_length_mm: 210.0
      body_mass_g: 4150.0
      sex: FEMALE
    - index: 237
      species: Gentoo
      island: Biscoe
      bill_length_mm: 49.2
      bill_depth_mm: 15.2
      flipper_length_mm: 221.0
      body_mass_g: 6300.0
      sex: MALE
    - index: 238
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.2
      bill_depth_mm: 14.5
      flipper_length_mm: 209.0
      body_mass_g: 4800.0
      sex: FEMALE
    - index: 239
      species: Gentoo
      island: Biscoe
      bill_length_mm: 48.7
      bill_depth_mm: 15.1
      flipper_length_mm: 222.0
      body_mass_g: 5350.0
      sex: MALE
    - index: 240
      species: Gentoo
      island: Biscoe
      bill_length_mm: 50.2
      bill_depth_mm: 14.3
      flipper_length_mm: 218.0
      body_mass_g: 5700.0
      sex: MALE
    - index: 241
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.1
      bill_depth_mm: 14.5
      flipper_length_mm: 215.0
      body_mass_g: 5000.0
      sex: FEMALE
    - index: 242
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.5
      bill_depth_mm: 14.5
      flipper_length_mm: 213.0
      body_mass_g: 4400.0
      sex: FEMALE
    - index: 243
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.3
      bill_depth_mm: 15.8
      flipper_length_mm: 215.0
      body_mass_g: 5050.0
      sex: MALE
    - index: 244
      species: Gentoo
      island: Biscoe
      bill_length_mm: 42.9
      bill_depth_mm: 13.1
      flipper_length_mm: 215.0
      body_mass_g: 5000.0
      sex: FEMALE
    - index: 245
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.1
      bill_depth_mm: 15.1
      flipper_length_mm: 215.0
      body_mass_g: 5100.0
      sex: MALE
    - index: 246
      species: Gentoo
      island: Biscoe
      bill_length_mm: 44.5
      bill_depth_mm: 14.3
      flipper_length_mm: 216.0
      body_mass_g: 4100.0
      sex: null
    - index: 247
      species: Gentoo
      island: Biscoe
      bill_length_mm: 47.8
      bill_depth_mm: 15.0
      flipper_length_mm: 215.0
      body_mass_g: 5650.0
      sex: MALE
    - index: 248
      species: Gentoo
      island: Biscoe
      bill_length_mm: 48.2
      bill_depth_mm: 14.3
      flipper_length_mm: 210.0
      body_mass_g: 4600.0
      sex: FEMALE
    - index: 249
      species: Gentoo
      island: Biscoe
      bill_length_mm: 50.0
      bill_depth_mm: 15.3
      flipper_length_mm: 220.0
      body_mass_g: 5550.0
      sex: MALE
    - index: 250
      species: Gentoo
      island: Biscoe
      bill_length_mm: 47.3
      bill_depth_mm: 15.3
      flipper_length_mm: 222.0
      body_mass_g: 5250.0
      sex: MALE
    - index: 251
      species: Gentoo
      island: Biscoe
      bill_length_mm: 42.8
      bill_depth_mm: 14.2
      flipper_length_mm: 209.0
      body_mass_g: 4700.0
      sex: FEMALE
    - index: 252
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.1
      bill_depth_mm: 14.5
      flipper_length_mm: 207.0
      body_mass_g: 5050.0
      sex: FEMALE
    - index: 253
      species: Gentoo
      island: Biscoe
      bill_length_mm: 59.6
      bill_depth_mm: 17.0
      flipper_length_mm: 230.0
      body_mass_g: 6050.0
      sex: MALE
    - index: 254
      species: Gentoo
      island: Biscoe
      bill_length_mm: 49.1
      bill_depth_mm: 14.8
      flipper_length_mm: 220.0
      body_mass_g: 5150.0
      sex: FEMALE
    - index: 255
      species: Gentoo
      island: Biscoe
      bill_length_mm: 48.4
      bill_depth_mm: 16.3
      flipper_length_mm: 220.0
      body_mass_g: 5400.0
      sex: MALE
    - index: 256
      species: Gentoo
      island: Biscoe
      bill_length_mm: 42.6
      bill_depth_mm: 13.7
      flipper_length_mm: 213.0
      body_mass_g: 4950.0
      sex: FEMALE
    - index: 257
      species: Gentoo
      island: Biscoe
      bill_length_mm: 44.4
      bill_depth_mm: 17.3
      flipper_length_mm: 219.0
      body_mass_g: 5250.0
      sex: MALE
    - index: 258
      species: Gentoo
      island: Biscoe
      bill_length_mm: 44.0
      bill_depth_mm: 13.6
      flipper_length_mm: 208.0
      body_mass_g: 4350.0
      sex: FEMALE
    - index: 259
      species: Gentoo
      island: Biscoe
      bill_length_mm: 48.7
      bill_depth_mm: 15.7
      flipper_length_mm: 208.0
      body_mass_g: 5350.0
      sex: MALE
    - index: 260
      species: Gentoo
      island: Biscoe
      bill_length_mm: 42.7
      bill_depth_mm: 13.7
      flipper_length_mm: 208.0
      body_mass_g: 3950.0
      sex: FEMALE
    - index: 261
      species: Gentoo
      island: Biscoe
      bill_length_mm: 49.6
      bill_depth_mm: 16.0
      flipper_length_mm: 225.0
      body_mass_g: 5700.0
      sex: MALE
    - index: 262
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.3
      bill_depth_mm: 13.7
      flipper_length_mm: 210.0
      body_mass_g: 4300.0
      sex: FEMALE
    - index: 263
      species: Gentoo
      island: Biscoe
      bill_length_mm: 49.6
      bill_depth_mm: 15.0
      flipper_length_mm: 216.0
      body_mass_g: 4750.0
      sex: MALE
    - index: 264
      species: Gentoo
      island: Biscoe
      bill_length_mm: 50.5
      bill_depth_mm: 15.9
      flipper_length_mm: 222.0
      body_mass_g: 5550.0
      sex: MALE
    - index: 265
      species: Gentoo
      island: Biscoe
      bill_length_mm: 43.6
      bill_depth_mm: 13.9
      flipper_length_mm: 217.0
      body_mass_g: 4900.0
      sex: FEMALE
    - index: 266
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.5
      bill_depth_mm: 13.9
      flipper_length_mm: 210.0
      body_mass_g: 4200.0
      sex: FEMALE
    - index: 267
      species: Gentoo
      island: Biscoe
      bill_length_mm: 50.5
      bill_depth_mm: 15.9
      flipper_length_mm: 225.0
      body_mass_g: 5400.0
      sex: MALE
    - index: 268
      species: Gentoo
      island: Biscoe
      bill_length_mm: 44.9
      bill_depth_mm: 13.3
      flipper_length_mm: 213.0
      body_mass_g: 5100.0
      sex: FEMALE
    - index: 269
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.2
      bill_depth_mm: 15.8
      flipper_length_mm: 215.0
      body_mass_g: 5300.0
      sex: MALE
    - index: 270
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.6
      bill_depth_mm: 14.2
      flipper_length_mm: 210.0
      body_mass_g: 4850.0
      sex: FEMALE
    - index: 271
      species: Gentoo
      island: Biscoe
      bill_length_mm: 48.5
      bill_depth_mm: 14.1
      flipper_length_mm: 220.0
      body_mass_g: 5300.0
      sex: MALE
    - index: 272
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.1
      bill_depth_mm: 14.4
      flipper_length_mm: 210.0
      body_mass_g: 4400.0
      sex: FEMALE
    - index: 273
      species: Gentoo
      island: Biscoe
      bill_length_mm: 50.1
      bill_depth_mm: 15.0
      flipper_length_mm: 225.0
      body_mass_g: 5000.0
      sex: MALE
    - index: 274
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.5
      bill_depth_mm: 14.4
      flipper_length_mm: 217.0
      body_mass_g: 4900.0
      sex: FEMALE
    - index: 275
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.0
      bill_depth_mm: 15.4
      flipper_length_mm: 220.0
      body_mass_g: 5050.0
      sex: MALE
    - index: 276
      species: Gentoo
      island: Biscoe
      bill_length_mm: 43.8
      bill_depth_mm: 13.9
      flipper_length_mm: 208.0
      body_mass_g: 4300.0
      sex: FEMALE
    - index: 277
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.5
      bill_depth_mm: 15.0
      flipper_length_mm: 220.0
      body_mass_g: 5000.0
      sex: MALE
    - index: 278
      species: Gentoo
      island: Biscoe
      bill_length_mm: 43.2
      bill_depth_mm: 14.5
      flipper_length_mm: 208.0
      body_mass_g: 4450.0
      sex: FEMALE
    - index: 279
      species: Gentoo
      island: Biscoe
      bill_length_mm: 50.4
      bill_depth_mm: 15.3
      flipper_length_mm: 224.0
      body_mass_g: 5550.0
      sex: MALE
    - index: 280
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.3
      bill_depth_mm: 13.8
      flipper_length_mm: 208.0
      body_mass_g: 4200.0
      sex: FEMALE
    - index: 281
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.2
      bill_depth_mm: 14.9
      flipper_length_mm: 221.0
      body_mass_g: 5300.0
      sex: MALE
    - index: 282
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.7
      bill_depth_mm: 13.9
      flipper_length_mm: 214.0
      body_mass_g: 4400.0
      sex: FEMALE
    - index: 283
      species: Gentoo
      island: Biscoe
      bill_length_mm: 54.3
      bill_depth_mm: 15.7
      flipper_length_mm: 231.0
      body_mass_g: 5650.0
      sex: MALE
    - index: 284
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.8
      bill_depth_mm: 14.2
      flipper_length_mm: 219.0
      body_mass_g: 4700.0
      sex: FEMALE
    - index: 285
      species: Gentoo
      island: Biscoe
      bill_length_mm: 49.8
      bill_depth_mm: 16.8
      flipper_length_mm: 230.0
      body_mass_g: 5700.0
      sex: MALE
    - index: 286
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.2
      bill_depth_mm: 14.4
      flipper_length_mm: 214.0
      body_mass_g: 4650.0
      sex: null
    - index: 287
      species: Gentoo
      island: Biscoe
      bill_length_mm: 49.5
      bill_depth_mm: 16.2
      flipper_length_mm: 229.0
      body_mass_g: 5800.0
      sex: MALE
    - index: 288
      species: Gentoo
      island: Biscoe
      bill_length_mm: 43.5
      bill_depth_mm: 14.2
      flipper_length_mm: 220.0
      body_mass_g: 4700.0
      sex: FEMALE
    - index: 289
      species: Gentoo
      island: Biscoe
      bill_length_mm: 50.7
      bill_depth_mm: 15.0
      flipper_length_mm: 223.0
      body_mass_g: 5550.0
      sex: MALE
    - index: 290
      species: Gentoo
      island: Biscoe
      bill_length_mm: 47.7
      bill_depth_mm: 15.0
      flipper_length_mm: 216.0
      body_mass_g: 4750.0
      sex: FEMALE
    - index: 291
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.4
      bill_depth_mm: 15.6
      flipper_length_mm: 221.0
      body_mass_g: 5000.0
      sex: MALE
    - index: 292
      species: Gentoo
      island: Biscoe
      bill_length_mm: 48.2
      bill_depth_mm: 15.6
      flipper_length_mm: 221.0
      body_mass_g: 5100.0
      sex: MALE
    - index: 293
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.5
      bill_depth_mm: 14.8
      flipper_length_mm: 217.0
      body_mass_g: 5200.0
      sex: FEMALE
    - index: 294
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.4
      bill_depth_mm: 15.0
      flipper_length_mm: 216.0
      body_mass_g: 4700.0
      sex: FEMALE
    - index: 295
      species: Gentoo
      island: Biscoe
      bill_length_mm: 48.6
      bill_depth_mm: 16.0
      flipper_length_mm: 230.0
      body_mass_g: 5800.0
      sex: MALE
    - index: 296
      species: Gentoo
      island: Biscoe
      bill_length_mm: 47.5
      bill_depth_mm: 14.2
      flipper_length_mm: 209.0
      body_mass_g: 4600.0
      sex: FEMALE
    - index: 297
      species: Gentoo
      island: Biscoe
      bill_length_mm: 51.1
      bill_depth_mm: 16.3
      flipper_length_mm: 220.0
      body_mass_g: 6000.0
      sex: MALE
    - index: 298
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.2
      bill_depth_mm: 13.8
      flipper_length_mm: 215.0
      body_mass_g: 4750.0
      sex: FEMALE
    - index: 299
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.2
      bill_depth_mm: 16.4
      flipper_length_mm: 223.0
      body_mass_g: 5950.0
      sex: MALE
    - index: 300
      species: Gentoo
      island: Biscoe
      bill_length_mm: 49.1
      bill_depth_mm: 14.5
      flipper_length_mm: 212.0
      body_mass_g: 4625.0
      sex: FEMALE
    - index: 301
      species: Gentoo
      island: Biscoe
      bill_length_mm: 52.5
      bill_depth_mm: 15.6
      flipper_length_mm: 221.0
      body_mass_g: 5450.0
      sex: MALE
    - index: 302
      species: Gentoo
      island: Biscoe
      bill_length_mm: 47.4
      bill_depth_mm: 14.6
      flipper_length_mm: 212.0
      body_mass_g: 4725.0
      sex: FEMALE
    - index: 303
      species: Gentoo
      island: Biscoe
      bill_length_mm: 50.0
      bill_depth_mm: 15.9
      flipper_length_mm: 224.0
      body_mass_g: 5350.0
      sex: MALE
    - index: 304
      species: Gentoo
      island: Biscoe
      bill_length_mm: 44.9
      bill_depth_mm: 13.8
      flipper_length_mm: 212.0
      body_mass_g: 4750.0
      sex: FEMALE
    - index: 305
      species: Gentoo
      island: Biscoe
      bill_length_mm: 50.8
      bill_depth_mm: 17.3
      flipper_length_mm: 228.0
      body_mass_g: 5600.0
      sex: MALE
    - index: 306
      species: Gentoo
      island: Biscoe
      bill_length_mm: 43.4
      bill_depth_mm: 14.4
      flipper_length_mm: 218.0
      body_mass_g: 4600.0
      sex: FEMALE
    - index: 307
      species: Gentoo
      island: Biscoe
      bill_length_mm: 51.3
      bill_depth_mm: 14.2
      flipper_length_mm: 218.0
      body_mass_g: 5300.0
      sex: MALE
    - index: 308
      species: Gentoo
      island: Biscoe
      bill_length_mm: 47.5
      bill_depth_mm: 14.0
      flipper_length_mm: 212.0
      body_mass_g: 4875.0
      sex: FEMALE
    - index: 309
      species: Gentoo
      island: Biscoe
      bill_length_mm: 52.1
      bill_depth_mm: 17.0
      flipper_length_mm: 230.0
      body_mass_g: 5550.0
      sex: MALE
    - index: 310
      species: Gentoo
      island: Biscoe
      bill_length_mm: 47.5
      bill_depth_mm: 15.0
      flipper_length_mm: 218.0
      body_mass_g: 4950.0
      sex: FEMALE
    - index: 311
      species: Gentoo
      island: Biscoe
      bill_length_mm: 52.2
      bill_depth_mm: 17.1
      flipper_length_mm: 228.0
      body_mass_g: 5400.0
      sex: MALE
    - index: 312
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.5
      bill_depth_mm: 14.5
      flipper_length_mm: 212.0
      body_mass_g: 4750.0
      sex: FEMALE
    - index: 313
      species: Gentoo
      island: Biscoe
      bill_length_mm: 49.5
      bill_depth_mm: 16.1
      flipper_length_mm: 224.0
      body_mass_g: 5650.0
      sex: MALE
    - index: 314
      species: Gentoo
      island: Biscoe
      bill_length_mm: 44.5
      bill_depth_mm: 14.7
      flipper_length_mm: 214.0
      body_mass_g: 4850.0
      sex: FEMALE
    - index: 315
      species: Gentoo
      island: Biscoe
      bill_length_mm: 50.8
      bill_depth_mm: 15.7
      flipper_length_mm: 226.0
      body_mass_g: 5200.0
      sex: MALE
    - index: 316
      species: Gentoo
      island: Biscoe
      bill_length_mm: 49.4
      bill_depth_mm: 15.8
      flipper_length_mm: 216.0
      body_mass_g: 4925.0
      sex: MALE
    - index: 317
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.9
      bill_depth_mm: 14.6
      flipper_length_mm: 222.0
      body_mass_g: 4875.0
      sex: FEMALE
    - index: 318
      species: Gentoo
      island: Biscoe
      bill_length_mm: 48.4
      bill_depth_mm: 14.4
      flipper_length_mm: 203.0
      body_mass_g: 4625.0
      sex: FEMALE
    - index: 319
      species: Gentoo
      island: Biscoe
      bill_length_mm: 51.1
      bill_depth_mm: 16.5
      flipper_length_mm: 225.0
      body_mass_g: 5250.0
      sex: MALE
    - index: 320
      species: Gentoo
      island: Biscoe
      bill_length_mm: 48.5
      bill_depth_mm: 15.0
      flipper_length_mm: 219.0
      body_mass_g: 4850.0
      sex: FEMALE
    - index: 321
      species: Gentoo
      island: Biscoe
      bill_length_mm: 55.9
      bill_depth_mm: 17.0
      flipper_length_mm: 228.0
      body_mass_g: 5600.0
      sex: MALE
    - index: 322
      species: Gentoo
      island: Biscoe
      bill_length_mm: 47.2
      bill_depth_mm: 15.5
      flipper_length_mm: 215.0
      body_mass_g: 4975.0
      sex: FEMALE
    - index: 323
      species: Gentoo
      island: Biscoe
      bill_length_mm: 49.1
      bill_depth_mm: 15.0
      flipper_length_mm: 228.0
      body_mass_g: 5500.0
      sex: MALE
    - index: 324
      species: Gentoo
      island: Biscoe
      bill_length_mm: 47.3
      bill_depth_mm: 13.8
      flipper_length_mm: 216.0
      body_mass_g: 4725.0
      sex: null
    - index: 325
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.8
      bill_depth_mm: 16.1
      flipper_length_mm: 215.0
      body_mass_g: 5500.0
      sex: MALE
    - index: 326
      species: Gentoo
      island: Biscoe
      bill_length_mm: 41.7
      bill_depth_mm: 14.7
      flipper_length_mm: 210.0
      body_mass_g: 4700.0
      sex: FEMALE
    - index: 327
      species: Gentoo
      island: Biscoe
      bill_length_mm: 53.4
      bill_depth_mm: 15.8
      flipper_length_mm: 219.0
      body_mass_g: 5500.0
      sex: MALE
    - index: 328
      species: Gentoo
      island: Biscoe
      bill_length_mm: 43.3
      bill_depth_mm: 14.0
      flipper_length_mm: 208.0
      body_mass_g: 4575.0
      sex: FEMALE
    - index: 329
      species: Gentoo
      island: Biscoe
      bill_length_mm: 48.1
      bill_depth_mm: 15.1
      flipper_length_mm: 209.0
      body_mass_g: 5500.0
      sex: MALE
    - index: 330
      species: Gentoo
      island: Biscoe
      bill_length_mm: 50.5
      bill_depth_mm: 15.2
      flipper_length_mm: 216.0
      body_mass_g: 5000.0
      sex: FEMALE
    - index: 331
      species: Gentoo
      island: Biscoe
      bill_length_mm: 49.8
      bill_depth_mm: 15.9
      flipper_length_mm: 229.0
      body_mass_g: 5950.0
      sex: MALE
    - index: 332
      species: Gentoo
      island: Biscoe
      bill_length_mm: 43.5
      bill_depth_mm: 15.2
      flipper_length_mm: 213.0
      body_mass_g: 4650.0
      sex: FEMALE
    - index: 333
      species: Gentoo
      island: Biscoe
      bill_length_mm: 51.5
      bill_depth_mm: 16.3
      flipper_length_mm: 230.0
      body_mass_g: 5500.0
      sex: MALE
    - index: 334
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.2
      bill_depth_mm: 14.1
      flipper_length_mm: 217.0
      body_mass_g: 4375.0
      sex: FEMALE
    - index: 335
      species: Gentoo
      island: Biscoe
      bill_length_mm: 55.1
      bill_depth_mm: 16.0
      flipper_length_mm: 230.0
      body_mass_g: 5850.0
      sex: MALE
    - index: 336
      species: Gentoo
      island: Biscoe
      bill_length_mm: 44.5
      bill_depth_mm: 15.7
      flipper_length_mm: 217.0
      body_mass_g: 4875.0
      sex: null
    - index: 337
      species: Gentoo
      island: Biscoe
      bill_length_mm: 48.8
      bill_depth_mm: 16.2
      flipper_length_mm: 222.0
      body_mass_g: 6000.0
      sex: MALE
    - index: 338
      species: Gentoo
      island: Biscoe
      bill_length_mm: 47.2
      bill_depth_mm: 13.7
      flipper_length_mm: 214.0
      body_mass_g: 4925.0
      sex: FEMALE
    - index: 339
      species: Gentoo
      island: Biscoe
      bill_length_mm: null
      bill_depth_mm: null
      flipper_length_mm: null
      body_mass_g: null
      sex: null
    - index: 340
      species: Gentoo
      island: Biscoe
      bill_length_mm: 46.8
      bill_depth_mm: 14.3
      flipper_length_mm: 215.0
      body_mass_g: 4850.0
      sex: FEMALE
    - index: 341
      species: Gentoo
      island: Biscoe
      bill_length_mm: 50.4
      bill_depth_mm: 15.7
      flipper_length_mm: 222.0
      body_mass_g: 5750.0
      sex: MALE
    - index: 342
      species: Gentoo
      island: Biscoe
      bill_length_mm: 45.2
      bill_depth_mm: 14.8
      flipper_length_mm: 212.0
      body_mass_g: 5200.0
      sex: FEMALE
    - index: 343
      species: Gentoo
      island: Biscoe
      bill_length_mm: 49.9
      bill_depth_mm: 16.1
      flipper_length_mm: 213.0
      body_mass_g: 5400.0
      sex: MALE
    params_names_for_user:
    - name: df
      type: dataframe
    params_names_from_user:
    - name: groupby
---
# {{ params_vars_title }}

## Question Text

In this quiz we will be looking at exploring the `penguins` dataset.

<pl-figure file-name="penguins.png" directory="clientFilesQuestion" width="300"></pl-figure>

You can load the `penguins` dataset in `seaborn` using:

```python
df = sns.load_dataset("penguins")
```

This dataset contains information about three species of penguins (Adelie, Gentoo, and Chinstrap), and various
characteristics including their bill_length, bill_depth, flipper_length, body_mass, and sex.

<pl-figure file-name="description.png" directory="clientFilesQuestion" width="300"></pl-figure>

Credit: Artwork by [@allison_horst](https://www.allisonhorst.com).

This question requires you to use the `groupby()` method to produce the expected output.

<div class="card my-2">
<div class="card-header">Groupby</div>
<div class="card-body">

With the `penguins` DataFrame above assigned to the variable `df`, what code would you use to return the DataFrame below? We are looking for the **`{{ params_vars_func }}`** of the `penguins` DataFrame grouped by **{{ params_vars_left }}** and **{{ params_vars_right }}**.

*A few things to note*:

1. Your code should only be one line, and
1. The output should have the columns in precisely the **same order** as shown in the table below.

<pl-dataframe params-name="expected" show-dimensions=false show-python=false></pl-dataframe>

</div>
</div>

### Answer Section

### pl-submission-panel

{{feedback.groupby}}

<pl-external-grader-results></pl-external-grader-results>

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)