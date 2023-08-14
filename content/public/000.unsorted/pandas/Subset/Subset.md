---
title: Subset
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
- pokemon.png
autogradeTestFiles:
- ans.py
- setup_code.py
- starter_code.py
- test.py
part1:
  type: string-input
  pl-customizations:
    answers-name: df
    display: block
    placeholder: '...'
    label: 'df = '
    remove-spaces: true
myst:
  substitutions:
    params_vars_title: Subset
    params_vars_df__type: dataframe_v2
    params_vars_df__value_schema_fields:
    - name: index
      type: integer
    - name: '#'
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
      type: number
    - name: Attack
      type: number
    - name: Defense
      type: number
    - name: Sp. Atk
      type: number
    - name: Sp. Def
      type: number
    - name: Speed
      type: integer
    - name: Generation
      type: integer
    - name: Legendary
      type: boolean
    params_vars_df__value_schema_primaryKey:
    - index
    params_vars_df__value_schema_pandas_version: 1.4.0
    params_vars_df__value_data:
    - index: 0
      '#': 1
      Name: Bulbasaur
      Type 1: Grass
      Type 2: Poison
      Total: 318
      HP: 45.0
      Attack: 49.0
      Defense: 49.0
      Sp. Atk: 65.0
      Sp. Def: 65.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 1
      '#': 2
      Name: Ivysaur
      Type 1: Grass
      Type 2: Poison
      Total: 405
      HP: 60.0
      Attack: 62.0
      Defense: 63.0
      Sp. Atk: 80.0
      Sp. Def: 80.0
      Speed: 60
      Generation: 1
      Legendary: false
    - index: 2
      '#': 3
      Name: Venusaur
      Type 1: Grass
      Type 2: Poison
      Total: 525
      HP: 80.0
      Attack: 82.0
      Defense: 83.0
      Sp. Atk: 100.0
      Sp. Def: 100.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 3
      '#': 3
      Name: VenusaurMega Venusaur
      Type 1: Grass
      Type 2: Poison
      Total: 625
      HP: 80.0
      Attack: 100.0
      Defense: 123.0
      Sp. Atk: 122.0
      Sp. Def: 120.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 4
      '#': 4
      Name: Charmander
      Type 1: Fire
      Type 2: null
      Total: 309
      HP: 39.0
      Attack: 52.0
      Defense: 43.0
      Sp. Atk: 60.0
      Sp. Def: 50.0
      Speed: 65
      Generation: 1
      Legendary: false
    - index: 5
      '#': 5
      Name: Charmeleon
      Type 1: Fire
      Type 2: null
      Total: 405
      HP: 58.0
      Attack: 64.0
      Defense: 58.0
      Sp. Atk: 80.0
      Sp. Def: 65.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 6
      '#': 6
      Name: Charizard
      Type 1: Fire
      Type 2: Flying
      Total: 534
      HP: 78.0
      Attack: 84.0
      Defense: 78.0
      Sp. Atk: 109.0
      Sp. Def: 85.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 7
      '#': 6
      Name: CharizardMega Charizard X
      Type 1: Fire
      Type 2: Dragon
      Total: 634
      HP: 78.0
      Attack: 130.0
      Defense: 111.0
      Sp. Atk: 130.0
      Sp. Def: 85.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 8
      '#': 6
      Name: CharizardMega Charizard Y
      Type 1: Fire
      Type 2: Flying
      Total: 634
      HP: 78.0
      Attack: 104.0
      Defense: 78.0
      Sp. Atk: 159.0
      Sp. Def: 115.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 9
      '#': 7
      Name: Squirtle
      Type 1: Water
      Type 2: null
      Total: 314
      HP: 44.0
      Attack: 48.0
      Defense: 65.0
      Sp. Atk: 50.0
      Sp. Def: 64.0
      Speed: 43
      Generation: 1
      Legendary: false
    - index: 10
      '#': 8
      Name: Wartortle
      Type 1: Water
      Type 2: null
      Total: 405
      HP: 59.0
      Attack: 63.0
      Defense: 80.0
      Sp. Atk: 65.0
      Sp. Def: null
      Speed: 58
      Generation: 1
      Legendary: false
    - index: 11
      '#': 9
      Name: Blastoise
      Type 1: Water
      Type 2: null
      Total: 530
      HP: 79.0
      Attack: 83.0
      Defense: 100.0
      Sp. Atk: 85.0
      Sp. Def: 105.0
      Speed: 78
      Generation: 1
      Legendary: false
    - index: 12
      '#': 9
      Name: BlastoiseMega Blastoise
      Type 1: Water
      Type 2: null
      Total: 630
      HP: 79.0
      Attack: 103.0
      Defense: 120.0
      Sp. Atk: 135.0
      Sp. Def: 115.0
      Speed: 78
      Generation: 1
      Legendary: false
    - index: 13
      '#': 10
      Name: Caterpie
      Type 1: Bug
      Type 2: null
      Total: 195
      HP: 45.0
      Attack: 30.0
      Defense: null
      Sp. Atk: null
      Sp. Def: 20.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 14
      '#': 11
      Name: Metapod
      Type 1: Bug
      Type 2: null
      Total: 205
      HP: 50.0
      Attack: 20.0
      Defense: null
      Sp. Atk: 25.0
      Sp. Def: null
      Speed: 30
      Generation: 1
      Legendary: false
    - index: 15
      '#': 12
      Name: Butterfree
      Type 1: Bug
      Type 2: Flying
      Total: 395
      HP: null
      Attack: 45.0
      Defense: 50.0
      Sp. Atk: 90.0
      Sp. Def: 80.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 16
      '#': 13
      Name: Weedle
      Type 1: Bug
      Type 2: Poison
      Total: 195
      HP: 40.0
      Attack: 35.0
      Defense: 30.0
      Sp. Atk: 20.0
      Sp. Def: null
      Speed: 50
      Generation: 1
      Legendary: false
    - index: 17
      '#': 14
      Name: Kakuna
      Type 1: Bug
      Type 2: Poison
      Total: 205
      HP: 45.0
      Attack: null
      Defense: 50.0
      Sp. Atk: null
      Sp. Def: 25.0
      Speed: 35
      Generation: 1
      Legendary: false
    - index: 18
      '#': 15
      Name: Beedrill
      Type 1: Bug
      Type 2: Poison
      Total: 395
      HP: 65.0
      Attack: 90.0
      Defense: 40.0
      Sp. Atk: 45.0
      Sp. Def: null
      Speed: 75
      Generation: 1
      Legendary: false
    - index: 19
      '#': 15
      Name: BeedrillMega Beedrill
      Type 1: Bug
      Type 2: Poison
      Total: 495
      HP: 65.0
      Attack: 150.0
      Defense: 40.0
      Sp. Atk: 15.0
      Sp. Def: 80.0
      Speed: 145
      Generation: 1
      Legendary: false
    - index: 20
      '#': 16
      Name: Pidgey
      Type 1: Normal
      Type 2: Flying
      Total: 251
      HP: 40.0
      Attack: 45.0
      Defense: 40.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 56
      Generation: 1
      Legendary: false
    - index: 21
      '#': 17
      Name: Pidgeotto
      Type 1: Normal
      Type 2: Flying
      Total: 349
      HP: 63.0
      Attack: 60.0
      Defense: 55.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 71
      Generation: 1
      Legendary: false
    - index: 22
      '#': 18
      Name: Pidgeot
      Type 1: Normal
      Type 2: Flying
      Total: 479
      HP: 83.0
      Attack: 80.0
      Defense: 75.0
      Sp. Atk: 70.0
      Sp. Def: 70.0
      Speed: 101
      Generation: 1
      Legendary: false
    - index: 23
      '#': 18
      Name: PidgeotMega Pidgeot
      Type 1: Normal
      Type 2: Flying
      Total: 579
      HP: 83.0
      Attack: 80.0
      Defense: 80.0
      Sp. Atk: 135.0
      Sp. Def: 80.0
      Speed: 121
      Generation: 1
      Legendary: false
    - index: 24
      '#': 19
      Name: Rattata
      Type 1: Normal
      Type 2: null
      Total: 253
      HP: 30.0
      Attack: 56.0
      Defense: 35.0
      Sp. Atk: 25.0
      Sp. Def: 35.0
      Speed: 72
      Generation: 1
      Legendary: false
    - index: 25
      '#': 20
      Name: Raticate
      Type 1: Normal
      Type 2: null
      Total: 413
      HP: 55.0
      Attack: 81.0
      Defense: 60.0
      Sp. Atk: 50.0
      Sp. Def: 70.0
      Speed: 97
      Generation: 1
      Legendary: false
    - index: 26
      '#': 21
      Name: Spearow
      Type 1: Normal
      Type 2: Flying
      Total: 262
      HP: 40.0
      Attack: 60.0
      Defense: 30.0
      Sp. Atk: 31.0
      Sp. Def: 31.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 27
      '#': 22
      Name: Fearow
      Type 1: Normal
      Type 2: Flying
      Total: 442
      HP: 65.0
      Attack: 90.0
      Defense: 65.0
      Sp. Atk: 61.0
      Sp. Def: 61.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 28
      '#': 23
      Name: Ekans
      Type 1: Poison
      Type 2: null
      Total: 288
      HP: 35.0
      Attack: 60.0
      Defense: 44.0
      Sp. Atk: 40.0
      Sp. Def: 54.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 29
      '#': 24
      Name: Arbok
      Type 1: Poison
      Type 2: null
      Total: 438
      HP: 60.0
      Attack: 85.0
      Defense: 69.0
      Sp. Atk: 65.0
      Sp. Def: 79.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 30
      '#': 25
      Name: Pikachu
      Type 1: Electric
      Type 2: null
      Total: 320
      HP: 35.0
      Attack: 55.0
      Defense: 40.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 31
      '#': 26
      Name: Raichu
      Type 1: Electric
      Type 2: null
      Total: 485
      HP: 60.0
      Attack: 90.0
      Defense: 55.0
      Sp. Atk: 90.0
      Sp. Def: 80.0
      Speed: 110
      Generation: 1
      Legendary: false
    - index: 32
      '#': 27
      Name: Sandshrew
      Type 1: Ground
      Type 2: null
      Total: 300
      HP: 50.0
      Attack: 75.0
      Defense: 85.0
      Sp. Atk: 20.0
      Sp. Def: 30.0
      Speed: 40
      Generation: 1
      Legendary: false
    - index: 33
      '#': 28
      Name: Sandslash
      Type 1: Ground
      Type 2: null
      Total: 450
      HP: 75.0
      Attack: 100.0
      Defense: 110.0
      Sp. Atk: 45.0
      Sp. Def: 55.0
      Speed: 65
      Generation: 1
      Legendary: false
    - index: 34
      '#': 29
      Name: Nidoran♀
      Type 1: Poison
      Type 2: null
      Total: 275
      HP: 55.0
      Attack: 47.0
      Defense: 52.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 41
      Generation: 1
      Legendary: false
    - index: 35
      '#': 30
      Name: Nidorina
      Type 1: Poison
      Type 2: null
      Total: 365
      HP: 70.0
      Attack: 62.0
      Defense: 67.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 56
      Generation: 1
      Legendary: false
    - index: 36
      '#': 31
      Name: Nidoqueen
      Type 1: Poison
      Type 2: Ground
      Total: 505
      HP: 90.0
      Attack: 92.0
      Defense: 87.0
      Sp. Atk: 75.0
      Sp. Def: 85.0
      Speed: 76
      Generation: 1
      Legendary: false
    - index: 37
      '#': 32
      Name: Nidoran♂
      Type 1: Poison
      Type 2: null
      Total: 273
      HP: 46.0
      Attack: 57.0
      Defense: 40.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 50
      Generation: 1
      Legendary: false
    - index: 38
      '#': 33
      Name: Nidorino
      Type 1: Poison
      Type 2: null
      Total: 365
      HP: 61.0
      Attack: 72.0
      Defense: 57.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 65
      Generation: 1
      Legendary: false
    - index: 39
      '#': 34
      Name: Nidoking
      Type 1: Poison
      Type 2: Ground
      Total: 505
      HP: 81.0
      Attack: 102.0
      Defense: 77.0
      Sp. Atk: 85.0
      Sp. Def: 75.0
      Speed: 85
      Generation: 1
      Legendary: false
    - index: 40
      '#': 35
      Name: Clefairy
      Type 1: Fairy
      Type 2: null
      Total: 323
      HP: 70.0
      Attack: 45.0
      Defense: 48.0
      Sp. Atk: 60.0
      Sp. Def: 65.0
      Speed: 35
      Generation: 1
      Legendary: false
    - index: 41
      '#': 36
      Name: Clefable
      Type 1: Fairy
      Type 2: null
      Total: 483
      HP: 95.0
      Attack: 70.0
      Defense: 73.0
      Sp. Atk: 95.0
      Sp. Def: 90.0
      Speed: 60
      Generation: 1
      Legendary: false
    - index: 42
      '#': 37
      Name: Vulpix
      Type 1: Fire
      Type 2: null
      Total: 299
      HP: 38.0
      Attack: 41.0
      Defense: 40.0
      Sp. Atk: 50.0
      Sp. Def: 65.0
      Speed: 65
      Generation: 1
      Legendary: false
    - index: 43
      '#': 38
      Name: Ninetales
      Type 1: Fire
      Type 2: null
      Total: 505
      HP: 73.0
      Attack: 76.0
      Defense: 75.0
      Sp. Atk: 81.0
      Sp. Def: 100.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 44
      '#': 39
      Name: Jigglypuff
      Type 1: Normal
      Type 2: Fairy
      Total: 270
      HP: 115.0
      Attack: 45.0
      Defense: 20.0
      Sp. Atk: 45.0
      Sp. Def: 25.0
      Speed: 20
      Generation: 1
      Legendary: false
    - index: 45
      '#': 40
      Name: Wigglytuff
      Type 1: Normal
      Type 2: Fairy
      Total: 435
      HP: 140.0
      Attack: 70.0
      Defense: 45.0
      Sp. Atk: 85.0
      Sp. Def: 50.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 46
      '#': 41
      Name: Zubat
      Type 1: Poison
      Type 2: Flying
      Total: 245
      HP: 40.0
      Attack: 45.0
      Defense: 35.0
      Sp. Atk: 30.0
      Sp. Def: 40.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 47
      '#': 42
      Name: Golbat
      Type 1: Poison
      Type 2: Flying
      Total: 455
      HP: 75.0
      Attack: 80.0
      Defense: 70.0
      Sp. Atk: 65.0
      Sp. Def: 75.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 48
      '#': 43
      Name: Oddish
      Type 1: Grass
      Type 2: Poison
      Total: 320
      HP: 45.0
      Attack: 50.0
      Defense: 55.0
      Sp. Atk: 75.0
      Sp. Def: 65.0
      Speed: 30
      Generation: 1
      Legendary: false
    - index: 49
      '#': 44
      Name: Gloom
      Type 1: Grass
      Type 2: Poison
      Total: 395
      HP: 60.0
      Attack: 65.0
      Defense: 70.0
      Sp. Atk: 85.0
      Sp. Def: 75.0
      Speed: 40
      Generation: 1
      Legendary: false
    - index: 50
      '#': 45
      Name: Vileplume
      Type 1: Grass
      Type 2: Poison
      Total: 490
      HP: 75.0
      Attack: 80.0
      Defense: 85.0
      Sp. Atk: 110.0
      Sp. Def: 90.0
      Speed: 50
      Generation: 1
      Legendary: false
    - index: 51
      '#': 46
      Name: Paras
      Type 1: Bug
      Type 2: Grass
      Total: 285
      HP: 35.0
      Attack: 70.0
      Defense: 55.0
      Sp. Atk: 45.0
      Sp. Def: 55.0
      Speed: 25
      Generation: 1
      Legendary: false
    - index: 52
      '#': 47
      Name: Parasect
      Type 1: Bug
      Type 2: Grass
      Total: 405
      HP: 60.0
      Attack: 95.0
      Defense: 80.0
      Sp. Atk: 60.0
      Sp. Def: 80.0
      Speed: 30
      Generation: 1
      Legendary: false
    - index: 53
      '#': 48
      Name: Venonat
      Type 1: Bug
      Type 2: Poison
      Total: 305
      HP: 60.0
      Attack: 55.0
      Defense: 50.0
      Sp. Atk: 40.0
      Sp. Def: 55.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 54
      '#': 49
      Name: Venomoth
      Type 1: Bug
      Type 2: Poison
      Total: 450
      HP: 70.0
      Attack: 65.0
      Defense: 60.0
      Sp. Atk: 90.0
      Sp. Def: 75.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 55
      '#': 50
      Name: Diglett
      Type 1: Ground
      Type 2: null
      Total: 265
      HP: 10.0
      Attack: 55.0
      Defense: 25.0
      Sp. Atk: 35.0
      Sp. Def: 45.0
      Speed: 95
      Generation: 1
      Legendary: false
    - index: 56
      '#': 51
      Name: Dugtrio
      Type 1: Ground
      Type 2: null
      Total: 405
      HP: 35.0
      Attack: 80.0
      Defense: 50.0
      Sp. Atk: 50.0
      Sp. Def: 70.0
      Speed: 120
      Generation: 1
      Legendary: false
    - index: 57
      '#': 52
      Name: Meowth
      Type 1: Normal
      Type 2: null
      Total: 290
      HP: 40.0
      Attack: 45.0
      Defense: 35.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 58
      '#': 53
      Name: Persian
      Type 1: Normal
      Type 2: null
      Total: 440
      HP: 65.0
      Attack: 70.0
      Defense: 60.0
      Sp. Atk: 65.0
      Sp. Def: 65.0
      Speed: 115
      Generation: 1
      Legendary: false
    - index: 59
      '#': 54
      Name: Psyduck
      Type 1: Water
      Type 2: null
      Total: 320
      HP: 50.0
      Attack: 52.0
      Defense: 48.0
      Sp. Atk: 65.0
      Sp. Def: 50.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 60
      '#': 55
      Name: Golduck
      Type 1: Water
      Type 2: null
      Total: 500
      HP: 80.0
      Attack: 82.0
      Defense: 78.0
      Sp. Atk: 95.0
      Sp. Def: 80.0
      Speed: 85
      Generation: 1
      Legendary: false
    - index: 61
      '#': 56
      Name: Mankey
      Type 1: Fighting
      Type 2: null
      Total: 305
      HP: 40.0
      Attack: 80.0
      Defense: 35.0
      Sp. Atk: 35.0
      Sp. Def: 45.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 62
      '#': 57
      Name: Primeape
      Type 1: Fighting
      Type 2: null
      Total: 455
      HP: 65.0
      Attack: 105.0
      Defense: 60.0
      Sp. Atk: 60.0
      Sp. Def: 70.0
      Speed: 95
      Generation: 1
      Legendary: false
    - index: 63
      '#': 58
      Name: Growlithe
      Type 1: Fire
      Type 2: null
      Total: 350
      HP: 55.0
      Attack: 70.0
      Defense: 45.0
      Sp. Atk: 70.0
      Sp. Def: 50.0
      Speed: 60
      Generation: 1
      Legendary: false
    - index: 64
      '#': 59
      Name: Arcanine
      Type 1: Fire
      Type 2: null
      Total: 555
      HP: 90.0
      Attack: 110.0
      Defense: 80.0
      Sp. Atk: 100.0
      Sp. Def: 80.0
      Speed: 95
      Generation: 1
      Legendary: false
    - index: 65
      '#': 60
      Name: Poliwag
      Type 1: Water
      Type 2: null
      Total: 300
      HP: 40.0
      Attack: 50.0
      Defense: 40.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 66
      '#': 61
      Name: Poliwhirl
      Type 1: Water
      Type 2: null
      Total: 385
      HP: 65.0
      Attack: 65.0
      Defense: 65.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 67
      '#': 62
      Name: Poliwrath
      Type 1: Water
      Type 2: Fighting
      Total: 510
      HP: 90.0
      Attack: 95.0
      Defense: 95.0
      Sp. Atk: 70.0
      Sp. Def: 90.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 68
      '#': 63
      Name: Abra
      Type 1: Psychic
      Type 2: null
      Total: 310
      HP: 25.0
      Attack: 20.0
      Defense: 15.0
      Sp. Atk: 105.0
      Sp. Def: 55.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 69
      '#': 64
      Name: Kadabra
      Type 1: Psychic
      Type 2: null
      Total: 400
      HP: 40.0
      Attack: 35.0
      Defense: 30.0
      Sp. Atk: 120.0
      Sp. Def: 70.0
      Speed: 105
      Generation: 1
      Legendary: false
    - index: 70
      '#': 65
      Name: Alakazam
      Type 1: Psychic
      Type 2: null
      Total: 500
      HP: 55.0
      Attack: 50.0
      Defense: 45.0
      Sp. Atk: 135.0
      Sp. Def: 95.0
      Speed: 120
      Generation: 1
      Legendary: false
    - index: 71
      '#': 65
      Name: AlakazamMega Alakazam
      Type 1: Psychic
      Type 2: null
      Total: 590
      HP: 55.0
      Attack: 50.0
      Defense: 65.0
      Sp. Atk: 175.0
      Sp. Def: 95.0
      Speed: 150
      Generation: 1
      Legendary: false
    - index: 72
      '#': 66
      Name: Machop
      Type 1: Fighting
      Type 2: null
      Total: 305
      HP: 70.0
      Attack: 80.0
      Defense: 50.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 35
      Generation: 1
      Legendary: false
    - index: 73
      '#': 67
      Name: Machoke
      Type 1: Fighting
      Type 2: null
      Total: 405
      HP: 80.0
      Attack: 100.0
      Defense: 70.0
      Sp. Atk: 50.0
      Sp. Def: 60.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 74
      '#': 68
      Name: Machamp
      Type 1: Fighting
      Type 2: null
      Total: 505
      HP: 90.0
      Attack: 130.0
      Defense: 80.0
      Sp. Atk: 65.0
      Sp. Def: 85.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 75
      '#': 69
      Name: Bellsprout
      Type 1: Grass
      Type 2: Poison
      Total: 300
      HP: 50.0
      Attack: 75.0
      Defense: 35.0
      Sp. Atk: 70.0
      Sp. Def: 30.0
      Speed: 40
      Generation: 1
      Legendary: false
    - index: 76
      '#': 70
      Name: Weepinbell
      Type 1: Grass
      Type 2: Poison
      Total: 390
      HP: 65.0
      Attack: 90.0
      Defense: 50.0
      Sp. Atk: 85.0
      Sp. Def: 45.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 77
      '#': 71
      Name: Victreebel
      Type 1: Grass
      Type 2: Poison
      Total: 490
      HP: 80.0
      Attack: 105.0
      Defense: 65.0
      Sp. Atk: 100.0
      Sp. Def: 70.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 78
      '#': 72
      Name: Tentacool
      Type 1: Water
      Type 2: Poison
      Total: 335
      HP: 40.0
      Attack: 40.0
      Defense: 35.0
      Sp. Atk: 50.0
      Sp. Def: 100.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 79
      '#': 73
      Name: Tentacruel
      Type 1: Water
      Type 2: Poison
      Total: 515
      HP: 80.0
      Attack: 70.0
      Defense: 65.0
      Sp. Atk: 80.0
      Sp. Def: 120.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 80
      '#': 74
      Name: Geodude
      Type 1: Rock
      Type 2: Ground
      Total: 300
      HP: 40.0
      Attack: 80.0
      Defense: 100.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 20
      Generation: 1
      Legendary: false
    - index: 81
      '#': 75
      Name: Graveler
      Type 1: Rock
      Type 2: Ground
      Total: 390
      HP: 55.0
      Attack: 95.0
      Defense: 115.0
      Sp. Atk: 45.0
      Sp. Def: 45.0
      Speed: 35
      Generation: 1
      Legendary: false
    - index: 82
      '#': 76
      Name: Golem
      Type 1: Rock
      Type 2: Ground
      Total: 495
      HP: 80.0
      Attack: 120.0
      Defense: 130.0
      Sp. Atk: 55.0
      Sp. Def: 65.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 83
      '#': 77
      Name: Ponyta
      Type 1: Fire
      Type 2: null
      Total: 410
      HP: 50.0
      Attack: 85.0
      Defense: 55.0
      Sp. Atk: 65.0
      Sp. Def: 65.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 84
      '#': 78
      Name: Rapidash
      Type 1: Fire
      Type 2: null
      Total: 500
      HP: 65.0
      Attack: 100.0
      Defense: 70.0
      Sp. Atk: 80.0
      Sp. Def: 80.0
      Speed: 105
      Generation: 1
      Legendary: false
    - index: 85
      '#': 79
      Name: Slowpoke
      Type 1: Water
      Type 2: Psychic
      Total: 315
      HP: 90.0
      Attack: 65.0
      Defense: 65.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 15
      Generation: 1
      Legendary: false
    - index: 86
      '#': 80
      Name: Slowbro
      Type 1: Water
      Type 2: Psychic
      Total: 490
      HP: 95.0
      Attack: 75.0
      Defense: 110.0
      Sp. Atk: 100.0
      Sp. Def: 80.0
      Speed: 30
      Generation: 1
      Legendary: false
    - index: 87
      '#': 80
      Name: SlowbroMega Slowbro
      Type 1: Water
      Type 2: Psychic
      Total: 590
      HP: 95.0
      Attack: 75.0
      Defense: 180.0
      Sp. Atk: 130.0
      Sp. Def: 80.0
      Speed: 30
      Generation: 1
      Legendary: false
    - index: 88
      '#': 81
      Name: Magnemite
      Type 1: Electric
      Type 2: Steel
      Total: 325
      HP: 25.0
      Attack: 35.0
      Defense: 70.0
      Sp. Atk: 95.0
      Sp. Def: 55.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 89
      '#': 82
      Name: Magneton
      Type 1: Electric
      Type 2: Steel
      Total: 465
      HP: 50.0
      Attack: 60.0
      Defense: 95.0
      Sp. Atk: 120.0
      Sp. Def: 70.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 90
      '#': 83
      Name: Farfetch'd
      Type 1: Normal
      Type 2: Flying
      Total: 352
      HP: 52.0
      Attack: 65.0
      Defense: 55.0
      Sp. Atk: 58.0
      Sp. Def: 62.0
      Speed: 60
      Generation: 1
      Legendary: false
    - index: 91
      '#': 84
      Name: Doduo
      Type 1: Normal
      Type 2: Flying
      Total: 310
      HP: 35.0
      Attack: 85.0
      Defense: 45.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 75
      Generation: 1
      Legendary: false
    - index: 92
      '#': 85
      Name: Dodrio
      Type 1: Normal
      Type 2: Flying
      Total: 460
      HP: 60.0
      Attack: 110.0
      Defense: 70.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 93
      '#': 86
      Name: Seel
      Type 1: Water
      Type 2: null
      Total: 325
      HP: 65.0
      Attack: 45.0
      Defense: 55.0
      Sp. Atk: 45.0
      Sp. Def: 70.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 94
      '#': 87
      Name: Dewgong
      Type 1: Water
      Type 2: Ice
      Total: 475
      HP: 90.0
      Attack: 70.0
      Defense: 80.0
      Sp. Atk: 70.0
      Sp. Def: 95.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 95
      '#': 88
      Name: Grimer
      Type 1: Poison
      Type 2: null
      Total: 325
      HP: 80.0
      Attack: 80.0
      Defense: 50.0
      Sp. Atk: 40.0
      Sp. Def: 50.0
      Speed: 25
      Generation: 1
      Legendary: false
    - index: 96
      '#': 89
      Name: Muk
      Type 1: Poison
      Type 2: null
      Total: 500
      HP: 105.0
      Attack: 105.0
      Defense: 75.0
      Sp. Atk: 65.0
      Sp. Def: 100.0
      Speed: 50
      Generation: 1
      Legendary: false
    - index: 97
      '#': 90
      Name: Shellder
      Type 1: Water
      Type 2: null
      Total: 305
      HP: 30.0
      Attack: 65.0
      Defense: 100.0
      Sp. Atk: 45.0
      Sp. Def: 25.0
      Speed: 40
      Generation: 1
      Legendary: false
    - index: 98
      '#': 91
      Name: Cloyster
      Type 1: Water
      Type 2: Ice
      Total: 525
      HP: 50.0
      Attack: 95.0
      Defense: 180.0
      Sp. Atk: 85.0
      Sp. Def: 45.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 99
      '#': 92
      Name: Gastly
      Type 1: Ghost
      Type 2: Poison
      Total: 310
      HP: 30.0
      Attack: 35.0
      Defense: 30.0
      Sp. Atk: 100.0
      Sp. Def: 35.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 100
      '#': 93
      Name: Haunter
      Type 1: Ghost
      Type 2: Poison
      Total: 405
      HP: 45.0
      Attack: 50.0
      Defense: 45.0
      Sp. Atk: 115.0
      Sp. Def: 55.0
      Speed: 95
      Generation: 1
      Legendary: false
    - index: 101
      '#': 94
      Name: Gengar
      Type 1: Ghost
      Type 2: Poison
      Total: 500
      HP: 60.0
      Attack: 65.0
      Defense: 60.0
      Sp. Atk: 130.0
      Sp. Def: 75.0
      Speed: 110
      Generation: 1
      Legendary: false
    - index: 102
      '#': 94
      Name: GengarMega Gengar
      Type 1: Ghost
      Type 2: Poison
      Total: 600
      HP: 60.0
      Attack: 65.0
      Defense: 80.0
      Sp. Atk: 170.0
      Sp. Def: 95.0
      Speed: 130
      Generation: 1
      Legendary: false
    - index: 103
      '#': 95
      Name: Onix
      Type 1: Rock
      Type 2: Ground
      Total: 385
      HP: 35.0
      Attack: 45.0
      Defense: 160.0
      Sp. Atk: 30.0
      Sp. Def: 45.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 104
      '#': 96
      Name: Drowzee
      Type 1: Psychic
      Type 2: null
      Total: 328
      HP: 60.0
      Attack: 48.0
      Defense: 45.0
      Sp. Atk: 43.0
      Sp. Def: 90.0
      Speed: 42
      Generation: 1
      Legendary: false
    - index: 105
      '#': 97
      Name: Hypno
      Type 1: Psychic
      Type 2: null
      Total: 483
      HP: 85.0
      Attack: 73.0
      Defense: 70.0
      Sp. Atk: 73.0
      Sp. Def: 115.0
      Speed: 67
      Generation: 1
      Legendary: false
    - index: 106
      '#': 98
      Name: Krabby
      Type 1: Water
      Type 2: null
      Total: 325
      HP: 30.0
      Attack: 105.0
      Defense: 90.0
      Sp. Atk: 25.0
      Sp. Def: 25.0
      Speed: 50
      Generation: 1
      Legendary: false
    - index: 107
      '#': 99
      Name: Kingler
      Type 1: Water
      Type 2: null
      Total: 475
      HP: 55.0
      Attack: 130.0
      Defense: 115.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 75
      Generation: 1
      Legendary: false
    - index: 108
      '#': 100
      Name: Voltorb
      Type 1: Electric
      Type 2: null
      Total: 330
      HP: 40.0
      Attack: 30.0
      Defense: 50.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 109
      '#': 101
      Name: Electrode
      Type 1: Electric
      Type 2: null
      Total: 480
      HP: 60.0
      Attack: 50.0
      Defense: 70.0
      Sp. Atk: 80.0
      Sp. Def: 80.0
      Speed: 140
      Generation: 1
      Legendary: false
    - index: 110
      '#': 102
      Name: Exeggcute
      Type 1: Grass
      Type 2: Psychic
      Total: 325
      HP: 60.0
      Attack: 40.0
      Defense: 80.0
      Sp. Atk: 60.0
      Sp. Def: 45.0
      Speed: 40
      Generation: 1
      Legendary: false
    - index: 111
      '#': 103
      Name: Exeggutor
      Type 1: Grass
      Type 2: Psychic
      Total: 520
      HP: 95.0
      Attack: 95.0
      Defense: 85.0
      Sp. Atk: 125.0
      Sp. Def: 65.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 112
      '#': 104
      Name: Cubone
      Type 1: Ground
      Type 2: null
      Total: 320
      HP: 50.0
      Attack: 50.0
      Defense: 95.0
      Sp. Atk: 40.0
      Sp. Def: 50.0
      Speed: 35
      Generation: 1
      Legendary: false
    - index: 113
      '#': 105
      Name: Marowak
      Type 1: Ground
      Type 2: null
      Total: 425
      HP: 60.0
      Attack: 80.0
      Defense: 110.0
      Sp. Atk: 50.0
      Sp. Def: 80.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 114
      '#': 106
      Name: Hitmonlee
      Type 1: Fighting
      Type 2: null
      Total: 455
      HP: 50.0
      Attack: 120.0
      Defense: 53.0
      Sp. Atk: 35.0
      Sp. Def: 110.0
      Speed: 87
      Generation: 1
      Legendary: false
    - index: 115
      '#': 107
      Name: Hitmonchan
      Type 1: Fighting
      Type 2: null
      Total: 455
      HP: 50.0
      Attack: 105.0
      Defense: 79.0
      Sp. Atk: 35.0
      Sp. Def: 110.0
      Speed: 76
      Generation: 1
      Legendary: false
    - index: 116
      '#': 108
      Name: Lickitung
      Type 1: Normal
      Type 2: null
      Total: 385
      HP: 90.0
      Attack: 55.0
      Defense: 75.0
      Sp. Atk: 60.0
      Sp. Def: 75.0
      Speed: 30
      Generation: 1
      Legendary: false
    - index: 117
      '#': 109
      Name: Koffing
      Type 1: Poison
      Type 2: null
      Total: 340
      HP: 40.0
      Attack: 65.0
      Defense: 95.0
      Sp. Atk: 60.0
      Sp. Def: 45.0
      Speed: 35
      Generation: 1
      Legendary: false
    - index: 118
      '#': 110
      Name: Weezing
      Type 1: Poison
      Type 2: null
      Total: 490
      HP: 65.0
      Attack: 90.0
      Defense: 120.0
      Sp. Atk: 85.0
      Sp. Def: 70.0
      Speed: 60
      Generation: 1
      Legendary: false
    - index: 119
      '#': 111
      Name: Rhyhorn
      Type 1: Ground
      Type 2: Rock
      Total: 345
      HP: 80.0
      Attack: 85.0
      Defense: 95.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 25
      Generation: 1
      Legendary: false
    - index: 120
      '#': 112
      Name: Rhydon
      Type 1: Ground
      Type 2: Rock
      Total: 485
      HP: 105.0
      Attack: 130.0
      Defense: 120.0
      Sp. Atk: 45.0
      Sp. Def: 45.0
      Speed: 40
      Generation: 1
      Legendary: false
    - index: 121
      '#': 113
      Name: Chansey
      Type 1: Normal
      Type 2: null
      Total: 450
      HP: 250.0
      Attack: 5.0
      Defense: 5.0
      Sp. Atk: 35.0
      Sp. Def: 105.0
      Speed: 50
      Generation: 1
      Legendary: false
    - index: 122
      '#': 114
      Name: Tangela
      Type 1: Grass
      Type 2: null
      Total: 435
      HP: 65.0
      Attack: 55.0
      Defense: 115.0
      Sp. Atk: 100.0
      Sp. Def: 40.0
      Speed: 60
      Generation: 1
      Legendary: false
    - index: 123
      '#': 115
      Name: Kangaskhan
      Type 1: Normal
      Type 2: null
      Total: 490
      HP: 105.0
      Attack: 95.0
      Defense: 80.0
      Sp. Atk: 40.0
      Sp. Def: 80.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 124
      '#': 115
      Name: KangaskhanMega Kangaskhan
      Type 1: Normal
      Type 2: null
      Total: 590
      HP: 105.0
      Attack: 125.0
      Defense: 100.0
      Sp. Atk: 60.0
      Sp. Def: 100.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 125
      '#': 116
      Name: Horsea
      Type 1: Water
      Type 2: null
      Total: 295
      HP: 30.0
      Attack: 40.0
      Defense: 70.0
      Sp. Atk: 70.0
      Sp. Def: 25.0
      Speed: 60
      Generation: 1
      Legendary: false
    - index: 126
      '#': 117
      Name: Seadra
      Type 1: Water
      Type 2: null
      Total: 440
      HP: 55.0
      Attack: 65.0
      Defense: 95.0
      Sp. Atk: 95.0
      Sp. Def: 45.0
      Speed: 85
      Generation: 1
      Legendary: false
    - index: 127
      '#': 118
      Name: Goldeen
      Type 1: Water
      Type 2: null
      Total: 320
      HP: 45.0
      Attack: 67.0
      Defense: 60.0
      Sp. Atk: 35.0
      Sp. Def: 50.0
      Speed: 63
      Generation: 1
      Legendary: false
    - index: 128
      '#': 119
      Name: Seaking
      Type 1: Water
      Type 2: null
      Total: 450
      HP: 80.0
      Attack: 92.0
      Defense: 65.0
      Sp. Atk: 65.0
      Sp. Def: 80.0
      Speed: 68
      Generation: 1
      Legendary: false
    - index: 129
      '#': 120
      Name: Staryu
      Type 1: Water
      Type 2: null
      Total: 340
      HP: 30.0
      Attack: 45.0
      Defense: 55.0
      Sp. Atk: 70.0
      Sp. Def: 55.0
      Speed: 85
      Generation: 1
      Legendary: false
    - index: 130
      '#': 121
      Name: Starmie
      Type 1: Water
      Type 2: Psychic
      Total: 520
      HP: 60.0
      Attack: 75.0
      Defense: 85.0
      Sp. Atk: 100.0
      Sp. Def: 85.0
      Speed: 115
      Generation: 1
      Legendary: false
    - index: 131
      '#': 122
      Name: Mr. Mime
      Type 1: Psychic
      Type 2: Fairy
      Total: 460
      HP: 40.0
      Attack: 45.0
      Defense: 65.0
      Sp. Atk: 100.0
      Sp. Def: 120.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 132
      '#': 123
      Name: Scyther
      Type 1: Bug
      Type 2: Flying
      Total: 500
      HP: 70.0
      Attack: 110.0
      Defense: 80.0
      Sp. Atk: 55.0
      Sp. Def: 80.0
      Speed: 105
      Generation: 1
      Legendary: false
    - index: 133
      '#': 124
      Name: Jynx
      Type 1: Ice
      Type 2: Psychic
      Total: 455
      HP: 65.0
      Attack: 50.0
      Defense: 35.0
      Sp. Atk: 115.0
      Sp. Def: 95.0
      Speed: 95
      Generation: 1
      Legendary: false
    - index: 134
      '#': 125
      Name: Electabuzz
      Type 1: Electric
      Type 2: null
      Total: 490
      HP: 65.0
      Attack: 83.0
      Defense: 57.0
      Sp. Atk: 95.0
      Sp. Def: 85.0
      Speed: 105
      Generation: 1
      Legendary: false
    - index: 135
      '#': 126
      Name: Magmar
      Type 1: Fire
      Type 2: null
      Total: 495
      HP: 65.0
      Attack: 95.0
      Defense: 57.0
      Sp. Atk: 100.0
      Sp. Def: 85.0
      Speed: 93
      Generation: 1
      Legendary: false
    - index: 136
      '#': 127
      Name: Pinsir
      Type 1: Bug
      Type 2: null
      Total: 500
      HP: 65.0
      Attack: 125.0
      Defense: 100.0
      Sp. Atk: 55.0
      Sp. Def: 70.0
      Speed: 85
      Generation: 1
      Legendary: false
    - index: 137
      '#': 127
      Name: PinsirMega Pinsir
      Type 1: Bug
      Type 2: Flying
      Total: 600
      HP: 65.0
      Attack: 155.0
      Defense: 120.0
      Sp. Atk: 65.0
      Sp. Def: 90.0
      Speed: 105
      Generation: 1
      Legendary: false
    - index: 138
      '#': 128
      Name: Tauros
      Type 1: Normal
      Type 2: null
      Total: 490
      HP: 75.0
      Attack: 100.0
      Defense: 95.0
      Sp. Atk: 40.0
      Sp. Def: 70.0
      Speed: 110
      Generation: 1
      Legendary: false
    - index: 139
      '#': 129
      Name: Magikarp
      Type 1: Water
      Type 2: null
      Total: 200
      HP: 20.0
      Attack: 10.0
      Defense: 55.0
      Sp. Atk: 15.0
      Sp. Def: 20.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 140
      '#': 130
      Name: Gyarados
      Type 1: Water
      Type 2: Flying
      Total: 540
      HP: 95.0
      Attack: 125.0
      Defense: 79.0
      Sp. Atk: 60.0
      Sp. Def: 100.0
      Speed: 81
      Generation: 1
      Legendary: false
    - index: 141
      '#': 130
      Name: GyaradosMega Gyarados
      Type 1: Water
      Type 2: Dark
      Total: 640
      HP: 95.0
      Attack: 155.0
      Defense: 109.0
      Sp. Atk: 70.0
      Sp. Def: 130.0
      Speed: 81
      Generation: 1
      Legendary: false
    - index: 142
      '#': 131
      Name: Lapras
      Type 1: Water
      Type 2: Ice
      Total: 535
      HP: 130.0
      Attack: 85.0
      Defense: 80.0
      Sp. Atk: 85.0
      Sp. Def: 95.0
      Speed: 60
      Generation: 1
      Legendary: false
    - index: 143
      '#': 132
      Name: Ditto
      Type 1: Normal
      Type 2: null
      Total: 288
      HP: 48.0
      Attack: 48.0
      Defense: 48.0
      Sp. Atk: 48.0
      Sp. Def: 48.0
      Speed: 48
      Generation: 1
      Legendary: false
    - index: 144
      '#': 133
      Name: Eevee
      Type 1: Normal
      Type 2: null
      Total: 325
      HP: 55.0
      Attack: 55.0
      Defense: 50.0
      Sp. Atk: 45.0
      Sp. Def: 65.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 145
      '#': 134
      Name: Vaporeon
      Type 1: Water
      Type 2: null
      Total: 525
      HP: 130.0
      Attack: 65.0
      Defense: 60.0
      Sp. Atk: 110.0
      Sp. Def: 95.0
      Speed: 65
      Generation: 1
      Legendary: false
    - index: 146
      '#': 135
      Name: Jolteon
      Type 1: Electric
      Type 2: null
      Total: 525
      HP: 65.0
      Attack: 65.0
      Defense: 60.0
      Sp. Atk: 110.0
      Sp. Def: 95.0
      Speed: 130
      Generation: 1
      Legendary: false
    - index: 147
      '#': 136
      Name: Flareon
      Type 1: Fire
      Type 2: null
      Total: 525
      HP: 65.0
      Attack: 130.0
      Defense: 60.0
      Sp. Atk: 95.0
      Sp. Def: 110.0
      Speed: 65
      Generation: 1
      Legendary: false
    - index: 148
      '#': 137
      Name: Porygon
      Type 1: Normal
      Type 2: null
      Total: 395
      HP: 65.0
      Attack: 60.0
      Defense: 70.0
      Sp. Atk: 85.0
      Sp. Def: 75.0
      Speed: 40
      Generation: 1
      Legendary: false
    - index: 149
      '#': 138
      Name: Omanyte
      Type 1: Rock
      Type 2: Water
      Total: 355
      HP: 35.0
      Attack: 40.0
      Defense: 100.0
      Sp. Atk: 90.0
      Sp. Def: 55.0
      Speed: 35
      Generation: 1
      Legendary: false
    - index: 150
      '#': 139
      Name: Omastar
      Type 1: Rock
      Type 2: Water
      Total: 495
      HP: 70.0
      Attack: 60.0
      Defense: 125.0
      Sp. Atk: 115.0
      Sp. Def: 70.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 151
      '#': 140
      Name: Kabuto
      Type 1: Rock
      Type 2: Water
      Total: 355
      HP: 30.0
      Attack: 80.0
      Defense: 90.0
      Sp. Atk: 55.0
      Sp. Def: 45.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 152
      '#': 141
      Name: Kabutops
      Type 1: Rock
      Type 2: Water
      Total: 495
      HP: 60.0
      Attack: 115.0
      Defense: 105.0
      Sp. Atk: 65.0
      Sp. Def: 70.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 153
      '#': 142
      Name: Aerodactyl
      Type 1: Rock
      Type 2: Flying
      Total: 515
      HP: 80.0
      Attack: 105.0
      Defense: 65.0
      Sp. Atk: 60.0
      Sp. Def: 75.0
      Speed: 130
      Generation: 1
      Legendary: false
    - index: 154
      '#': 142
      Name: AerodactylMega Aerodactyl
      Type 1: Rock
      Type 2: Flying
      Total: 615
      HP: 80.0
      Attack: 135.0
      Defense: 85.0
      Sp. Atk: 70.0
      Sp. Def: 95.0
      Speed: 150
      Generation: 1
      Legendary: false
    - index: 155
      '#': 143
      Name: Snorlax
      Type 1: Normal
      Type 2: null
      Total: 540
      HP: 160.0
      Attack: 110.0
      Defense: 65.0
      Sp. Atk: 65.0
      Sp. Def: 110.0
      Speed: 30
      Generation: 1
      Legendary: false
    - index: 156
      '#': 144
      Name: Articuno
      Type 1: Ice
      Type 2: Flying
      Total: 580
      HP: 90.0
      Attack: 85.0
      Defense: 100.0
      Sp. Atk: 95.0
      Sp. Def: 125.0
      Speed: 85
      Generation: 1
      Legendary: true
    - index: 157
      '#': 145
      Name: Zapdos
      Type 1: Electric
      Type 2: Flying
      Total: 580
      HP: 90.0
      Attack: 90.0
      Defense: 85.0
      Sp. Atk: 125.0
      Sp. Def: 90.0
      Speed: 100
      Generation: 1
      Legendary: true
    - index: 158
      '#': 146
      Name: Moltres
      Type 1: Fire
      Type 2: Flying
      Total: 580
      HP: 90.0
      Attack: 100.0
      Defense: 90.0
      Sp. Atk: 125.0
      Sp. Def: 85.0
      Speed: 90
      Generation: 1
      Legendary: true
    - index: 159
      '#': 147
      Name: Dratini
      Type 1: Dragon
      Type 2: null
      Total: 300
      HP: 41.0
      Attack: 64.0
      Defense: 45.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 50
      Generation: 1
      Legendary: false
    - index: 160
      '#': 148
      Name: Dragonair
      Type 1: Dragon
      Type 2: null
      Total: 420
      HP: 61.0
      Attack: 84.0
      Defense: 65.0
      Sp. Atk: 70.0
      Sp. Def: 70.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 161
      '#': 149
      Name: Dragonite
      Type 1: Dragon
      Type 2: Flying
      Total: 600
      HP: 91.0
      Attack: 134.0
      Defense: 95.0
      Sp. Atk: 100.0
      Sp. Def: 100.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 162
      '#': 150
      Name: Mewtwo
      Type 1: Psychic
      Type 2: null
      Total: 680
      HP: 106.0
      Attack: 110.0
      Defense: 90.0
      Sp. Atk: 154.0
      Sp. Def: 90.0
      Speed: 130
      Generation: 1
      Legendary: true
    - index: 163
      '#': 150
      Name: MewtwoMega Mewtwo X
      Type 1: Psychic
      Type 2: Fighting
      Total: 780
      HP: 106.0
      Attack: 190.0
      Defense: 100.0
      Sp. Atk: 154.0
      Sp. Def: 100.0
      Speed: 130
      Generation: 1
      Legendary: true
    - index: 164
      '#': 150
      Name: MewtwoMega Mewtwo Y
      Type 1: Psychic
      Type 2: null
      Total: 780
      HP: 106.0
      Attack: 150.0
      Defense: 70.0
      Sp. Atk: 194.0
      Sp. Def: 120.0
      Speed: 140
      Generation: 1
      Legendary: true
    - index: 165
      '#': 151
      Name: Mew
      Type 1: Psychic
      Type 2: null
      Total: 600
      HP: 100.0
      Attack: 100.0
      Defense: 100.0
      Sp. Atk: 100.0
      Sp. Def: 100.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 166
      '#': 152
      Name: Chikorita
      Type 1: Grass
      Type 2: null
      Total: 318
      HP: 45.0
      Attack: 49.0
      Defense: 65.0
      Sp. Atk: 49.0
      Sp. Def: 65.0
      Speed: 45
      Generation: 2
      Legendary: false
    - index: 167
      '#': 153
      Name: Bayleef
      Type 1: Grass
      Type 2: null
      Total: 405
      HP: 60.0
      Attack: 62.0
      Defense: 80.0
      Sp. Atk: 63.0
      Sp. Def: 80.0
      Speed: 60
      Generation: 2
      Legendary: false
    - index: 168
      '#': 154
      Name: Meganium
      Type 1: Grass
      Type 2: null
      Total: 525
      HP: 80.0
      Attack: 82.0
      Defense: 100.0
      Sp. Atk: 83.0
      Sp. Def: 100.0
      Speed: 80
      Generation: 2
      Legendary: false
    - index: 169
      '#': 155
      Name: Cyndaquil
      Type 1: Fire
      Type 2: null
      Total: 309
      HP: 39.0
      Attack: 52.0
      Defense: 43.0
      Sp. Atk: 60.0
      Sp. Def: 50.0
      Speed: 65
      Generation: 2
      Legendary: false
    - index: 170
      '#': 156
      Name: Quilava
      Type 1: Fire
      Type 2: null
      Total: 405
      HP: 58.0
      Attack: 64.0
      Defense: 58.0
      Sp. Atk: 80.0
      Sp. Def: 65.0
      Speed: 80
      Generation: 2
      Legendary: false
    - index: 171
      '#': 157
      Name: Typhlosion
      Type 1: Fire
      Type 2: null
      Total: 534
      HP: 78.0
      Attack: 84.0
      Defense: 78.0
      Sp. Atk: 109.0
      Sp. Def: 85.0
      Speed: 100
      Generation: 2
      Legendary: false
    - index: 172
      '#': 158
      Name: Totodile
      Type 1: Water
      Type 2: null
      Total: 314
      HP: 50.0
      Attack: 65.0
      Defense: 64.0
      Sp. Atk: 44.0
      Sp. Def: 48.0
      Speed: 43
      Generation: 2
      Legendary: false
    - index: 173
      '#': 159
      Name: Croconaw
      Type 1: Water
      Type 2: null
      Total: 405
      HP: 65.0
      Attack: 80.0
      Defense: 80.0
      Sp. Atk: 59.0
      Sp. Def: 63.0
      Speed: 58
      Generation: 2
      Legendary: false
    - index: 174
      '#': 160
      Name: Feraligatr
      Type 1: Water
      Type 2: null
      Total: 530
      HP: 85.0
      Attack: 105.0
      Defense: 100.0
      Sp. Atk: 79.0
      Sp. Def: 83.0
      Speed: 78
      Generation: 2
      Legendary: false
    - index: 175
      '#': 161
      Name: Sentret
      Type 1: Normal
      Type 2: null
      Total: 215
      HP: 35.0
      Attack: 46.0
      Defense: 34.0
      Sp. Atk: 35.0
      Sp. Def: 45.0
      Speed: 20
      Generation: 2
      Legendary: false
    - index: 176
      '#': 162
      Name: Furret
      Type 1: Normal
      Type 2: null
      Total: 415
      HP: 85.0
      Attack: 76.0
      Defense: 64.0
      Sp. Atk: 45.0
      Sp. Def: 55.0
      Speed: 90
      Generation: 2
      Legendary: false
    - index: 177
      '#': 163
      Name: Hoothoot
      Type 1: Normal
      Type 2: Flying
      Total: 262
      HP: 60.0
      Attack: 30.0
      Defense: 30.0
      Sp. Atk: 36.0
      Sp. Def: 56.0
      Speed: 50
      Generation: 2
      Legendary: false
    - index: 178
      '#': 164
      Name: Noctowl
      Type 1: Normal
      Type 2: Flying
      Total: 442
      HP: 100.0
      Attack: 50.0
      Defense: 50.0
      Sp. Atk: 76.0
      Sp. Def: 96.0
      Speed: 70
      Generation: 2
      Legendary: false
    - index: 179
      '#': 165
      Name: Ledyba
      Type 1: Bug
      Type 2: Flying
      Total: 265
      HP: 40.0
      Attack: 20.0
      Defense: 30.0
      Sp. Atk: 40.0
      Sp. Def: 80.0
      Speed: 55
      Generation: 2
      Legendary: false
    - index: 180
      '#': 166
      Name: Ledian
      Type 1: Bug
      Type 2: Flying
      Total: 390
      HP: 55.0
      Attack: 35.0
      Defense: 50.0
      Sp. Atk: 55.0
      Sp. Def: 110.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 181
      '#': 167
      Name: Spinarak
      Type 1: Bug
      Type 2: Poison
      Total: 250
      HP: 40.0
      Attack: 60.0
      Defense: 40.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 182
      '#': 168
      Name: Ariados
      Type 1: Bug
      Type 2: Poison
      Total: 390
      HP: 70.0
      Attack: 90.0
      Defense: 70.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 40
      Generation: 2
      Legendary: false
    - index: 183
      '#': 169
      Name: Crobat
      Type 1: Poison
      Type 2: Flying
      Total: 535
      HP: 85.0
      Attack: 90.0
      Defense: 80.0
      Sp. Atk: 70.0
      Sp. Def: 80.0
      Speed: 130
      Generation: 2
      Legendary: false
    - index: 184
      '#': 170
      Name: Chinchou
      Type 1: Water
      Type 2: Electric
      Total: 330
      HP: 75.0
      Attack: 38.0
      Defense: 38.0
      Sp. Atk: 56.0
      Sp. Def: 56.0
      Speed: 67
      Generation: 2
      Legendary: false
    - index: 185
      '#': 171
      Name: Lanturn
      Type 1: Water
      Type 2: Electric
      Total: 460
      HP: 125.0
      Attack: 58.0
      Defense: 58.0
      Sp. Atk: 76.0
      Sp. Def: 76.0
      Speed: 67
      Generation: 2
      Legendary: false
    - index: 186
      '#': 172
      Name: Pichu
      Type 1: Electric
      Type 2: null
      Total: 205
      HP: 20.0
      Attack: 40.0
      Defense: 15.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 60
      Generation: 2
      Legendary: false
    - index: 187
      '#': 173
      Name: Cleffa
      Type 1: Fairy
      Type 2: null
      Total: 218
      HP: 50.0
      Attack: 25.0
      Defense: 28.0
      Sp. Atk: 45.0
      Sp. Def: 55.0
      Speed: 15
      Generation: 2
      Legendary: false
    - index: 188
      '#': 174
      Name: Igglybuff
      Type 1: Normal
      Type 2: Fairy
      Total: 210
      HP: 90.0
      Attack: 30.0
      Defense: 15.0
      Sp. Atk: 40.0
      Sp. Def: 20.0
      Speed: 15
      Generation: 2
      Legendary: false
    - index: 189
      '#': 175
      Name: Togepi
      Type 1: Fairy
      Type 2: null
      Total: 245
      HP: 35.0
      Attack: 20.0
      Defense: 65.0
      Sp. Atk: 40.0
      Sp. Def: 65.0
      Speed: 20
      Generation: 2
      Legendary: false
    - index: 190
      '#': 176
      Name: Togetic
      Type 1: Fairy
      Type 2: Flying
      Total: 405
      HP: 55.0
      Attack: 40.0
      Defense: 85.0
      Sp. Atk: 80.0
      Sp. Def: 105.0
      Speed: 40
      Generation: 2
      Legendary: false
    - index: 191
      '#': 177
      Name: Natu
      Type 1: Psychic
      Type 2: Flying
      Total: 320
      HP: 40.0
      Attack: 50.0
      Defense: 45.0
      Sp. Atk: 70.0
      Sp. Def: 45.0
      Speed: 70
      Generation: 2
      Legendary: false
    - index: 192
      '#': 178
      Name: Xatu
      Type 1: Psychic
      Type 2: Flying
      Total: 470
      HP: 65.0
      Attack: 75.0
      Defense: 70.0
      Sp. Atk: 95.0
      Sp. Def: 70.0
      Speed: 95
      Generation: 2
      Legendary: false
    - index: 193
      '#': 179
      Name: Mareep
      Type 1: Electric
      Type 2: null
      Total: 280
      HP: 55.0
      Attack: 40.0
      Defense: 40.0
      Sp. Atk: 65.0
      Sp. Def: 45.0
      Speed: 35
      Generation: 2
      Legendary: false
    - index: 194
      '#': 180
      Name: Flaaffy
      Type 1: Electric
      Type 2: null
      Total: 365
      HP: 70.0
      Attack: 55.0
      Defense: 55.0
      Sp. Atk: 80.0
      Sp. Def: 60.0
      Speed: 45
      Generation: 2
      Legendary: false
    - index: 195
      '#': 181
      Name: Ampharos
      Type 1: Electric
      Type 2: null
      Total: 510
      HP: 90.0
      Attack: 75.0
      Defense: 85.0
      Sp. Atk: 115.0
      Sp. Def: 90.0
      Speed: 55
      Generation: 2
      Legendary: false
    - index: 196
      '#': 181
      Name: AmpharosMega Ampharos
      Type 1: Electric
      Type 2: Dragon
      Total: 610
      HP: 90.0
      Attack: 95.0
      Defense: 105.0
      Sp. Atk: 165.0
      Sp. Def: 110.0
      Speed: 45
      Generation: 2
      Legendary: false
    - index: 197
      '#': 182
      Name: Bellossom
      Type 1: Grass
      Type 2: null
      Total: 490
      HP: 75.0
      Attack: 80.0
      Defense: 95.0
      Sp. Atk: 90.0
      Sp. Def: 100.0
      Speed: 50
      Generation: 2
      Legendary: false
    - index: 198
      '#': 183
      Name: Marill
      Type 1: Water
      Type 2: Fairy
      Total: 250
      HP: 70.0
      Attack: 20.0
      Defense: 50.0
      Sp. Atk: 20.0
      Sp. Def: 50.0
      Speed: 40
      Generation: 2
      Legendary: false
    - index: 199
      '#': 184
      Name: Azumarill
      Type 1: Water
      Type 2: Fairy
      Total: 420
      HP: 100.0
      Attack: 50.0
      Defense: 80.0
      Sp. Atk: 60.0
      Sp. Def: 80.0
      Speed: 50
      Generation: 2
      Legendary: false
    - index: 200
      '#': 185
      Name: Sudowoodo
      Type 1: Rock
      Type 2: null
      Total: 410
      HP: 70.0
      Attack: 100.0
      Defense: 115.0
      Sp. Atk: 30.0
      Sp. Def: 65.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 201
      '#': 186
      Name: Politoed
      Type 1: Water
      Type 2: null
      Total: 500
      HP: 90.0
      Attack: 75.0
      Defense: 75.0
      Sp. Atk: 90.0
      Sp. Def: 100.0
      Speed: 70
      Generation: 2
      Legendary: false
    - index: 202
      '#': 187
      Name: Hoppip
      Type 1: Grass
      Type 2: Flying
      Total: 250
      HP: 35.0
      Attack: 35.0
      Defense: 40.0
      Sp. Atk: 35.0
      Sp. Def: 55.0
      Speed: 50
      Generation: 2
      Legendary: false
    - index: 203
      '#': 188
      Name: Skiploom
      Type 1: Grass
      Type 2: Flying
      Total: 340
      HP: 55.0
      Attack: 45.0
      Defense: 50.0
      Sp. Atk: 45.0
      Sp. Def: 65.0
      Speed: 80
      Generation: 2
      Legendary: false
    - index: 204
      '#': 189
      Name: Jumpluff
      Type 1: Grass
      Type 2: Flying
      Total: 460
      HP: 75.0
      Attack: 55.0
      Defense: 70.0
      Sp. Atk: 55.0
      Sp. Def: 95.0
      Speed: 110
      Generation: 2
      Legendary: false
    - index: 205
      '#': 190
      Name: Aipom
      Type 1: Normal
      Type 2: null
      Total: 360
      HP: 55.0
      Attack: 70.0
      Defense: 55.0
      Sp. Atk: 40.0
      Sp. Def: 55.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 206
      '#': 191
      Name: Sunkern
      Type 1: Grass
      Type 2: null
      Total: 180
      HP: 30.0
      Attack: 30.0
      Defense: 30.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 207
      '#': 192
      Name: Sunflora
      Type 1: Grass
      Type 2: null
      Total: 425
      HP: 75.0
      Attack: 75.0
      Defense: 55.0
      Sp. Atk: 105.0
      Sp. Def: 85.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 208
      '#': 193
      Name: Yanma
      Type 1: Bug
      Type 2: Flying
      Total: 390
      HP: 65.0
      Attack: 65.0
      Defense: 45.0
      Sp. Atk: 75.0
      Sp. Def: 45.0
      Speed: 95
      Generation: 2
      Legendary: false
    - index: 209
      '#': 194
      Name: Wooper
      Type 1: Water
      Type 2: Ground
      Total: 210
      HP: 55.0
      Attack: 45.0
      Defense: 45.0
      Sp. Atk: 25.0
      Sp. Def: 25.0
      Speed: 15
      Generation: 2
      Legendary: false
    - index: 210
      '#': 195
      Name: Quagsire
      Type 1: Water
      Type 2: Ground
      Total: 430
      HP: 95.0
      Attack: 85.0
      Defense: 85.0
      Sp. Atk: 65.0
      Sp. Def: 65.0
      Speed: 35
      Generation: 2
      Legendary: false
    - index: 211
      '#': 196
      Name: Espeon
      Type 1: Psychic
      Type 2: null
      Total: 525
      HP: 65.0
      Attack: 65.0
      Defense: 60.0
      Sp. Atk: 130.0
      Sp. Def: 95.0
      Speed: 110
      Generation: 2
      Legendary: false
    - index: 212
      '#': 197
      Name: Umbreon
      Type 1: Dark
      Type 2: null
      Total: 525
      HP: 95.0
      Attack: 65.0
      Defense: 110.0
      Sp. Atk: 60.0
      Sp. Def: 130.0
      Speed: 65
      Generation: 2
      Legendary: false
    - index: 213
      '#': 198
      Name: Murkrow
      Type 1: Dark
      Type 2: Flying
      Total: 405
      HP: 60.0
      Attack: 85.0
      Defense: 42.0
      Sp. Atk: 85.0
      Sp. Def: 42.0
      Speed: 91
      Generation: 2
      Legendary: false
    - index: 214
      '#': 199
      Name: Slowking
      Type 1: Water
      Type 2: Psychic
      Total: 490
      HP: 95.0
      Attack: 75.0
      Defense: 80.0
      Sp. Atk: 100.0
      Sp. Def: 110.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 215
      '#': 200
      Name: Misdreavus
      Type 1: Ghost
      Type 2: null
      Total: 435
      HP: 60.0
      Attack: 60.0
      Defense: 60.0
      Sp. Atk: 85.0
      Sp. Def: 85.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 216
      '#': 201
      Name: Unown
      Type 1: Psychic
      Type 2: null
      Total: 336
      HP: 48.0
      Attack: 72.0
      Defense: 48.0
      Sp. Atk: 72.0
      Sp. Def: 48.0
      Speed: 48
      Generation: 2
      Legendary: false
    - index: 217
      '#': 202
      Name: Wobbuffet
      Type 1: Psychic
      Type 2: null
      Total: 405
      HP: 190.0
      Attack: 33.0
      Defense: 58.0
      Sp. Atk: 33.0
      Sp. Def: 58.0
      Speed: 33
      Generation: 2
      Legendary: false
    - index: 218
      '#': 203
      Name: Girafarig
      Type 1: Normal
      Type 2: Psychic
      Total: 455
      HP: 70.0
      Attack: 80.0
      Defense: 65.0
      Sp. Atk: 90.0
      Sp. Def: 65.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 219
      '#': 204
      Name: Pineco
      Type 1: Bug
      Type 2: null
      Total: 290
      HP: 50.0
      Attack: 65.0
      Defense: 90.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 15
      Generation: 2
      Legendary: false
    - index: 220
      '#': 205
      Name: Forretress
      Type 1: Bug
      Type 2: Steel
      Total: 465
      HP: 75.0
      Attack: 90.0
      Defense: 140.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 40
      Generation: 2
      Legendary: false
    - index: 221
      '#': 206
      Name: Dunsparce
      Type 1: Normal
      Type 2: null
      Total: 415
      HP: 100.0
      Attack: 70.0
      Defense: 70.0
      Sp. Atk: 65.0
      Sp. Def: 65.0
      Speed: 45
      Generation: 2
      Legendary: false
    - index: 222
      '#': 207
      Name: Gligar
      Type 1: Ground
      Type 2: Flying
      Total: 430
      HP: 65.0
      Attack: 75.0
      Defense: 105.0
      Sp. Atk: 35.0
      Sp. Def: 65.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 223
      '#': 208
      Name: Steelix
      Type 1: Steel
      Type 2: Ground
      Total: 510
      HP: 75.0
      Attack: 85.0
      Defense: 200.0
      Sp. Atk: 55.0
      Sp. Def: 65.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 224
      '#': 208
      Name: SteelixMega Steelix
      Type 1: Steel
      Type 2: Ground
      Total: 610
      HP: 75.0
      Attack: 125.0
      Defense: 230.0
      Sp. Atk: 55.0
      Sp. Def: 95.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 225
      '#': 209
      Name: Snubbull
      Type 1: Fairy
      Type 2: null
      Total: 300
      HP: 60.0
      Attack: 80.0
      Defense: 50.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 226
      '#': 210
      Name: Granbull
      Type 1: Fairy
      Type 2: null
      Total: 450
      HP: 90.0
      Attack: 120.0
      Defense: 75.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 45
      Generation: 2
      Legendary: false
    - index: 227
      '#': 211
      Name: Qwilfish
      Type 1: Water
      Type 2: Poison
      Total: 430
      HP: 65.0
      Attack: 95.0
      Defense: 75.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 228
      '#': 212
      Name: Scizor
      Type 1: Bug
      Type 2: Steel
      Total: 500
      HP: 70.0
      Attack: 130.0
      Defense: 100.0
      Sp. Atk: 55.0
      Sp. Def: 80.0
      Speed: 65
      Generation: 2
      Legendary: false
    - index: 229
      '#': 212
      Name: ScizorMega Scizor
      Type 1: Bug
      Type 2: Steel
      Total: 600
      HP: 70.0
      Attack: 150.0
      Defense: 140.0
      Sp. Atk: 65.0
      Sp. Def: 100.0
      Speed: 75
      Generation: 2
      Legendary: false
    - index: 230
      '#': 213
      Name: Shuckle
      Type 1: Bug
      Type 2: Rock
      Total: 505
      HP: 20.0
      Attack: 10.0
      Defense: 230.0
      Sp. Atk: 10.0
      Sp. Def: 230.0
      Speed: 5
      Generation: 2
      Legendary: false
    - index: 231
      '#': 214
      Name: Heracross
      Type 1: Bug
      Type 2: Fighting
      Total: 500
      HP: 80.0
      Attack: 125.0
      Defense: 75.0
      Sp. Atk: 40.0
      Sp. Def: 95.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 232
      '#': 214
      Name: HeracrossMega Heracross
      Type 1: Bug
      Type 2: Fighting
      Total: 600
      HP: 80.0
      Attack: 185.0
      Defense: 115.0
      Sp. Atk: 40.0
      Sp. Def: 105.0
      Speed: 75
      Generation: 2
      Legendary: false
    - index: 233
      '#': 215
      Name: Sneasel
      Type 1: Dark
      Type 2: Ice
      Total: 430
      HP: 55.0
      Attack: 95.0
      Defense: 55.0
      Sp. Atk: 35.0
      Sp. Def: 75.0
      Speed: 115
      Generation: 2
      Legendary: false
    - index: 234
      '#': 216
      Name: Teddiursa
      Type 1: Normal
      Type 2: null
      Total: 330
      HP: 60.0
      Attack: 80.0
      Defense: 50.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 40
      Generation: 2
      Legendary: false
    - index: 235
      '#': 217
      Name: Ursaring
      Type 1: Normal
      Type 2: null
      Total: 500
      HP: 90.0
      Attack: 130.0
      Defense: 75.0
      Sp. Atk: 75.0
      Sp. Def: 75.0
      Speed: 55
      Generation: 2
      Legendary: false
    - index: 236
      '#': 218
      Name: Slugma
      Type 1: Fire
      Type 2: null
      Total: 250
      HP: 40.0
      Attack: 40.0
      Defense: 40.0
      Sp. Atk: 70.0
      Sp. Def: 40.0
      Speed: 20
      Generation: 2
      Legendary: false
    - index: 237
      '#': 219
      Name: Magcargo
      Type 1: Fire
      Type 2: Rock
      Total: 410
      HP: 50.0
      Attack: 50.0
      Defense: 120.0
      Sp. Atk: 80.0
      Sp. Def: 80.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 238
      '#': 220
      Name: Swinub
      Type 1: Ice
      Type 2: Ground
      Total: 250
      HP: 50.0
      Attack: 50.0
      Defense: 40.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 50
      Generation: 2
      Legendary: false
    - index: 239
      '#': 221
      Name: Piloswine
      Type 1: Ice
      Type 2: Ground
      Total: 450
      HP: 100.0
      Attack: 100.0
      Defense: 80.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 50
      Generation: 2
      Legendary: false
    - index: 240
      '#': 222
      Name: Corsola
      Type 1: Water
      Type 2: Rock
      Total: 380
      HP: 55.0
      Attack: 55.0
      Defense: 85.0
      Sp. Atk: 65.0
      Sp. Def: 85.0
      Speed: 35
      Generation: 2
      Legendary: false
    - index: 241
      '#': 223
      Name: Remoraid
      Type 1: Water
      Type 2: null
      Total: 300
      HP: 35.0
      Attack: 65.0
      Defense: 35.0
      Sp. Atk: 65.0
      Sp. Def: 35.0
      Speed: 65
      Generation: 2
      Legendary: false
    - index: 242
      '#': 224
      Name: Octillery
      Type 1: Water
      Type 2: null
      Total: 480
      HP: 75.0
      Attack: 105.0
      Defense: 75.0
      Sp. Atk: 105.0
      Sp. Def: 75.0
      Speed: 45
      Generation: 2
      Legendary: false
    - index: 243
      '#': 225
      Name: Delibird
      Type 1: Ice
      Type 2: Flying
      Total: 330
      HP: 45.0
      Attack: 55.0
      Defense: 45.0
      Sp. Atk: 65.0
      Sp. Def: 45.0
      Speed: 75
      Generation: 2
      Legendary: false
    - index: 244
      '#': 226
      Name: Mantine
      Type 1: Water
      Type 2: Flying
      Total: 465
      HP: 65.0
      Attack: 40.0
      Defense: 70.0
      Sp. Atk: 80.0
      Sp. Def: 140.0
      Speed: 70
      Generation: 2
      Legendary: false
    - index: 245
      '#': 227
      Name: Skarmory
      Type 1: Steel
      Type 2: Flying
      Total: 465
      HP: 65.0
      Attack: 80.0
      Defense: 140.0
      Sp. Atk: 40.0
      Sp. Def: 70.0
      Speed: 70
      Generation: 2
      Legendary: false
    - index: 246
      '#': 228
      Name: Houndour
      Type 1: Dark
      Type 2: Fire
      Total: 330
      HP: 45.0
      Attack: 60.0
      Defense: 30.0
      Sp. Atk: 80.0
      Sp. Def: 50.0
      Speed: 65
      Generation: 2
      Legendary: false
    - index: 247
      '#': 229
      Name: Houndoom
      Type 1: Dark
      Type 2: Fire
      Total: 500
      HP: 75.0
      Attack: 90.0
      Defense: 50.0
      Sp. Atk: 110.0
      Sp. Def: 80.0
      Speed: 95
      Generation: 2
      Legendary: false
    - index: 248
      '#': 229
      Name: HoundoomMega Houndoom
      Type 1: Dark
      Type 2: Fire
      Total: 600
      HP: 75.0
      Attack: 90.0
      Defense: 90.0
      Sp. Atk: 140.0
      Sp. Def: 90.0
      Speed: 115
      Generation: 2
      Legendary: false
    - index: 249
      '#': 230
      Name: Kingdra
      Type 1: Water
      Type 2: Dragon
      Total: 540
      HP: 75.0
      Attack: 95.0
      Defense: 95.0
      Sp. Atk: 95.0
      Sp. Def: 95.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 250
      '#': 231
      Name: Phanpy
      Type 1: Ground
      Type 2: null
      Total: 330
      HP: 90.0
      Attack: 60.0
      Defense: 60.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 40
      Generation: 2
      Legendary: false
    - index: 251
      '#': 232
      Name: Donphan
      Type 1: Ground
      Type 2: null
      Total: 500
      HP: 90.0
      Attack: 120.0
      Defense: 120.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 50
      Generation: 2
      Legendary: false
    - index: 252
      '#': 233
      Name: Porygon2
      Type 1: Normal
      Type 2: null
      Total: 515
      HP: 85.0
      Attack: 80.0
      Defense: 90.0
      Sp. Atk: 105.0
      Sp. Def: 95.0
      Speed: 60
      Generation: 2
      Legendary: false
    - index: 253
      '#': 234
      Name: Stantler
      Type 1: Normal
      Type 2: null
      Total: 465
      HP: 73.0
      Attack: 95.0
      Defense: 62.0
      Sp. Atk: 85.0
      Sp. Def: 65.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 254
      '#': 235
      Name: Smeargle
      Type 1: Normal
      Type 2: null
      Total: 250
      HP: 55.0
      Attack: 20.0
      Defense: 35.0
      Sp. Atk: 20.0
      Sp. Def: 45.0
      Speed: 75
      Generation: 2
      Legendary: false
    - index: 255
      '#': 236
      Name: Tyrogue
      Type 1: Fighting
      Type 2: null
      Total: 210
      HP: 35.0
      Attack: 35.0
      Defense: 35.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 35
      Generation: 2
      Legendary: false
    - index: 256
      '#': 237
      Name: Hitmontop
      Type 1: Fighting
      Type 2: null
      Total: 455
      HP: 50.0
      Attack: 95.0
      Defense: 95.0
      Sp. Atk: 35.0
      Sp. Def: 110.0
      Speed: 70
      Generation: 2
      Legendary: false
    - index: 257
      '#': 238
      Name: Smoochum
      Type 1: Ice
      Type 2: Psychic
      Total: 305
      HP: 45.0
      Attack: 30.0
      Defense: 15.0
      Sp. Atk: 85.0
      Sp. Def: 65.0
      Speed: 65
      Generation: 2
      Legendary: false
    - index: 258
      '#': 239
      Name: Elekid
      Type 1: Electric
      Type 2: null
      Total: 360
      HP: 45.0
      Attack: 63.0
      Defense: 37.0
      Sp. Atk: 65.0
      Sp. Def: 55.0
      Speed: 95
      Generation: 2
      Legendary: false
    - index: 259
      '#': 240
      Name: Magby
      Type 1: Fire
      Type 2: null
      Total: 365
      HP: 45.0
      Attack: 75.0
      Defense: 37.0
      Sp. Atk: 70.0
      Sp. Def: 55.0
      Speed: 83
      Generation: 2
      Legendary: false
    - index: 260
      '#': 241
      Name: Miltank
      Type 1: Normal
      Type 2: null
      Total: 490
      HP: 95.0
      Attack: 80.0
      Defense: 105.0
      Sp. Atk: 40.0
      Sp. Def: 70.0
      Speed: 100
      Generation: 2
      Legendary: false
    - index: 261
      '#': 242
      Name: Blissey
      Type 1: Normal
      Type 2: null
      Total: 540
      HP: 255.0
      Attack: 10.0
      Defense: 10.0
      Sp. Atk: 75.0
      Sp. Def: 135.0
      Speed: 55
      Generation: 2
      Legendary: false
    - index: 262
      '#': 243
      Name: Raikou
      Type 1: Electric
      Type 2: null
      Total: 580
      HP: 90.0
      Attack: 85.0
      Defense: 75.0
      Sp. Atk: 115.0
      Sp. Def: 100.0
      Speed: 115
      Generation: 2
      Legendary: true
    - index: 263
      '#': 244
      Name: Entei
      Type 1: Fire
      Type 2: null
      Total: 580
      HP: 115.0
      Attack: 115.0
      Defense: 85.0
      Sp. Atk: 90.0
      Sp. Def: 75.0
      Speed: 100
      Generation: 2
      Legendary: true
    - index: 264
      '#': 245
      Name: Suicune
      Type 1: Water
      Type 2: null
      Total: 580
      HP: 100.0
      Attack: 75.0
      Defense: 115.0
      Sp. Atk: 90.0
      Sp. Def: 115.0
      Speed: 85
      Generation: 2
      Legendary: true
    - index: 265
      '#': 246
      Name: Larvitar
      Type 1: Rock
      Type 2: Ground
      Total: 300
      HP: 50.0
      Attack: 64.0
      Defense: 50.0
      Sp. Atk: 45.0
      Sp. Def: 50.0
      Speed: 41
      Generation: 2
      Legendary: false
    - index: 266
      '#': 247
      Name: Pupitar
      Type 1: Rock
      Type 2: Ground
      Total: 410
      HP: 70.0
      Attack: 84.0
      Defense: 70.0
      Sp. Atk: 65.0
      Sp. Def: 70.0
      Speed: 51
      Generation: 2
      Legendary: false
    - index: 267
      '#': 248
      Name: Tyranitar
      Type 1: Rock
      Type 2: Dark
      Total: 600
      HP: 100.0
      Attack: 134.0
      Defense: 110.0
      Sp. Atk: 95.0
      Sp. Def: 100.0
      Speed: 61
      Generation: 2
      Legendary: false
    - index: 268
      '#': 248
      Name: TyranitarMega Tyranitar
      Type 1: Rock
      Type 2: Dark
      Total: 700
      HP: 100.0
      Attack: 164.0
      Defense: 150.0
      Sp. Atk: 95.0
      Sp. Def: 120.0
      Speed: 71
      Generation: 2
      Legendary: false
    - index: 269
      '#': 249
      Name: Lugia
      Type 1: Psychic
      Type 2: Flying
      Total: 680
      HP: 106.0
      Attack: 90.0
      Defense: 130.0
      Sp. Atk: 90.0
      Sp. Def: 154.0
      Speed: 110
      Generation: 2
      Legendary: true
    - index: 270
      '#': 250
      Name: Ho-oh
      Type 1: Fire
      Type 2: Flying
      Total: 680
      HP: 106.0
      Attack: 130.0
      Defense: 90.0
      Sp. Atk: 110.0
      Sp. Def: 154.0
      Speed: 90
      Generation: 2
      Legendary: true
    - index: 271
      '#': 251
      Name: Celebi
      Type 1: Psychic
      Type 2: Grass
      Total: 600
      HP: 100.0
      Attack: 100.0
      Defense: 100.0
      Sp. Atk: 100.0
      Sp. Def: 100.0
      Speed: 100
      Generation: 2
      Legendary: false
    - index: 272
      '#': 252
      Name: Treecko
      Type 1: Grass
      Type 2: null
      Total: 310
      HP: 40.0
      Attack: 45.0
      Defense: 35.0
      Sp. Atk: 65.0
      Sp. Def: 55.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 273
      '#': 253
      Name: Grovyle
      Type 1: Grass
      Type 2: null
      Total: 405
      HP: 50.0
      Attack: 65.0
      Defense: 45.0
      Sp. Atk: 85.0
      Sp. Def: 65.0
      Speed: 95
      Generation: 3
      Legendary: false
    - index: 274
      '#': 254
      Name: Sceptile
      Type 1: Grass
      Type 2: null
      Total: 530
      HP: 70.0
      Attack: 85.0
      Defense: 65.0
      Sp. Atk: 105.0
      Sp. Def: 85.0
      Speed: 120
      Generation: 3
      Legendary: false
    - index: 275
      '#': 254
      Name: SceptileMega Sceptile
      Type 1: Grass
      Type 2: Dragon
      Total: 630
      HP: 70.0
      Attack: 110.0
      Defense: 75.0
      Sp. Atk: 145.0
      Sp. Def: 85.0
      Speed: 145
      Generation: 3
      Legendary: false
    - index: 276
      '#': 255
      Name: Torchic
      Type 1: Fire
      Type 2: null
      Total: 310
      HP: 45.0
      Attack: 60.0
      Defense: 40.0
      Sp. Atk: 70.0
      Sp. Def: 50.0
      Speed: 45
      Generation: 3
      Legendary: false
    - index: 277
      '#': 256
      Name: Combusken
      Type 1: Fire
      Type 2: Fighting
      Total: 405
      HP: 60.0
      Attack: 85.0
      Defense: 60.0
      Sp. Atk: 85.0
      Sp. Def: 60.0
      Speed: 55
      Generation: 3
      Legendary: false
    - index: 278
      '#': 257
      Name: Blaziken
      Type 1: Fire
      Type 2: Fighting
      Total: 530
      HP: 80.0
      Attack: 120.0
      Defense: 70.0
      Sp. Atk: 110.0
      Sp. Def: 70.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 279
      '#': 257
      Name: BlazikenMega Blaziken
      Type 1: Fire
      Type 2: Fighting
      Total: 630
      HP: 80.0
      Attack: 160.0
      Defense: 80.0
      Sp. Atk: 130.0
      Sp. Def: 80.0
      Speed: 100
      Generation: 3
      Legendary: false
    - index: 280
      '#': 258
      Name: Mudkip
      Type 1: Water
      Type 2: null
      Total: 310
      HP: 50.0
      Attack: 70.0
      Defense: 50.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 281
      '#': 259
      Name: Marshtomp
      Type 1: Water
      Type 2: Ground
      Total: 405
      HP: 70.0
      Attack: 85.0
      Defense: 70.0
      Sp. Atk: 60.0
      Sp. Def: 70.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 282
      '#': 260
      Name: Swampert
      Type 1: Water
      Type 2: Ground
      Total: 535
      HP: 100.0
      Attack: 110.0
      Defense: 90.0
      Sp. Atk: 85.0
      Sp. Def: 90.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 283
      '#': 260
      Name: SwampertMega Swampert
      Type 1: Water
      Type 2: Ground
      Total: 635
      HP: 100.0
      Attack: 150.0
      Defense: 110.0
      Sp. Atk: 95.0
      Sp. Def: 110.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 284
      '#': 261
      Name: Poochyena
      Type 1: Dark
      Type 2: null
      Total: 220
      HP: 35.0
      Attack: 55.0
      Defense: 35.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 35
      Generation: 3
      Legendary: false
    - index: 285
      '#': 262
      Name: Mightyena
      Type 1: Dark
      Type 2: null
      Total: 420
      HP: 70.0
      Attack: 90.0
      Defense: 70.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 286
      '#': 263
      Name: Zigzagoon
      Type 1: Normal
      Type 2: null
      Total: 240
      HP: 38.0
      Attack: 30.0
      Defense: 41.0
      Sp. Atk: 30.0
      Sp. Def: 41.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 287
      '#': 264
      Name: Linoone
      Type 1: Normal
      Type 2: null
      Total: 420
      HP: 78.0
      Attack: 70.0
      Defense: 61.0
      Sp. Atk: 50.0
      Sp. Def: 61.0
      Speed: 100
      Generation: 3
      Legendary: false
    - index: 288
      '#': 265
      Name: Wurmple
      Type 1: Bug
      Type 2: null
      Total: 195
      HP: 45.0
      Attack: 45.0
      Defense: 35.0
      Sp. Atk: 20.0
      Sp. Def: 30.0
      Speed: 20
      Generation: 3
      Legendary: false
    - index: 289
      '#': 266
      Name: Silcoon
      Type 1: Bug
      Type 2: null
      Total: 205
      HP: 50.0
      Attack: 35.0
      Defense: 55.0
      Sp. Atk: 25.0
      Sp. Def: 25.0
      Speed: 15
      Generation: 3
      Legendary: false
    - index: 290
      '#': 267
      Name: Beautifly
      Type 1: Bug
      Type 2: Flying
      Total: 395
      HP: 60.0
      Attack: 70.0
      Defense: 50.0
      Sp. Atk: 100.0
      Sp. Def: 50.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 291
      '#': 268
      Name: Cascoon
      Type 1: Bug
      Type 2: null
      Total: 205
      HP: 50.0
      Attack: 35.0
      Defense: 55.0
      Sp. Atk: 25.0
      Sp. Def: 25.0
      Speed: 15
      Generation: 3
      Legendary: false
    - index: 292
      '#': 269
      Name: Dustox
      Type 1: Bug
      Type 2: Poison
      Total: 385
      HP: 60.0
      Attack: 50.0
      Defense: 70.0
      Sp. Atk: 50.0
      Sp. Def: 90.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 293
      '#': 270
      Name: Lotad
      Type 1: Water
      Type 2: Grass
      Total: 220
      HP: 40.0
      Attack: 30.0
      Defense: 30.0
      Sp. Atk: 40.0
      Sp. Def: 50.0
      Speed: 30
      Generation: 3
      Legendary: false
    - index: 294
      '#': 271
      Name: Lombre
      Type 1: Water
      Type 2: Grass
      Total: 340
      HP: 60.0
      Attack: 50.0
      Defense: 50.0
      Sp. Atk: 60.0
      Sp. Def: 70.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 295
      '#': 272
      Name: Ludicolo
      Type 1: Water
      Type 2: Grass
      Total: 480
      HP: 80.0
      Attack: 70.0
      Defense: 70.0
      Sp. Atk: 90.0
      Sp. Def: 100.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 296
      '#': 273
      Name: Seedot
      Type 1: Grass
      Type 2: null
      Total: 220
      HP: 40.0
      Attack: 40.0
      Defense: 50.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 30
      Generation: 3
      Legendary: false
    - index: 297
      '#': 274
      Name: Nuzleaf
      Type 1: Grass
      Type 2: Dark
      Total: 340
      HP: 70.0
      Attack: 70.0
      Defense: 40.0
      Sp. Atk: 60.0
      Sp. Def: 40.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 298
      '#': 275
      Name: Shiftry
      Type 1: Grass
      Type 2: Dark
      Total: 480
      HP: 90.0
      Attack: 100.0
      Defense: 60.0
      Sp. Atk: 90.0
      Sp. Def: 60.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 299
      '#': 276
      Name: Taillow
      Type 1: Normal
      Type 2: Flying
      Total: 270
      HP: 40.0
      Attack: 55.0
      Defense: 30.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 85
      Generation: 3
      Legendary: false
    - index: 300
      '#': 277
      Name: Swellow
      Type 1: Normal
      Type 2: Flying
      Total: 430
      HP: 60.0
      Attack: 85.0
      Defense: 60.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 125
      Generation: 3
      Legendary: false
    - index: 301
      '#': 278
      Name: Wingull
      Type 1: Water
      Type 2: Flying
      Total: 270
      HP: 40.0
      Attack: 30.0
      Defense: 30.0
      Sp. Atk: 55.0
      Sp. Def: 30.0
      Speed: 85
      Generation: 3
      Legendary: false
    - index: 302
      '#': 279
      Name: Pelipper
      Type 1: Water
      Type 2: Flying
      Total: 430
      HP: 60.0
      Attack: 50.0
      Defense: 100.0
      Sp. Atk: 85.0
      Sp. Def: 70.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 303
      '#': 280
      Name: Ralts
      Type 1: Psychic
      Type 2: Fairy
      Total: 198
      HP: 28.0
      Attack: 25.0
      Defense: 25.0
      Sp. Atk: 45.0
      Sp. Def: 35.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 304
      '#': 281
      Name: Kirlia
      Type 1: Psychic
      Type 2: Fairy
      Total: 278
      HP: 38.0
      Attack: 35.0
      Defense: 35.0
      Sp. Atk: 65.0
      Sp. Def: 55.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 305
      '#': 282
      Name: Gardevoir
      Type 1: Psychic
      Type 2: Fairy
      Total: 518
      HP: 68.0
      Attack: 65.0
      Defense: 65.0
      Sp. Atk: 125.0
      Sp. Def: 115.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 306
      '#': 282
      Name: GardevoirMega Gardevoir
      Type 1: Psychic
      Type 2: Fairy
      Total: 618
      HP: 68.0
      Attack: 85.0
      Defense: 65.0
      Sp. Atk: 165.0
      Sp. Def: 135.0
      Speed: 100
      Generation: 3
      Legendary: false
    - index: 307
      '#': 283
      Name: Surskit
      Type 1: Bug
      Type 2: Water
      Total: 269
      HP: 40.0
      Attack: 30.0
      Defense: 32.0
      Sp. Atk: 50.0
      Sp. Def: 52.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 308
      '#': 284
      Name: Masquerain
      Type 1: Bug
      Type 2: Flying
      Total: 414
      HP: 70.0
      Attack: 60.0
      Defense: 62.0
      Sp. Atk: 80.0
      Sp. Def: 82.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 309
      '#': 285
      Name: Shroomish
      Type 1: Grass
      Type 2: null
      Total: 295
      HP: 60.0
      Attack: 40.0
      Defense: 60.0
      Sp. Atk: 40.0
      Sp. Def: 60.0
      Speed: 35
      Generation: 3
      Legendary: false
    - index: 310
      '#': 286
      Name: Breloom
      Type 1: Grass
      Type 2: Fighting
      Total: 460
      HP: 60.0
      Attack: 130.0
      Defense: 80.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 311
      '#': 287
      Name: Slakoth
      Type 1: Normal
      Type 2: null
      Total: 280
      HP: 60.0
      Attack: 60.0
      Defense: 60.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 30
      Generation: 3
      Legendary: false
    - index: 312
      '#': 288
      Name: Vigoroth
      Type 1: Normal
      Type 2: null
      Total: 440
      HP: 80.0
      Attack: 80.0
      Defense: 80.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 90
      Generation: 3
      Legendary: false
    - index: 313
      '#': 289
      Name: Slaking
      Type 1: Normal
      Type 2: null
      Total: 670
      HP: 150.0
      Attack: 160.0
      Defense: 100.0
      Sp. Atk: 95.0
      Sp. Def: 65.0
      Speed: 100
      Generation: 3
      Legendary: false
    - index: 314
      '#': 290
      Name: Nincada
      Type 1: Bug
      Type 2: Ground
      Total: 266
      HP: 31.0
      Attack: 45.0
      Defense: 90.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 315
      '#': 291
      Name: Ninjask
      Type 1: Bug
      Type 2: Flying
      Total: 456
      HP: 61.0
      Attack: 90.0
      Defense: 45.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 160
      Generation: 3
      Legendary: false
    - index: 316
      '#': 292
      Name: Shedinja
      Type 1: Bug
      Type 2: Ghost
      Total: 236
      HP: 1.0
      Attack: 90.0
      Defense: 45.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 317
      '#': 293
      Name: Whismur
      Type 1: Normal
      Type 2: null
      Total: 240
      HP: 64.0
      Attack: 51.0
      Defense: 23.0
      Sp. Atk: 51.0
      Sp. Def: 23.0
      Speed: 28
      Generation: 3
      Legendary: false
    - index: 318
      '#': 294
      Name: Loudred
      Type 1: Normal
      Type 2: null
      Total: 360
      HP: 84.0
      Attack: 71.0
      Defense: 43.0
      Sp. Atk: 71.0
      Sp. Def: 43.0
      Speed: 48
      Generation: 3
      Legendary: false
    - index: 319
      '#': 295
      Name: Exploud
      Type 1: Normal
      Type 2: null
      Total: 490
      HP: 104.0
      Attack: 91.0
      Defense: 63.0
      Sp. Atk: 91.0
      Sp. Def: 73.0
      Speed: 68
      Generation: 3
      Legendary: false
    - index: 320
      '#': 296
      Name: Makuhita
      Type 1: Fighting
      Type 2: null
      Total: 237
      HP: 72.0
      Attack: 60.0
      Defense: 30.0
      Sp. Atk: 20.0
      Sp. Def: 30.0
      Speed: 25
      Generation: 3
      Legendary: false
    - index: 321
      '#': 297
      Name: Hariyama
      Type 1: Fighting
      Type 2: null
      Total: 474
      HP: 144.0
      Attack: 120.0
      Defense: 60.0
      Sp. Atk: 40.0
      Sp. Def: 60.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 322
      '#': 298
      Name: Azurill
      Type 1: Normal
      Type 2: Fairy
      Total: 190
      HP: 50.0
      Attack: 20.0
      Defense: 40.0
      Sp. Atk: 20.0
      Sp. Def: 40.0
      Speed: 20
      Generation: 3
      Legendary: false
    - index: 323
      '#': 299
      Name: Nosepass
      Type 1: Rock
      Type 2: null
      Total: 375
      HP: 30.0
      Attack: 45.0
      Defense: 135.0
      Sp. Atk: 45.0
      Sp. Def: 90.0
      Speed: 30
      Generation: 3
      Legendary: false
    - index: 324
      '#': 300
      Name: Skitty
      Type 1: Normal
      Type 2: null
      Total: 260
      HP: 50.0
      Attack: 45.0
      Defense: 45.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 325
      '#': 301
      Name: Delcatty
      Type 1: Normal
      Type 2: null
      Total: 380
      HP: 70.0
      Attack: 65.0
      Defense: 65.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 326
      '#': 302
      Name: Sableye
      Type 1: Dark
      Type 2: Ghost
      Total: 380
      HP: 50.0
      Attack: 75.0
      Defense: 75.0
      Sp. Atk: 65.0
      Sp. Def: 65.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 327
      '#': 302
      Name: SableyeMega Sableye
      Type 1: Dark
      Type 2: Ghost
      Total: 480
      HP: 50.0
      Attack: 85.0
      Defense: 125.0
      Sp. Atk: 85.0
      Sp. Def: 115.0
      Speed: 20
      Generation: 3
      Legendary: false
    - index: 328
      '#': 303
      Name: Mawile
      Type 1: Steel
      Type 2: Fairy
      Total: 380
      HP: 50.0
      Attack: 85.0
      Defense: 85.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 329
      '#': 303
      Name: MawileMega Mawile
      Type 1: Steel
      Type 2: Fairy
      Total: 480
      HP: 50.0
      Attack: 105.0
      Defense: 125.0
      Sp. Atk: 55.0
      Sp. Def: 95.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 330
      '#': 304
      Name: Aron
      Type 1: Steel
      Type 2: Rock
      Total: 330
      HP: 50.0
      Attack: 70.0
      Defense: 100.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 30
      Generation: 3
      Legendary: false
    - index: 331
      '#': 305
      Name: Lairon
      Type 1: Steel
      Type 2: Rock
      Total: 430
      HP: 60.0
      Attack: 90.0
      Defense: 140.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 332
      '#': 306
      Name: Aggron
      Type 1: Steel
      Type 2: Rock
      Total: 530
      HP: 70.0
      Attack: 110.0
      Defense: 180.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 333
      '#': 306
      Name: AggronMega Aggron
      Type 1: Steel
      Type 2: null
      Total: 630
      HP: 70.0
      Attack: 140.0
      Defense: 230.0
      Sp. Atk: 60.0
      Sp. Def: 80.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 334
      '#': 307
      Name: Meditite
      Type 1: Fighting
      Type 2: Psychic
      Total: 280
      HP: 30.0
      Attack: 40.0
      Defense: 55.0
      Sp. Atk: 40.0
      Sp. Def: 55.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 335
      '#': 308
      Name: Medicham
      Type 1: Fighting
      Type 2: Psychic
      Total: 410
      HP: 60.0
      Attack: 60.0
      Defense: 75.0
      Sp. Atk: 60.0
      Sp. Def: 75.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 336
      '#': 308
      Name: MedichamMega Medicham
      Type 1: Fighting
      Type 2: Psychic
      Total: 510
      HP: 60.0
      Attack: 100.0
      Defense: 85.0
      Sp. Atk: 80.0
      Sp. Def: 85.0
      Speed: 100
      Generation: 3
      Legendary: false
    - index: 337
      '#': 309
      Name: Electrike
      Type 1: Electric
      Type 2: null
      Total: 295
      HP: 40.0
      Attack: 45.0
      Defense: 40.0
      Sp. Atk: 65.0
      Sp. Def: 40.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 338
      '#': 310
      Name: Manectric
      Type 1: Electric
      Type 2: null
      Total: 475
      HP: 70.0
      Attack: 75.0
      Defense: 60.0
      Sp. Atk: 105.0
      Sp. Def: 60.0
      Speed: 105
      Generation: 3
      Legendary: false
    - index: 339
      '#': 310
      Name: ManectricMega Manectric
      Type 1: Electric
      Type 2: null
      Total: 575
      HP: 70.0
      Attack: 75.0
      Defense: 80.0
      Sp. Atk: 135.0
      Sp. Def: 80.0
      Speed: 135
      Generation: 3
      Legendary: false
    - index: 340
      '#': 311
      Name: Plusle
      Type 1: Electric
      Type 2: null
      Total: 405
      HP: 60.0
      Attack: 50.0
      Defense: 40.0
      Sp. Atk: 85.0
      Sp. Def: 75.0
      Speed: 95
      Generation: 3
      Legendary: false
    - index: 341
      '#': 312
      Name: Minun
      Type 1: Electric
      Type 2: null
      Total: 405
      HP: 60.0
      Attack: 40.0
      Defense: 50.0
      Sp. Atk: 75.0
      Sp. Def: 85.0
      Speed: 95
      Generation: 3
      Legendary: false
    - index: 342
      '#': 313
      Name: Volbeat
      Type 1: Bug
      Type 2: null
      Total: 400
      HP: 65.0
      Attack: 73.0
      Defense: 55.0
      Sp. Atk: 47.0
      Sp. Def: 75.0
      Speed: 85
      Generation: 3
      Legendary: false
    - index: 343
      '#': 314
      Name: Illumise
      Type 1: Bug
      Type 2: null
      Total: 400
      HP: 65.0
      Attack: 47.0
      Defense: 55.0
      Sp. Atk: 73.0
      Sp. Def: 75.0
      Speed: 85
      Generation: 3
      Legendary: false
    - index: 344
      '#': 315
      Name: Roselia
      Type 1: Grass
      Type 2: Poison
      Total: 400
      HP: 50.0
      Attack: 60.0
      Defense: 45.0
      Sp. Atk: 100.0
      Sp. Def: 80.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 345
      '#': 316
      Name: Gulpin
      Type 1: Poison
      Type 2: null
      Total: 302
      HP: 70.0
      Attack: 43.0
      Defense: 53.0
      Sp. Atk: 43.0
      Sp. Def: 53.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 346
      '#': 317
      Name: Swalot
      Type 1: Poison
      Type 2: null
      Total: 467
      HP: 100.0
      Attack: 73.0
      Defense: 83.0
      Sp. Atk: 73.0
      Sp. Def: 83.0
      Speed: 55
      Generation: 3
      Legendary: false
    - index: 347
      '#': 318
      Name: Carvanha
      Type 1: Water
      Type 2: Dark
      Total: 305
      HP: 45.0
      Attack: 90.0
      Defense: 20.0
      Sp. Atk: 65.0
      Sp. Def: 20.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 348
      '#': 319
      Name: Sharpedo
      Type 1: Water
      Type 2: Dark
      Total: 460
      HP: 70.0
      Attack: 120.0
      Defense: 40.0
      Sp. Atk: 95.0
      Sp. Def: 40.0
      Speed: 95
      Generation: 3
      Legendary: false
    - index: 349
      '#': 319
      Name: SharpedoMega Sharpedo
      Type 1: Water
      Type 2: Dark
      Total: 560
      HP: 70.0
      Attack: 140.0
      Defense: 70.0
      Sp. Atk: 110.0
      Sp. Def: 65.0
      Speed: 105
      Generation: 3
      Legendary: false
    - index: 350
      '#': 320
      Name: Wailmer
      Type 1: Water
      Type 2: null
      Total: 400
      HP: 130.0
      Attack: 70.0
      Defense: 35.0
      Sp. Atk: 70.0
      Sp. Def: 35.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 351
      '#': 321
      Name: Wailord
      Type 1: Water
      Type 2: null
      Total: 500
      HP: 170.0
      Attack: 90.0
      Defense: 45.0
      Sp. Atk: 90.0
      Sp. Def: 45.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 352
      '#': 322
      Name: Numel
      Type 1: Fire
      Type 2: Ground
      Total: 305
      HP: 60.0
      Attack: 60.0
      Defense: 40.0
      Sp. Atk: 65.0
      Sp. Def: 45.0
      Speed: 35
      Generation: 3
      Legendary: false
    - index: 353
      '#': 323
      Name: Camerupt
      Type 1: Fire
      Type 2: Ground
      Total: 460
      HP: 70.0
      Attack: 100.0
      Defense: 70.0
      Sp. Atk: 105.0
      Sp. Def: 75.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 354
      '#': 323
      Name: CameruptMega Camerupt
      Type 1: Fire
      Type 2: Ground
      Total: 560
      HP: 70.0
      Attack: 120.0
      Defense: 100.0
      Sp. Atk: 145.0
      Sp. Def: 105.0
      Speed: 20
      Generation: 3
      Legendary: false
    - index: 355
      '#': 324
      Name: Torkoal
      Type 1: Fire
      Type 2: null
      Total: 470
      HP: 70.0
      Attack: 85.0
      Defense: 140.0
      Sp. Atk: 85.0
      Sp. Def: 70.0
      Speed: 20
      Generation: 3
      Legendary: false
    - index: 356
      '#': 325
      Name: Spoink
      Type 1: Psychic
      Type 2: null
      Total: 330
      HP: 60.0
      Attack: 25.0
      Defense: 35.0
      Sp. Atk: 70.0
      Sp. Def: 80.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 357
      '#': 326
      Name: Grumpig
      Type 1: Psychic
      Type 2: null
      Total: 470
      HP: 80.0
      Attack: 45.0
      Defense: 65.0
      Sp. Atk: 90.0
      Sp. Def: 110.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 358
      '#': 327
      Name: Spinda
      Type 1: Normal
      Type 2: null
      Total: 360
      HP: 60.0
      Attack: 60.0
      Defense: 60.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 359
      '#': 328
      Name: Trapinch
      Type 1: Ground
      Type 2: null
      Total: 290
      HP: 45.0
      Attack: 100.0
      Defense: 45.0
      Sp. Atk: 45.0
      Sp. Def: 45.0
      Speed: 10
      Generation: 3
      Legendary: false
    - index: 360
      '#': 329
      Name: Vibrava
      Type 1: Ground
      Type 2: Dragon
      Total: 340
      HP: 50.0
      Attack: 70.0
      Defense: 50.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 361
      '#': 330
      Name: Flygon
      Type 1: Ground
      Type 2: Dragon
      Total: 520
      HP: 80.0
      Attack: 100.0
      Defense: 80.0
      Sp. Atk: 80.0
      Sp. Def: 80.0
      Speed: 100
      Generation: 3
      Legendary: false
    - index: 362
      '#': 331
      Name: Cacnea
      Type 1: Grass
      Type 2: null
      Total: 335
      HP: 50.0
      Attack: 85.0
      Defense: 40.0
      Sp. Atk: 85.0
      Sp. Def: 40.0
      Speed: 35
      Generation: 3
      Legendary: false
    - index: 363
      '#': 332
      Name: Cacturne
      Type 1: Grass
      Type 2: Dark
      Total: 475
      HP: 70.0
      Attack: 115.0
      Defense: 60.0
      Sp. Atk: 115.0
      Sp. Def: 60.0
      Speed: 55
      Generation: 3
      Legendary: false
    - index: 364
      '#': 333
      Name: Swablu
      Type 1: Normal
      Type 2: Flying
      Total: 310
      HP: 45.0
      Attack: 40.0
      Defense: 60.0
      Sp. Atk: 40.0
      Sp. Def: 75.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 365
      '#': 334
      Name: Altaria
      Type 1: Dragon
      Type 2: Flying
      Total: 490
      HP: 75.0
      Attack: 70.0
      Defense: 90.0
      Sp. Atk: 70.0
      Sp. Def: 105.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 366
      '#': 334
      Name: AltariaMega Altaria
      Type 1: Dragon
      Type 2: Fairy
      Total: 590
      HP: 75.0
      Attack: 110.0
      Defense: 110.0
      Sp. Atk: 110.0
      Sp. Def: 105.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 367
      '#': 335
      Name: Zangoose
      Type 1: Normal
      Type 2: null
      Total: 458
      HP: 73.0
      Attack: 115.0
      Defense: 60.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 90
      Generation: 3
      Legendary: false
    - index: 368
      '#': 336
      Name: Seviper
      Type 1: Poison
      Type 2: null
      Total: 458
      HP: 73.0
      Attack: 100.0
      Defense: 60.0
      Sp. Atk: 100.0
      Sp. Def: 60.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 369
      '#': 337
      Name: Lunatone
      Type 1: Rock
      Type 2: Psychic
      Total: 440
      HP: 70.0
      Attack: 55.0
      Defense: 65.0
      Sp. Atk: 95.0
      Sp. Def: 85.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 370
      '#': 338
      Name: Solrock
      Type 1: Rock
      Type 2: Psychic
      Total: 440
      HP: 70.0
      Attack: 95.0
      Defense: 85.0
      Sp. Atk: 55.0
      Sp. Def: 65.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 371
      '#': 339
      Name: Barboach
      Type 1: Water
      Type 2: Ground
      Total: 288
      HP: 50.0
      Attack: 48.0
      Defense: 43.0
      Sp. Atk: 46.0
      Sp. Def: 41.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 372
      '#': 340
      Name: Whiscash
      Type 1: Water
      Type 2: Ground
      Total: 468
      HP: 110.0
      Attack: 78.0
      Defense: 73.0
      Sp. Atk: 76.0
      Sp. Def: 71.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 373
      '#': 341
      Name: Corphish
      Type 1: Water
      Type 2: null
      Total: 308
      HP: 43.0
      Attack: 80.0
      Defense: 65.0
      Sp. Atk: 50.0
      Sp. Def: 35.0
      Speed: 35
      Generation: 3
      Legendary: false
    - index: 374
      '#': 342
      Name: Crawdaunt
      Type 1: Water
      Type 2: Dark
      Total: 468
      HP: 63.0
      Attack: 120.0
      Defense: 85.0
      Sp. Atk: 90.0
      Sp. Def: 55.0
      Speed: 55
      Generation: 3
      Legendary: false
    - index: 375
      '#': 343
      Name: Baltoy
      Type 1: Ground
      Type 2: Psychic
      Total: 300
      HP: 40.0
      Attack: 40.0
      Defense: 55.0
      Sp. Atk: 40.0
      Sp. Def: 70.0
      Speed: 55
      Generation: 3
      Legendary: false
    - index: 376
      '#': 344
      Name: Claydol
      Type 1: Ground
      Type 2: Psychic
      Total: 500
      HP: 60.0
      Attack: 70.0
      Defense: 105.0
      Sp. Atk: 70.0
      Sp. Def: 120.0
      Speed: 75
      Generation: 3
      Legendary: false
    - index: 377
      '#': 345
      Name: Lileep
      Type 1: Rock
      Type 2: Grass
      Total: 355
      HP: 66.0
      Attack: 41.0
      Defense: 77.0
      Sp. Atk: 61.0
      Sp. Def: 87.0
      Speed: 23
      Generation: 3
      Legendary: false
    - index: 378
      '#': 346
      Name: Cradily
      Type 1: Rock
      Type 2: Grass
      Total: 495
      HP: 86.0
      Attack: 81.0
      Defense: 97.0
      Sp. Atk: 81.0
      Sp. Def: 107.0
      Speed: 43
      Generation: 3
      Legendary: false
    - index: 379
      '#': 347
      Name: Anorith
      Type 1: Rock
      Type 2: Bug
      Total: 355
      HP: 45.0
      Attack: 95.0
      Defense: 50.0
      Sp. Atk: 40.0
      Sp. Def: 50.0
      Speed: 75
      Generation: 3
      Legendary: false
    - index: 380
      '#': 348
      Name: Armaldo
      Type 1: Rock
      Type 2: Bug
      Total: 495
      HP: 75.0
      Attack: 125.0
      Defense: 100.0
      Sp. Atk: 70.0
      Sp. Def: 80.0
      Speed: 45
      Generation: 3
      Legendary: false
    - index: 381
      '#': 349
      Name: Feebas
      Type 1: Water
      Type 2: null
      Total: 200
      HP: 20.0
      Attack: 15.0
      Defense: 20.0
      Sp. Atk: 10.0
      Sp. Def: 55.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 382
      '#': 350
      Name: Milotic
      Type 1: Water
      Type 2: null
      Total: 540
      HP: 95.0
      Attack: 60.0
      Defense: 79.0
      Sp. Atk: 100.0
      Sp. Def: 125.0
      Speed: 81
      Generation: 3
      Legendary: false
    - index: 383
      '#': 351
      Name: Castform
      Type 1: Normal
      Type 2: null
      Total: 420
      HP: 70.0
      Attack: 70.0
      Defense: 70.0
      Sp. Atk: 70.0
      Sp. Def: 70.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 384
      '#': 352
      Name: Kecleon
      Type 1: Normal
      Type 2: null
      Total: 440
      HP: 60.0
      Attack: 90.0
      Defense: 70.0
      Sp. Atk: 60.0
      Sp. Def: 120.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 385
      '#': 353
      Name: Shuppet
      Type 1: Ghost
      Type 2: null
      Total: 295
      HP: 44.0
      Attack: 75.0
      Defense: 35.0
      Sp. Atk: 63.0
      Sp. Def: 33.0
      Speed: 45
      Generation: 3
      Legendary: false
    - index: 386
      '#': 354
      Name: Banette
      Type 1: Ghost
      Type 2: null
      Total: 455
      HP: 64.0
      Attack: 115.0
      Defense: 65.0
      Sp. Atk: 83.0
      Sp. Def: 63.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 387
      '#': 354
      Name: BanetteMega Banette
      Type 1: Ghost
      Type 2: null
      Total: 555
      HP: 64.0
      Attack: 165.0
      Defense: 75.0
      Sp. Atk: 93.0
      Sp. Def: 83.0
      Speed: 75
      Generation: 3
      Legendary: false
    - index: 388
      '#': 355
      Name: Duskull
      Type 1: Ghost
      Type 2: null
      Total: 295
      HP: 20.0
      Attack: 40.0
      Defense: 90.0
      Sp. Atk: 30.0
      Sp. Def: 90.0
      Speed: 25
      Generation: 3
      Legendary: false
    - index: 389
      '#': 356
      Name: Dusclops
      Type 1: Ghost
      Type 2: null
      Total: 455
      HP: 40.0
      Attack: 70.0
      Defense: 130.0
      Sp. Atk: 60.0
      Sp. Def: 130.0
      Speed: 25
      Generation: 3
      Legendary: false
    - index: 390
      '#': 357
      Name: Tropius
      Type 1: Grass
      Type 2: Flying
      Total: 460
      HP: 99.0
      Attack: 68.0
      Defense: 83.0
      Sp. Atk: 72.0
      Sp. Def: 87.0
      Speed: 51
      Generation: 3
      Legendary: false
    - index: 391
      '#': 358
      Name: Chimecho
      Type 1: Psychic
      Type 2: null
      Total: 425
      HP: 65.0
      Attack: 50.0
      Defense: 70.0
      Sp. Atk: 95.0
      Sp. Def: 80.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 392
      '#': 359
      Name: Absol
      Type 1: Dark
      Type 2: null
      Total: 465
      HP: 65.0
      Attack: 130.0
      Defense: 60.0
      Sp. Atk: 75.0
      Sp. Def: 60.0
      Speed: 75
      Generation: 3
      Legendary: false
    - index: 393
      '#': 359
      Name: AbsolMega Absol
      Type 1: Dark
      Type 2: null
      Total: 565
      HP: 65.0
      Attack: 150.0
      Defense: 60.0
      Sp. Atk: 115.0
      Sp. Def: 60.0
      Speed: 115
      Generation: 3
      Legendary: false
    - index: 394
      '#': 360
      Name: Wynaut
      Type 1: Psychic
      Type 2: null
      Total: 260
      HP: 95.0
      Attack: 23.0
      Defense: 48.0
      Sp. Atk: 23.0
      Sp. Def: 48.0
      Speed: 23
      Generation: 3
      Legendary: false
    - index: 395
      '#': 361
      Name: Snorunt
      Type 1: Ice
      Type 2: null
      Total: 300
      HP: 50.0
      Attack: 50.0
      Defense: 50.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 396
      '#': 362
      Name: Glalie
      Type 1: Ice
      Type 2: null
      Total: 480
      HP: 80.0
      Attack: 80.0
      Defense: 80.0
      Sp. Atk: 80.0
      Sp. Def: 80.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 397
      '#': 362
      Name: GlalieMega Glalie
      Type 1: Ice
      Type 2: null
      Total: 580
      HP: 80.0
      Attack: 120.0
      Defense: 80.0
      Sp. Atk: 120.0
      Sp. Def: 80.0
      Speed: 100
      Generation: 3
      Legendary: false
    - index: 398
      '#': 363
      Name: Spheal
      Type 1: Ice
      Type 2: Water
      Total: 290
      HP: 70.0
      Attack: 40.0
      Defense: 50.0
      Sp. Atk: 55.0
      Sp. Def: 50.0
      Speed: 25
      Generation: 3
      Legendary: false
    - index: 399
      '#': 364
      Name: Sealeo
      Type 1: Ice
      Type 2: Water
      Total: 410
      HP: 90.0
      Attack: 60.0
      Defense: 70.0
      Sp. Atk: 75.0
      Sp. Def: 70.0
      Speed: 45
      Generation: 3
      Legendary: false
    - index: 400
      '#': 365
      Name: Walrein
      Type 1: Ice
      Type 2: Water
      Total: 530
      HP: 110.0
      Attack: 80.0
      Defense: 90.0
      Sp. Atk: 95.0
      Sp. Def: 90.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 401
      '#': 366
      Name: Clamperl
      Type 1: Water
      Type 2: null
      Total: 345
      HP: 35.0
      Attack: 64.0
      Defense: 85.0
      Sp. Atk: 74.0
      Sp. Def: 55.0
      Speed: 32
      Generation: 3
      Legendary: false
    - index: 402
      '#': 367
      Name: Huntail
      Type 1: Water
      Type 2: null
      Total: 485
      HP: 55.0
      Attack: 104.0
      Defense: 105.0
      Sp. Atk: 94.0
      Sp. Def: 75.0
      Speed: 52
      Generation: 3
      Legendary: false
    - index: 403
      '#': 368
      Name: Gorebyss
      Type 1: Water
      Type 2: null
      Total: 485
      HP: 55.0
      Attack: 84.0
      Defense: 105.0
      Sp. Atk: 114.0
      Sp. Def: 75.0
      Speed: 52
      Generation: 3
      Legendary: false
    - index: 404
      '#': 369
      Name: Relicanth
      Type 1: Water
      Type 2: Rock
      Total: 485
      HP: 100.0
      Attack: 90.0
      Defense: 130.0
      Sp. Atk: 45.0
      Sp. Def: 65.0
      Speed: 55
      Generation: 3
      Legendary: false
    - index: 405
      '#': 370
      Name: Luvdisc
      Type 1: Water
      Type 2: null
      Total: 330
      HP: 43.0
      Attack: 30.0
      Defense: 55.0
      Sp. Atk: 40.0
      Sp. Def: 65.0
      Speed: 97
      Generation: 3
      Legendary: false
    - index: 406
      '#': 371
      Name: Bagon
      Type 1: Dragon
      Type 2: null
      Total: 300
      HP: 45.0
      Attack: 75.0
      Defense: 60.0
      Sp. Atk: 40.0
      Sp. Def: 30.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 407
      '#': 372
      Name: Shelgon
      Type 1: Dragon
      Type 2: null
      Total: 420
      HP: 65.0
      Attack: 95.0
      Defense: 100.0
      Sp. Atk: 60.0
      Sp. Def: 50.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 408
      '#': 373
      Name: Salamence
      Type 1: Dragon
      Type 2: Flying
      Total: 600
      HP: 95.0
      Attack: 135.0
      Defense: 80.0
      Sp. Atk: 110.0
      Sp. Def: 80.0
      Speed: 100
      Generation: 3
      Legendary: false
    - index: 409
      '#': 373
      Name: SalamenceMega Salamence
      Type 1: Dragon
      Type 2: Flying
      Total: 700
      HP: 95.0
      Attack: 145.0
      Defense: 130.0
      Sp. Atk: 120.0
      Sp. Def: 90.0
      Speed: 120
      Generation: 3
      Legendary: false
    - index: 410
      '#': 374
      Name: Beldum
      Type 1: Steel
      Type 2: Psychic
      Total: 300
      HP: 40.0
      Attack: 55.0
      Defense: 80.0
      Sp. Atk: 35.0
      Sp. Def: 60.0
      Speed: 30
      Generation: 3
      Legendary: false
    - index: 411
      '#': 375
      Name: Metang
      Type 1: Steel
      Type 2: Psychic
      Total: 420
      HP: 60.0
      Attack: 75.0
      Defense: 100.0
      Sp. Atk: 55.0
      Sp. Def: 80.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 412
      '#': 376
      Name: Metagross
      Type 1: Steel
      Type 2: Psychic
      Total: 600
      HP: 80.0
      Attack: 135.0
      Defense: 130.0
      Sp. Atk: 95.0
      Sp. Def: 90.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 413
      '#': 376
      Name: MetagrossMega Metagross
      Type 1: Steel
      Type 2: Psychic
      Total: 700
      HP: 80.0
      Attack: 145.0
      Defense: 150.0
      Sp. Atk: 105.0
      Sp. Def: 110.0
      Speed: 110
      Generation: 3
      Legendary: false
    - index: 414
      '#': 377
      Name: Regirock
      Type 1: Rock
      Type 2: null
      Total: 580
      HP: 80.0
      Attack: 100.0
      Defense: 200.0
      Sp. Atk: 50.0
      Sp. Def: 100.0
      Speed: 50
      Generation: 3
      Legendary: true
    - index: 415
      '#': 378
      Name: Regice
      Type 1: Ice
      Type 2: null
      Total: 580
      HP: 80.0
      Attack: 50.0
      Defense: 100.0
      Sp. Atk: 100.0
      Sp. Def: 200.0
      Speed: 50
      Generation: 3
      Legendary: true
    - index: 416
      '#': 379
      Name: Registeel
      Type 1: Steel
      Type 2: null
      Total: 580
      HP: 80.0
      Attack: 75.0
      Defense: 150.0
      Sp. Atk: 75.0
      Sp. Def: 150.0
      Speed: 50
      Generation: 3
      Legendary: true
    - index: 417
      '#': 380
      Name: Latias
      Type 1: Dragon
      Type 2: Psychic
      Total: 600
      HP: 80.0
      Attack: 80.0
      Defense: 90.0
      Sp. Atk: 110.0
      Sp. Def: 130.0
      Speed: 110
      Generation: 3
      Legendary: true
    - index: 418
      '#': 380
      Name: LatiasMega Latias
      Type 1: Dragon
      Type 2: Psychic
      Total: 700
      HP: 80.0
      Attack: 100.0
      Defense: 120.0
      Sp. Atk: 140.0
      Sp. Def: 150.0
      Speed: 110
      Generation: 3
      Legendary: true
    - index: 419
      '#': 381
      Name: Latios
      Type 1: Dragon
      Type 2: Psychic
      Total: 600
      HP: 80.0
      Attack: 90.0
      Defense: 80.0
      Sp. Atk: 130.0
      Sp. Def: 110.0
      Speed: 110
      Generation: 3
      Legendary: true
    - index: 420
      '#': 381
      Name: LatiosMega Latios
      Type 1: Dragon
      Type 2: Psychic
      Total: 700
      HP: 80.0
      Attack: 130.0
      Defense: 100.0
      Sp. Atk: 160.0
      Sp. Def: 120.0
      Speed: 110
      Generation: 3
      Legendary: true
    - index: 421
      '#': 382
      Name: Kyogre
      Type 1: Water
      Type 2: null
      Total: 670
      HP: 100.0
      Attack: 100.0
      Defense: 90.0
      Sp. Atk: 150.0
      Sp. Def: 140.0
      Speed: 90
      Generation: 3
      Legendary: true
    - index: 422
      '#': 382
      Name: KyogrePrimal Kyogre
      Type 1: Water
      Type 2: null
      Total: 770
      HP: 100.0
      Attack: 150.0
      Defense: 90.0
      Sp. Atk: 180.0
      Sp. Def: 160.0
      Speed: 90
      Generation: 3
      Legendary: true
    - index: 423
      '#': 383
      Name: Groudon
      Type 1: Ground
      Type 2: null
      Total: 670
      HP: 100.0
      Attack: 150.0
      Defense: 140.0
      Sp. Atk: 100.0
      Sp. Def: 90.0
      Speed: 90
      Generation: 3
      Legendary: true
    - index: 424
      '#': 383
      Name: GroudonPrimal Groudon
      Type 1: Ground
      Type 2: Fire
      Total: 770
      HP: 100.0
      Attack: 180.0
      Defense: 160.0
      Sp. Atk: 150.0
      Sp. Def: 90.0
      Speed: 90
      Generation: 3
      Legendary: true
    - index: 425
      '#': 384
      Name: Rayquaza
      Type 1: Dragon
      Type 2: Flying
      Total: 680
      HP: 105.0
      Attack: 150.0
      Defense: 90.0
      Sp. Atk: 150.0
      Sp. Def: 90.0
      Speed: 95
      Generation: 3
      Legendary: true
    - index: 426
      '#': 384
      Name: RayquazaMega Rayquaza
      Type 1: Dragon
      Type 2: Flying
      Total: 780
      HP: 105.0
      Attack: 180.0
      Defense: 100.0
      Sp. Atk: 180.0
      Sp. Def: 100.0
      Speed: 115
      Generation: 3
      Legendary: true
    - index: 427
      '#': 385
      Name: Jirachi
      Type 1: Steel
      Type 2: Psychic
      Total: 600
      HP: 100.0
      Attack: 100.0
      Defense: 100.0
      Sp. Atk: 100.0
      Sp. Def: 100.0
      Speed: 100
      Generation: 3
      Legendary: true
    - index: 428
      '#': 386
      Name: DeoxysNormal Forme
      Type 1: Psychic
      Type 2: null
      Total: 600
      HP: 50.0
      Attack: 150.0
      Defense: 50.0
      Sp. Atk: 150.0
      Sp. Def: 50.0
      Speed: 150
      Generation: 3
      Legendary: true
    - index: 429
      '#': 386
      Name: DeoxysAttack Forme
      Type 1: Psychic
      Type 2: null
      Total: 600
      HP: 50.0
      Attack: 180.0
      Defense: 20.0
      Sp. Atk: 180.0
      Sp. Def: 20.0
      Speed: 150
      Generation: 3
      Legendary: true
    - index: 430
      '#': 386
      Name: DeoxysDefense Forme
      Type 1: Psychic
      Type 2: null
      Total: 600
      HP: 50.0
      Attack: 70.0
      Defense: 160.0
      Sp. Atk: 70.0
      Sp. Def: 160.0
      Speed: 90
      Generation: 3
      Legendary: true
    - index: 431
      '#': 386
      Name: DeoxysSpeed Forme
      Type 1: Psychic
      Type 2: null
      Total: 600
      HP: 50.0
      Attack: 95.0
      Defense: 90.0
      Sp. Atk: 95.0
      Sp. Def: 90.0
      Speed: 180
      Generation: 3
      Legendary: true
    - index: 432
      '#': 387
      Name: Turtwig
      Type 1: Grass
      Type 2: null
      Total: 318
      HP: 55.0
      Attack: 68.0
      Defense: 64.0
      Sp. Atk: 45.0
      Sp. Def: 55.0
      Speed: 31
      Generation: 4
      Legendary: false
    - index: 433
      '#': 388
      Name: Grotle
      Type 1: Grass
      Type 2: null
      Total: 405
      HP: 75.0
      Attack: 89.0
      Defense: 85.0
      Sp. Atk: 55.0
      Sp. Def: 65.0
      Speed: 36
      Generation: 4
      Legendary: false
    - index: 434
      '#': 389
      Name: Torterra
      Type 1: Grass
      Type 2: Ground
      Total: 525
      HP: 95.0
      Attack: 109.0
      Defense: 105.0
      Sp. Atk: 75.0
      Sp. Def: 85.0
      Speed: 56
      Generation: 4
      Legendary: false
    - index: 435
      '#': 390
      Name: Chimchar
      Type 1: Fire
      Type 2: null
      Total: 309
      HP: 44.0
      Attack: 58.0
      Defense: 44.0
      Sp. Atk: 58.0
      Sp. Def: 44.0
      Speed: 61
      Generation: 4
      Legendary: false
    - index: 436
      '#': 391
      Name: Monferno
      Type 1: Fire
      Type 2: Fighting
      Total: 405
      HP: 64.0
      Attack: 78.0
      Defense: 52.0
      Sp. Atk: 78.0
      Sp. Def: 52.0
      Speed: 81
      Generation: 4
      Legendary: false
    - index: 437
      '#': 392
      Name: Infernape
      Type 1: Fire
      Type 2: Fighting
      Total: 534
      HP: 76.0
      Attack: 104.0
      Defense: 71.0
      Sp. Atk: 104.0
      Sp. Def: 71.0
      Speed: 108
      Generation: 4
      Legendary: false
    - index: 438
      '#': 393
      Name: Piplup
      Type 1: Water
      Type 2: null
      Total: 314
      HP: 53.0
      Attack: 51.0
      Defense: 53.0
      Sp. Atk: 61.0
      Sp. Def: 56.0
      Speed: 40
      Generation: 4
      Legendary: false
    - index: 439
      '#': 394
      Name: Prinplup
      Type 1: Water
      Type 2: null
      Total: 405
      HP: 64.0
      Attack: 66.0
      Defense: 68.0
      Sp. Atk: 81.0
      Sp. Def: 76.0
      Speed: 50
      Generation: 4
      Legendary: false
    - index: 440
      '#': 395
      Name: Empoleon
      Type 1: Water
      Type 2: Steel
      Total: 530
      HP: 84.0
      Attack: 86.0
      Defense: 88.0
      Sp. Atk: 111.0
      Sp. Def: 101.0
      Speed: 60
      Generation: 4
      Legendary: false
    - index: 441
      '#': 396
      Name: Starly
      Type 1: Normal
      Type 2: Flying
      Total: 245
      HP: 40.0
      Attack: 55.0
      Defense: 30.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 60
      Generation: 4
      Legendary: false
    - index: 442
      '#': 397
      Name: Staravia
      Type 1: Normal
      Type 2: Flying
      Total: 340
      HP: 55.0
      Attack: 75.0
      Defense: 50.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 80
      Generation: 4
      Legendary: false
    - index: 443
      '#': 398
      Name: Staraptor
      Type 1: Normal
      Type 2: Flying
      Total: 485
      HP: 85.0
      Attack: 120.0
      Defense: 70.0
      Sp. Atk: 50.0
      Sp. Def: 60.0
      Speed: 100
      Generation: 4
      Legendary: false
    - index: 444
      '#': 399
      Name: Bidoof
      Type 1: Normal
      Type 2: null
      Total: 250
      HP: 59.0
      Attack: 45.0
      Defense: 40.0
      Sp. Atk: 35.0
      Sp. Def: 40.0
      Speed: 31
      Generation: 4
      Legendary: false
    - index: 445
      '#': 400
      Name: Bibarel
      Type 1: Normal
      Type 2: Water
      Total: 410
      HP: 79.0
      Attack: 85.0
      Defense: 60.0
      Sp. Atk: 55.0
      Sp. Def: 60.0
      Speed: 71
      Generation: 4
      Legendary: false
    - index: 446
      '#': 401
      Name: Kricketot
      Type 1: Bug
      Type 2: null
      Total: 194
      HP: 37.0
      Attack: 25.0
      Defense: 41.0
      Sp. Atk: 25.0
      Sp. Def: 41.0
      Speed: 25
      Generation: 4
      Legendary: false
    - index: 447
      '#': 402
      Name: Kricketune
      Type 1: Bug
      Type 2: null
      Total: 384
      HP: 77.0
      Attack: 85.0
      Defense: 51.0
      Sp. Atk: 55.0
      Sp. Def: 51.0
      Speed: 65
      Generation: 4
      Legendary: false
    - index: 448
      '#': 403
      Name: Shinx
      Type 1: Electric
      Type 2: null
      Total: 263
      HP: 45.0
      Attack: 65.0
      Defense: 34.0
      Sp. Atk: 40.0
      Sp. Def: 34.0
      Speed: 45
      Generation: 4
      Legendary: false
    - index: 449
      '#': 404
      Name: Luxio
      Type 1: Electric
      Type 2: null
      Total: 363
      HP: 60.0
      Attack: 85.0
      Defense: 49.0
      Sp. Atk: 60.0
      Sp. Def: 49.0
      Speed: 60
      Generation: 4
      Legendary: false
    - index: 450
      '#': 405
      Name: Luxray
      Type 1: Electric
      Type 2: null
      Total: 523
      HP: 80.0
      Attack: 120.0
      Defense: 79.0
      Sp. Atk: 95.0
      Sp. Def: 79.0
      Speed: 70
      Generation: 4
      Legendary: false
    - index: 451
      '#': 406
      Name: Budew
      Type 1: Grass
      Type 2: Poison
      Total: 280
      HP: 40.0
      Attack: 30.0
      Defense: 35.0
      Sp. Atk: 50.0
      Sp. Def: 70.0
      Speed: 55
      Generation: 4
      Legendary: false
    - index: 452
      '#': 407
      Name: Roserade
      Type 1: Grass
      Type 2: Poison
      Total: 515
      HP: 60.0
      Attack: 70.0
      Defense: 65.0
      Sp. Atk: 125.0
      Sp. Def: 105.0
      Speed: 90
      Generation: 4
      Legendary: false
    - index: 453
      '#': 408
      Name: Cranidos
      Type 1: Rock
      Type 2: null
      Total: 350
      HP: 67.0
      Attack: 125.0
      Defense: 40.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 58
      Generation: 4
      Legendary: false
    - index: 454
      '#': 409
      Name: Rampardos
      Type 1: Rock
      Type 2: null
      Total: 495
      HP: 97.0
      Attack: 165.0
      Defense: 60.0
      Sp. Atk: 65.0
      Sp. Def: 50.0
      Speed: 58
      Generation: 4
      Legendary: false
    - index: 455
      '#': 410
      Name: Shieldon
      Type 1: Rock
      Type 2: Steel
      Total: 350
      HP: 30.0
      Attack: 42.0
      Defense: 118.0
      Sp. Atk: 42.0
      Sp. Def: 88.0
      Speed: 30
      Generation: 4
      Legendary: false
    - index: 456
      '#': 411
      Name: Bastiodon
      Type 1: Rock
      Type 2: Steel
      Total: 495
      HP: 60.0
      Attack: 52.0
      Defense: 168.0
      Sp. Atk: 47.0
      Sp. Def: 138.0
      Speed: 30
      Generation: 4
      Legendary: false
    - index: 457
      '#': 412
      Name: Burmy
      Type 1: Bug
      Type 2: null
      Total: 224
      HP: 40.0
      Attack: 29.0
      Defense: 45.0
      Sp. Atk: 29.0
      Sp. Def: 45.0
      Speed: 36
      Generation: 4
      Legendary: false
    - index: 458
      '#': 413
      Name: WormadamPlant Cloak
      Type 1: Bug
      Type 2: Grass
      Total: 424
      HP: 60.0
      Attack: 59.0
      Defense: 85.0
      Sp. Atk: 79.0
      Sp. Def: 105.0
      Speed: 36
      Generation: 4
      Legendary: false
    - index: 459
      '#': 413
      Name: WormadamSandy Cloak
      Type 1: Bug
      Type 2: Ground
      Total: 424
      HP: 60.0
      Attack: 79.0
      Defense: 105.0
      Sp. Atk: 59.0
      Sp. Def: 85.0
      Speed: 36
      Generation: 4
      Legendary: false
    - index: 460
      '#': 413
      Name: WormadamTrash Cloak
      Type 1: Bug
      Type 2: Steel
      Total: 424
      HP: 60.0
      Attack: 69.0
      Defense: 95.0
      Sp. Atk: 69.0
      Sp. Def: 95.0
      Speed: 36
      Generation: 4
      Legendary: false
    - index: 461
      '#': 414
      Name: Mothim
      Type 1: Bug
      Type 2: Flying
      Total: 424
      HP: 70.0
      Attack: 94.0
      Defense: 50.0
      Sp. Atk: 94.0
      Sp. Def: 50.0
      Speed: 66
      Generation: 4
      Legendary: false
    - index: 462
      '#': 415
      Name: Combee
      Type 1: Bug
      Type 2: Flying
      Total: 244
      HP: 30.0
      Attack: 30.0
      Defense: 42.0
      Sp. Atk: 30.0
      Sp. Def: 42.0
      Speed: 70
      Generation: 4
      Legendary: false
    - index: 463
      '#': 416
      Name: Vespiquen
      Type 1: Bug
      Type 2: Flying
      Total: 474
      HP: 70.0
      Attack: 80.0
      Defense: 102.0
      Sp. Atk: 80.0
      Sp. Def: 102.0
      Speed: 40
      Generation: 4
      Legendary: false
    - index: 464
      '#': 417
      Name: Pachirisu
      Type 1: Electric
      Type 2: null
      Total: 405
      HP: 60.0
      Attack: 45.0
      Defense: 70.0
      Sp. Atk: 45.0
      Sp. Def: 90.0
      Speed: 95
      Generation: 4
      Legendary: false
    - index: 465
      '#': 418
      Name: Buizel
      Type 1: Water
      Type 2: null
      Total: 330
      HP: 55.0
      Attack: 65.0
      Defense: 35.0
      Sp. Atk: 60.0
      Sp. Def: 30.0
      Speed: 85
      Generation: 4
      Legendary: false
    - index: 466
      '#': 419
      Name: Floatzel
      Type 1: Water
      Type 2: null
      Total: 495
      HP: 85.0
      Attack: 105.0
      Defense: 55.0
      Sp. Atk: 85.0
      Sp. Def: 50.0
      Speed: 115
      Generation: 4
      Legendary: false
    - index: 467
      '#': 420
      Name: Cherubi
      Type 1: Grass
      Type 2: null
      Total: 275
      HP: 45.0
      Attack: 35.0
      Defense: 45.0
      Sp. Atk: 62.0
      Sp. Def: 53.0
      Speed: 35
      Generation: 4
      Legendary: false
    - index: 468
      '#': 421
      Name: Cherrim
      Type 1: Grass
      Type 2: null
      Total: 450
      HP: 70.0
      Attack: 60.0
      Defense: 70.0
      Sp. Atk: 87.0
      Sp. Def: 78.0
      Speed: 85
      Generation: 4
      Legendary: false
    - index: 469
      '#': 422
      Name: Shellos
      Type 1: Water
      Type 2: null
      Total: 325
      HP: 76.0
      Attack: 48.0
      Defense: 48.0
      Sp. Atk: 57.0
      Sp. Def: 62.0
      Speed: 34
      Generation: 4
      Legendary: false
    - index: 470
      '#': 423
      Name: Gastrodon
      Type 1: Water
      Type 2: Ground
      Total: 475
      HP: 111.0
      Attack: 83.0
      Defense: 68.0
      Sp. Atk: 92.0
      Sp. Def: 82.0
      Speed: 39
      Generation: 4
      Legendary: false
    - index: 471
      '#': 424
      Name: Ambipom
      Type 1: Normal
      Type 2: null
      Total: 482
      HP: 75.0
      Attack: 100.0
      Defense: 66.0
      Sp. Atk: 60.0
      Sp. Def: 66.0
      Speed: 115
      Generation: 4
      Legendary: false
    - index: 472
      '#': 425
      Name: Drifloon
      Type 1: Ghost
      Type 2: Flying
      Total: 348
      HP: 90.0
      Attack: 50.0
      Defense: 34.0
      Sp. Atk: 60.0
      Sp. Def: 44.0
      Speed: 70
      Generation: 4
      Legendary: false
    - index: 473
      '#': 426
      Name: Drifblim
      Type 1: Ghost
      Type 2: Flying
      Total: 498
      HP: 150.0
      Attack: 80.0
      Defense: 44.0
      Sp. Atk: 90.0
      Sp. Def: 54.0
      Speed: 80
      Generation: 4
      Legendary: false
    - index: 474
      '#': 427
      Name: Buneary
      Type 1: Normal
      Type 2: null
      Total: 350
      HP: 55.0
      Attack: 66.0
      Defense: 44.0
      Sp. Atk: 44.0
      Sp. Def: 56.0
      Speed: 85
      Generation: 4
      Legendary: false
    - index: 475
      '#': 428
      Name: Lopunny
      Type 1: Normal
      Type 2: null
      Total: 480
      HP: 65.0
      Attack: 76.0
      Defense: 84.0
      Sp. Atk: 54.0
      Sp. Def: 96.0
      Speed: 105
      Generation: 4
      Legendary: false
    - index: 476
      '#': 428
      Name: LopunnyMega Lopunny
      Type 1: Normal
      Type 2: Fighting
      Total: 580
      HP: 65.0
      Attack: 136.0
      Defense: 94.0
      Sp. Atk: 54.0
      Sp. Def: 96.0
      Speed: 135
      Generation: 4
      Legendary: false
    - index: 477
      '#': 429
      Name: Mismagius
      Type 1: Ghost
      Type 2: null
      Total: 495
      HP: 60.0
      Attack: 60.0
      Defense: 60.0
      Sp. Atk: 105.0
      Sp. Def: 105.0
      Speed: 105
      Generation: 4
      Legendary: false
    - index: 478
      '#': 430
      Name: Honchkrow
      Type 1: Dark
      Type 2: Flying
      Total: 505
      HP: 100.0
      Attack: 125.0
      Defense: 52.0
      Sp. Atk: 105.0
      Sp. Def: 52.0
      Speed: 71
      Generation: 4
      Legendary: false
    - index: 479
      '#': 431
      Name: Glameow
      Type 1: Normal
      Type 2: null
      Total: 310
      HP: 49.0
      Attack: 55.0
      Defense: 42.0
      Sp. Atk: 42.0
      Sp. Def: 37.0
      Speed: 85
      Generation: 4
      Legendary: false
    - index: 480
      '#': 432
      Name: Purugly
      Type 1: Normal
      Type 2: null
      Total: 452
      HP: 71.0
      Attack: 82.0
      Defense: 64.0
      Sp. Atk: 64.0
      Sp. Def: 59.0
      Speed: 112
      Generation: 4
      Legendary: false
    - index: 481
      '#': 433
      Name: Chingling
      Type 1: Psychic
      Type 2: null
      Total: 285
      HP: 45.0
      Attack: 30.0
      Defense: 50.0
      Sp. Atk: 65.0
      Sp. Def: 50.0
      Speed: 45
      Generation: 4
      Legendary: false
    - index: 482
      '#': 434
      Name: Stunky
      Type 1: Poison
      Type 2: Dark
      Total: 329
      HP: 63.0
      Attack: 63.0
      Defense: 47.0
      Sp. Atk: 41.0
      Sp. Def: 41.0
      Speed: 74
      Generation: 4
      Legendary: false
    - index: 483
      '#': 435
      Name: Skuntank
      Type 1: Poison
      Type 2: Dark
      Total: 479
      HP: 103.0
      Attack: 93.0
      Defense: 67.0
      Sp. Atk: 71.0
      Sp. Def: 61.0
      Speed: 84
      Generation: 4
      Legendary: false
    - index: 484
      '#': 436
      Name: Bronzor
      Type 1: Steel
      Type 2: Psychic
      Total: 300
      HP: 57.0
      Attack: 24.0
      Defense: 86.0
      Sp. Atk: 24.0
      Sp. Def: 86.0
      Speed: 23
      Generation: 4
      Legendary: false
    - index: 485
      '#': 437
      Name: Bronzong
      Type 1: Steel
      Type 2: Psychic
      Total: 500
      HP: 67.0
      Attack: 89.0
      Defense: 116.0
      Sp. Atk: 79.0
      Sp. Def: 116.0
      Speed: 33
      Generation: 4
      Legendary: false
    - index: 486
      '#': 438
      Name: Bonsly
      Type 1: Rock
      Type 2: null
      Total: 290
      HP: 50.0
      Attack: 80.0
      Defense: 95.0
      Sp. Atk: 10.0
      Sp. Def: 45.0
      Speed: 10
      Generation: 4
      Legendary: false
    - index: 487
      '#': 439
      Name: Mime Jr.
      Type 1: Psychic
      Type 2: Fairy
      Total: 310
      HP: 20.0
      Attack: 25.0
      Defense: 45.0
      Sp. Atk: 70.0
      Sp. Def: 90.0
      Speed: 60
      Generation: 4
      Legendary: false
    - index: 488
      '#': 440
      Name: Happiny
      Type 1: Normal
      Type 2: null
      Total: 220
      HP: 100.0
      Attack: 5.0
      Defense: 5.0
      Sp. Atk: 15.0
      Sp. Def: 65.0
      Speed: 30
      Generation: 4
      Legendary: false
    - index: 489
      '#': 441
      Name: Chatot
      Type 1: Normal
      Type 2: Flying
      Total: 411
      HP: 76.0
      Attack: 65.0
      Defense: 45.0
      Sp. Atk: 92.0
      Sp. Def: 42.0
      Speed: 91
      Generation: 4
      Legendary: false
    - index: 490
      '#': 442
      Name: Spiritomb
      Type 1: Ghost
      Type 2: Dark
      Total: 485
      HP: 50.0
      Attack: 92.0
      Defense: 108.0
      Sp. Atk: 92.0
      Sp. Def: 108.0
      Speed: 35
      Generation: 4
      Legendary: false
    - index: 491
      '#': 443
      Name: Gible
      Type 1: Dragon
      Type 2: Ground
      Total: 300
      HP: 58.0
      Attack: 70.0
      Defense: 45.0
      Sp. Atk: 40.0
      Sp. Def: 45.0
      Speed: 42
      Generation: 4
      Legendary: false
    - index: 492
      '#': 444
      Name: Gabite
      Type 1: Dragon
      Type 2: Ground
      Total: 410
      HP: 68.0
      Attack: 90.0
      Defense: 65.0
      Sp. Atk: 50.0
      Sp. Def: 55.0
      Speed: 82
      Generation: 4
      Legendary: false
    - index: 493
      '#': 445
      Name: Garchomp
      Type 1: Dragon
      Type 2: Ground
      Total: 600
      HP: 108.0
      Attack: 130.0
      Defense: 95.0
      Sp. Atk: 80.0
      Sp. Def: 85.0
      Speed: 102
      Generation: 4
      Legendary: false
    - index: 494
      '#': 445
      Name: GarchompMega Garchomp
      Type 1: Dragon
      Type 2: Ground
      Total: 700
      HP: 108.0
      Attack: 170.0
      Defense: 115.0
      Sp. Atk: 120.0
      Sp. Def: 95.0
      Speed: 92
      Generation: 4
      Legendary: false
    - index: 495
      '#': 446
      Name: Munchlax
      Type 1: Normal
      Type 2: null
      Total: 390
      HP: 135.0
      Attack: 85.0
      Defense: 40.0
      Sp. Atk: 40.0
      Sp. Def: 85.0
      Speed: 5
      Generation: 4
      Legendary: false
    - index: 496
      '#': 447
      Name: Riolu
      Type 1: Fighting
      Type 2: null
      Total: 285
      HP: 40.0
      Attack: 70.0
      Defense: 40.0
      Sp. Atk: 35.0
      Sp. Def: 40.0
      Speed: 60
      Generation: 4
      Legendary: false
    - index: 497
      '#': 448
      Name: Lucario
      Type 1: Fighting
      Type 2: Steel
      Total: 525
      HP: 70.0
      Attack: 110.0
      Defense: 70.0
      Sp. Atk: 115.0
      Sp. Def: 70.0
      Speed: 90
      Generation: 4
      Legendary: false
    - index: 498
      '#': 448
      Name: LucarioMega Lucario
      Type 1: Fighting
      Type 2: Steel
      Total: 625
      HP: 70.0
      Attack: 145.0
      Defense: 88.0
      Sp. Atk: 140.0
      Sp. Def: 70.0
      Speed: 112
      Generation: 4
      Legendary: false
    - index: 499
      '#': 449
      Name: Hippopotas
      Type 1: Ground
      Type 2: null
      Total: 330
      HP: 68.0
      Attack: 72.0
      Defense: 78.0
      Sp. Atk: 38.0
      Sp. Def: 42.0
      Speed: 32
      Generation: 4
      Legendary: false
    - index: 500
      '#': 450
      Name: Hippowdon
      Type 1: Ground
      Type 2: null
      Total: 525
      HP: 108.0
      Attack: 112.0
      Defense: 118.0
      Sp. Atk: 68.0
      Sp. Def: 72.0
      Speed: 47
      Generation: 4
      Legendary: false
    - index: 501
      '#': 451
      Name: Skorupi
      Type 1: Poison
      Type 2: Bug
      Total: 330
      HP: 40.0
      Attack: 50.0
      Defense: 90.0
      Sp. Atk: 30.0
      Sp. Def: 55.0
      Speed: 65
      Generation: 4
      Legendary: false
    - index: 502
      '#': 452
      Name: Drapion
      Type 1: Poison
      Type 2: Dark
      Total: 500
      HP: 70.0
      Attack: 90.0
      Defense: 110.0
      Sp. Atk: 60.0
      Sp. Def: 75.0
      Speed: 95
      Generation: 4
      Legendary: false
    - index: 503
      '#': 453
      Name: Croagunk
      Type 1: Poison
      Type 2: Fighting
      Total: 300
      HP: 48.0
      Attack: 61.0
      Defense: 40.0
      Sp. Atk: 61.0
      Sp. Def: 40.0
      Speed: 50
      Generation: 4
      Legendary: false
    - index: 504
      '#': 454
      Name: Toxicroak
      Type 1: Poison
      Type 2: Fighting
      Total: 490
      HP: 83.0
      Attack: 106.0
      Defense: 65.0
      Sp. Atk: 86.0
      Sp. Def: 65.0
      Speed: 85
      Generation: 4
      Legendary: false
    - index: 505
      '#': 455
      Name: Carnivine
      Type 1: Grass
      Type 2: null
      Total: 454
      HP: 74.0
      Attack: 100.0
      Defense: 72.0
      Sp. Atk: 90.0
      Sp. Def: 72.0
      Speed: 46
      Generation: 4
      Legendary: false
    - index: 506
      '#': 456
      Name: Finneon
      Type 1: Water
      Type 2: null
      Total: 330
      HP: 49.0
      Attack: 49.0
      Defense: 56.0
      Sp. Atk: 49.0
      Sp. Def: 61.0
      Speed: 66
      Generation: 4
      Legendary: false
    - index: 507
      '#': 457
      Name: Lumineon
      Type 1: Water
      Type 2: null
      Total: 460
      HP: 69.0
      Attack: 69.0
      Defense: 76.0
      Sp. Atk: 69.0
      Sp. Def: 86.0
      Speed: 91
      Generation: 4
      Legendary: false
    - index: 508
      '#': 458
      Name: Mantyke
      Type 1: Water
      Type 2: Flying
      Total: 345
      HP: 45.0
      Attack: 20.0
      Defense: 50.0
      Sp. Atk: 60.0
      Sp. Def: 120.0
      Speed: 50
      Generation: 4
      Legendary: false
    - index: 509
      '#': 459
      Name: Snover
      Type 1: Grass
      Type 2: Ice
      Total: 334
      HP: 60.0
      Attack: 62.0
      Defense: 50.0
      Sp. Atk: 62.0
      Sp. Def: 60.0
      Speed: 40
      Generation: 4
      Legendary: false
    - index: 510
      '#': 460
      Name: Abomasnow
      Type 1: Grass
      Type 2: Ice
      Total: 494
      HP: 90.0
      Attack: 92.0
      Defense: 75.0
      Sp. Atk: 92.0
      Sp. Def: 85.0
      Speed: 60
      Generation: 4
      Legendary: false
    - index: 511
      '#': 460
      Name: AbomasnowMega Abomasnow
      Type 1: Grass
      Type 2: Ice
      Total: 594
      HP: 90.0
      Attack: 132.0
      Defense: 105.0
      Sp. Atk: 132.0
      Sp. Def: 105.0
      Speed: 30
      Generation: 4
      Legendary: false
    - index: 512
      '#': 461
      Name: Weavile
      Type 1: Dark
      Type 2: Ice
      Total: 510
      HP: 70.0
      Attack: 120.0
      Defense: 65.0
      Sp. Atk: 45.0
      Sp. Def: 85.0
      Speed: 125
      Generation: 4
      Legendary: false
    - index: 513
      '#': 462
      Name: Magnezone
      Type 1: Electric
      Type 2: Steel
      Total: 535
      HP: 70.0
      Attack: 70.0
      Defense: 115.0
      Sp. Atk: 130.0
      Sp. Def: 90.0
      Speed: 60
      Generation: 4
      Legendary: false
    - index: 514
      '#': 463
      Name: Lickilicky
      Type 1: Normal
      Type 2: null
      Total: 515
      HP: 110.0
      Attack: 85.0
      Defense: 95.0
      Sp. Atk: 80.0
      Sp. Def: 95.0
      Speed: 50
      Generation: 4
      Legendary: false
    - index: 515
      '#': 464
      Name: Rhyperior
      Type 1: Ground
      Type 2: Rock
      Total: 535
      HP: 115.0
      Attack: 140.0
      Defense: 130.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 40
      Generation: 4
      Legendary: false
    - index: 516
      '#': 465
      Name: Tangrowth
      Type 1: Grass
      Type 2: null
      Total: 535
      HP: 100.0
      Attack: 100.0
      Defense: 125.0
      Sp. Atk: 110.0
      Sp. Def: 50.0
      Speed: 50
      Generation: 4
      Legendary: false
    - index: 517
      '#': 466
      Name: Electivire
      Type 1: Electric
      Type 2: null
      Total: 540
      HP: 75.0
      Attack: 123.0
      Defense: 67.0
      Sp. Atk: 95.0
      Sp. Def: 85.0
      Speed: 95
      Generation: 4
      Legendary: false
    - index: 518
      '#': 467
      Name: Magmortar
      Type 1: Fire
      Type 2: null
      Total: 540
      HP: 75.0
      Attack: 95.0
      Defense: 67.0
      Sp. Atk: 125.0
      Sp. Def: 95.0
      Speed: 83
      Generation: 4
      Legendary: false
    - index: 519
      '#': 468
      Name: Togekiss
      Type 1: Fairy
      Type 2: Flying
      Total: 545
      HP: 85.0
      Attack: 50.0
      Defense: 95.0
      Sp. Atk: 120.0
      Sp. Def: 115.0
      Speed: 80
      Generation: 4
      Legendary: false
    - index: 520
      '#': 469
      Name: Yanmega
      Type 1: Bug
      Type 2: Flying
      Total: 515
      HP: 86.0
      Attack: 76.0
      Defense: 86.0
      Sp. Atk: 116.0
      Sp. Def: 56.0
      Speed: 95
      Generation: 4
      Legendary: false
    - index: 521
      '#': 470
      Name: Leafeon
      Type 1: Grass
      Type 2: null
      Total: 525
      HP: 65.0
      Attack: 110.0
      Defense: 130.0
      Sp. Atk: 60.0
      Sp. Def: 65.0
      Speed: 95
      Generation: 4
      Legendary: false
    - index: 522
      '#': 471
      Name: Glaceon
      Type 1: Ice
      Type 2: null
      Total: 525
      HP: 65.0
      Attack: 60.0
      Defense: 110.0
      Sp. Atk: 130.0
      Sp. Def: 95.0
      Speed: 65
      Generation: 4
      Legendary: false
    - index: 523
      '#': 472
      Name: Gliscor
      Type 1: Ground
      Type 2: Flying
      Total: 510
      HP: 75.0
      Attack: 95.0
      Defense: 125.0
      Sp. Atk: 45.0
      Sp. Def: 75.0
      Speed: 95
      Generation: 4
      Legendary: false
    - index: 524
      '#': 473
      Name: Mamoswine
      Type 1: Ice
      Type 2: Ground
      Total: 530
      HP: 110.0
      Attack: 130.0
      Defense: 80.0
      Sp. Atk: 70.0
      Sp. Def: 60.0
      Speed: 80
      Generation: 4
      Legendary: false
    - index: 525
      '#': 474
      Name: Porygon-Z
      Type 1: Normal
      Type 2: null
      Total: 535
      HP: 85.0
      Attack: 80.0
      Defense: 70.0
      Sp. Atk: 135.0
      Sp. Def: 75.0
      Speed: 90
      Generation: 4
      Legendary: false
    - index: 526
      '#': 475
      Name: Gallade
      Type 1: Psychic
      Type 2: Fighting
      Total: 518
      HP: 68.0
      Attack: 125.0
      Defense: 65.0
      Sp. Atk: 65.0
      Sp. Def: 115.0
      Speed: 80
      Generation: 4
      Legendary: false
    - index: 527
      '#': 475
      Name: GalladeMega Gallade
      Type 1: Psychic
      Type 2: Fighting
      Total: 618
      HP: 68.0
      Attack: 165.0
      Defense: 95.0
      Sp. Atk: 65.0
      Sp. Def: 115.0
      Speed: 110
      Generation: 4
      Legendary: false
    - index: 528
      '#': 476
      Name: Probopass
      Type 1: Rock
      Type 2: Steel
      Total: 525
      HP: 60.0
      Attack: 55.0
      Defense: 145.0
      Sp. Atk: 75.0
      Sp. Def: 150.0
      Speed: 40
      Generation: 4
      Legendary: false
    - index: 529
      '#': 477
      Name: Dusknoir
      Type 1: Ghost
      Type 2: null
      Total: 525
      HP: 45.0
      Attack: 100.0
      Defense: 135.0
      Sp. Atk: 65.0
      Sp. Def: 135.0
      Speed: 45
      Generation: 4
      Legendary: false
    - index: 530
      '#': 478
      Name: Froslass
      Type 1: Ice
      Type 2: Ghost
      Total: 480
      HP: 70.0
      Attack: 80.0
      Defense: 70.0
      Sp. Atk: 80.0
      Sp. Def: 70.0
      Speed: 110
      Generation: 4
      Legendary: false
    - index: 531
      '#': 479
      Name: Rotom
      Type 1: Electric
      Type 2: Ghost
      Total: 440
      HP: 50.0
      Attack: 50.0
      Defense: 77.0
      Sp. Atk: 95.0
      Sp. Def: 77.0
      Speed: 91
      Generation: 4
      Legendary: false
    - index: 532
      '#': 479
      Name: RotomHeat Rotom
      Type 1: Electric
      Type 2: Fire
      Total: 520
      HP: 50.0
      Attack: 65.0
      Defense: 107.0
      Sp. Atk: 105.0
      Sp. Def: 107.0
      Speed: 86
      Generation: 4
      Legendary: false
    - index: 533
      '#': 479
      Name: RotomWash Rotom
      Type 1: Electric
      Type 2: Water
      Total: 520
      HP: 50.0
      Attack: 65.0
      Defense: 107.0
      Sp. Atk: 105.0
      Sp. Def: 107.0
      Speed: 86
      Generation: 4
      Legendary: false
    - index: 534
      '#': 479
      Name: RotomFrost Rotom
      Type 1: Electric
      Type 2: Ice
      Total: 520
      HP: 50.0
      Attack: 65.0
      Defense: 107.0
      Sp. Atk: 105.0
      Sp. Def: 107.0
      Speed: 86
      Generation: 4
      Legendary: false
    - index: 535
      '#': 479
      Name: RotomFan Rotom
      Type 1: Electric
      Type 2: Flying
      Total: 520
      HP: 50.0
      Attack: 65.0
      Defense: 107.0
      Sp. Atk: 105.0
      Sp. Def: 107.0
      Speed: 86
      Generation: 4
      Legendary: false
    - index: 536
      '#': 479
      Name: RotomMow Rotom
      Type 1: Electric
      Type 2: Grass
      Total: 520
      HP: 50.0
      Attack: 65.0
      Defense: 107.0
      Sp. Atk: 105.0
      Sp. Def: 107.0
      Speed: 86
      Generation: 4
      Legendary: false
    - index: 537
      '#': 480
      Name: Uxie
      Type 1: Psychic
      Type 2: null
      Total: 580
      HP: 75.0
      Attack: 75.0
      Defense: 130.0
      Sp. Atk: 75.0
      Sp. Def: 130.0
      Speed: 95
      Generation: 4
      Legendary: true
    - index: 538
      '#': 481
      Name: Mesprit
      Type 1: Psychic
      Type 2: null
      Total: 580
      HP: 80.0
      Attack: 105.0
      Defense: 105.0
      Sp. Atk: 105.0
      Sp. Def: 105.0
      Speed: 80
      Generation: 4
      Legendary: true
    - index: 539
      '#': 482
      Name: Azelf
      Type 1: Psychic
      Type 2: null
      Total: 580
      HP: 75.0
      Attack: 125.0
      Defense: 70.0
      Sp. Atk: 125.0
      Sp. Def: 70.0
      Speed: 115
      Generation: 4
      Legendary: true
    - index: 540
      '#': 483
      Name: Dialga
      Type 1: Steel
      Type 2: Dragon
      Total: 680
      HP: 100.0
      Attack: 120.0
      Defense: 120.0
      Sp. Atk: 150.0
      Sp. Def: 100.0
      Speed: 90
      Generation: 4
      Legendary: true
    - index: 541
      '#': 484
      Name: Palkia
      Type 1: Water
      Type 2: Dragon
      Total: 680
      HP: 90.0
      Attack: 120.0
      Defense: 100.0
      Sp. Atk: 150.0
      Sp. Def: 120.0
      Speed: 100
      Generation: 4
      Legendary: true
    - index: 542
      '#': 485
      Name: Heatran
      Type 1: Fire
      Type 2: Steel
      Total: 600
      HP: 91.0
      Attack: 90.0
      Defense: 106.0
      Sp. Atk: 130.0
      Sp. Def: 106.0
      Speed: 77
      Generation: 4
      Legendary: true
    - index: 543
      '#': 486
      Name: Regigigas
      Type 1: Normal
      Type 2: null
      Total: 670
      HP: 110.0
      Attack: 160.0
      Defense: 110.0
      Sp. Atk: 80.0
      Sp. Def: 110.0
      Speed: 100
      Generation: 4
      Legendary: true
    - index: 544
      '#': 487
      Name: GiratinaAltered Forme
      Type 1: Ghost
      Type 2: Dragon
      Total: 680
      HP: 150.0
      Attack: 100.0
      Defense: 120.0
      Sp. Atk: 100.0
      Sp. Def: 120.0
      Speed: 90
      Generation: 4
      Legendary: true
    - index: 545
      '#': 487
      Name: GiratinaOrigin Forme
      Type 1: Ghost
      Type 2: Dragon
      Total: 680
      HP: 150.0
      Attack: 120.0
      Defense: 100.0
      Sp. Atk: 120.0
      Sp. Def: 100.0
      Speed: 90
      Generation: 4
      Legendary: true
    - index: 546
      '#': 488
      Name: Cresselia
      Type 1: Psychic
      Type 2: null
      Total: 600
      HP: 120.0
      Attack: 70.0
      Defense: 120.0
      Sp. Atk: 75.0
      Sp. Def: 130.0
      Speed: 85
      Generation: 4
      Legendary: false
    - index: 547
      '#': 489
      Name: Phione
      Type 1: Water
      Type 2: null
      Total: 480
      HP: 80.0
      Attack: 80.0
      Defense: 80.0
      Sp. Atk: 80.0
      Sp. Def: 80.0
      Speed: 80
      Generation: 4
      Legendary: false
    - index: 548
      '#': 490
      Name: Manaphy
      Type 1: Water
      Type 2: null
      Total: 600
      HP: 100.0
      Attack: 100.0
      Defense: 100.0
      Sp. Atk: 100.0
      Sp. Def: 100.0
      Speed: 100
      Generation: 4
      Legendary: false
    - index: 549
      '#': 491
      Name: Darkrai
      Type 1: Dark
      Type 2: null
      Total: 600
      HP: 70.0
      Attack: 90.0
      Defense: 90.0
      Sp. Atk: 135.0
      Sp. Def: 90.0
      Speed: 125
      Generation: 4
      Legendary: true
    - index: 550
      '#': 492
      Name: ShayminLand Forme
      Type 1: Grass
      Type 2: null
      Total: 600
      HP: 100.0
      Attack: 100.0
      Defense: 100.0
      Sp. Atk: 100.0
      Sp. Def: 100.0
      Speed: 100
      Generation: 4
      Legendary: true
    - index: 551
      '#': 492
      Name: ShayminSky Forme
      Type 1: Grass
      Type 2: Flying
      Total: 600
      HP: 100.0
      Attack: 103.0
      Defense: 75.0
      Sp. Atk: 120.0
      Sp. Def: 75.0
      Speed: 127
      Generation: 4
      Legendary: true
    - index: 552
      '#': 493
      Name: Arceus
      Type 1: Normal
      Type 2: null
      Total: 720
      HP: 120.0
      Attack: 120.0
      Defense: 120.0
      Sp. Atk: 120.0
      Sp. Def: 120.0
      Speed: 120
      Generation: 4
      Legendary: true
    - index: 553
      '#': 494
      Name: Victini
      Type 1: Psychic
      Type 2: Fire
      Total: 600
      HP: 100.0
      Attack: 100.0
      Defense: 100.0
      Sp. Atk: 100.0
      Sp. Def: 100.0
      Speed: 100
      Generation: 5
      Legendary: true
    - index: 554
      '#': 495
      Name: Snivy
      Type 1: Grass
      Type 2: null
      Total: 308
      HP: 45.0
      Attack: 45.0
      Defense: 55.0
      Sp. Atk: 45.0
      Sp. Def: 55.0
      Speed: 63
      Generation: 5
      Legendary: false
    - index: 555
      '#': 496
      Name: Servine
      Type 1: Grass
      Type 2: null
      Total: 413
      HP: 60.0
      Attack: 60.0
      Defense: 75.0
      Sp. Atk: 60.0
      Sp. Def: 75.0
      Speed: 83
      Generation: 5
      Legendary: false
    - index: 556
      '#': 497
      Name: Serperior
      Type 1: Grass
      Type 2: null
      Total: 528
      HP: 75.0
      Attack: 75.0
      Defense: 95.0
      Sp. Atk: 75.0
      Sp. Def: 95.0
      Speed: 113
      Generation: 5
      Legendary: false
    - index: 557
      '#': 498
      Name: Tepig
      Type 1: Fire
      Type 2: null
      Total: 308
      HP: 65.0
      Attack: 63.0
      Defense: 45.0
      Sp. Atk: 45.0
      Sp. Def: 45.0
      Speed: 45
      Generation: 5
      Legendary: false
    - index: 558
      '#': 499
      Name: Pignite
      Type 1: Fire
      Type 2: Fighting
      Total: 418
      HP: 90.0
      Attack: 93.0
      Defense: 55.0
      Sp. Atk: 70.0
      Sp. Def: 55.0
      Speed: 55
      Generation: 5
      Legendary: false
    - index: 559
      '#': 500
      Name: Emboar
      Type 1: Fire
      Type 2: Fighting
      Total: 528
      HP: 110.0
      Attack: 123.0
      Defense: 65.0
      Sp. Atk: 100.0
      Sp. Def: 65.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 560
      '#': 501
      Name: Oshawott
      Type 1: Water
      Type 2: null
      Total: 308
      HP: 55.0
      Attack: 55.0
      Defense: 45.0
      Sp. Atk: 63.0
      Sp. Def: 45.0
      Speed: 45
      Generation: 5
      Legendary: false
    - index: 561
      '#': 502
      Name: Dewott
      Type 1: Water
      Type 2: null
      Total: 413
      HP: 75.0
      Attack: 75.0
      Defense: 60.0
      Sp. Atk: 83.0
      Sp. Def: 60.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 562
      '#': 503
      Name: Samurott
      Type 1: Water
      Type 2: null
      Total: 528
      HP: 95.0
      Attack: 100.0
      Defense: 85.0
      Sp. Atk: 108.0
      Sp. Def: 70.0
      Speed: 70
      Generation: 5
      Legendary: false
    - index: 563
      '#': 504
      Name: Patrat
      Type 1: Normal
      Type 2: null
      Total: 255
      HP: 45.0
      Attack: 55.0
      Defense: 39.0
      Sp. Atk: 35.0
      Sp. Def: 39.0
      Speed: 42
      Generation: 5
      Legendary: false
    - index: 564
      '#': 505
      Name: Watchog
      Type 1: Normal
      Type 2: null
      Total: 420
      HP: 60.0
      Attack: 85.0
      Defense: 69.0
      Sp. Atk: 60.0
      Sp. Def: 69.0
      Speed: 77
      Generation: 5
      Legendary: false
    - index: 565
      '#': 506
      Name: Lillipup
      Type 1: Normal
      Type 2: null
      Total: 275
      HP: 45.0
      Attack: 60.0
      Defense: 45.0
      Sp. Atk: 25.0
      Sp. Def: 45.0
      Speed: 55
      Generation: 5
      Legendary: false
    - index: 566
      '#': 507
      Name: Herdier
      Type 1: Normal
      Type 2: null
      Total: 370
      HP: 65.0
      Attack: 80.0
      Defense: 65.0
      Sp. Atk: 35.0
      Sp. Def: 65.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 567
      '#': 508
      Name: Stoutland
      Type 1: Normal
      Type 2: null
      Total: 500
      HP: 85.0
      Attack: 110.0
      Defense: 90.0
      Sp. Atk: 45.0
      Sp. Def: 90.0
      Speed: 80
      Generation: 5
      Legendary: false
    - index: 568
      '#': 509
      Name: Purrloin
      Type 1: Dark
      Type 2: null
      Total: 281
      HP: 41.0
      Attack: 50.0
      Defense: 37.0
      Sp. Atk: 50.0
      Sp. Def: 37.0
      Speed: 66
      Generation: 5
      Legendary: false
    - index: 569
      '#': 510
      Name: Liepard
      Type 1: Dark
      Type 2: null
      Total: 446
      HP: 64.0
      Attack: 88.0
      Defense: 50.0
      Sp. Atk: 88.0
      Sp. Def: 50.0
      Speed: 106
      Generation: 5
      Legendary: false
    - index: 570
      '#': 511
      Name: Pansage
      Type 1: Grass
      Type 2: null
      Total: 316
      HP: 50.0
      Attack: 53.0
      Defense: 48.0
      Sp. Atk: 53.0
      Sp. Def: 48.0
      Speed: 64
      Generation: 5
      Legendary: false
    - index: 571
      '#': 512
      Name: Simisage
      Type 1: Grass
      Type 2: null
      Total: 498
      HP: 75.0
      Attack: 98.0
      Defense: 63.0
      Sp. Atk: 98.0
      Sp. Def: 63.0
      Speed: 101
      Generation: 5
      Legendary: false
    - index: 572
      '#': 513
      Name: Pansear
      Type 1: Fire
      Type 2: null
      Total: 316
      HP: 50.0
      Attack: 53.0
      Defense: 48.0
      Sp. Atk: 53.0
      Sp. Def: 48.0
      Speed: 64
      Generation: 5
      Legendary: false
    - index: 573
      '#': 514
      Name: Simisear
      Type 1: Fire
      Type 2: null
      Total: 498
      HP: 75.0
      Attack: 98.0
      Defense: 63.0
      Sp. Atk: 98.0
      Sp. Def: 63.0
      Speed: 101
      Generation: 5
      Legendary: false
    - index: 574
      '#': 515
      Name: Panpour
      Type 1: Water
      Type 2: null
      Total: 316
      HP: 50.0
      Attack: 53.0
      Defense: 48.0
      Sp. Atk: 53.0
      Sp. Def: 48.0
      Speed: 64
      Generation: 5
      Legendary: false
    - index: 575
      '#': 516
      Name: Simipour
      Type 1: Water
      Type 2: null
      Total: 498
      HP: 75.0
      Attack: 98.0
      Defense: 63.0
      Sp. Atk: 98.0
      Sp. Def: 63.0
      Speed: 101
      Generation: 5
      Legendary: false
    - index: 576
      '#': 517
      Name: Munna
      Type 1: Psychic
      Type 2: null
      Total: 292
      HP: 76.0
      Attack: 25.0
      Defense: 45.0
      Sp. Atk: 67.0
      Sp. Def: 55.0
      Speed: 24
      Generation: 5
      Legendary: false
    - index: 577
      '#': 518
      Name: Musharna
      Type 1: Psychic
      Type 2: null
      Total: 487
      HP: 116.0
      Attack: 55.0
      Defense: 85.0
      Sp. Atk: 107.0
      Sp. Def: 95.0
      Speed: 29
      Generation: 5
      Legendary: false
    - index: 578
      '#': 519
      Name: Pidove
      Type 1: Normal
      Type 2: Flying
      Total: 264
      HP: 50.0
      Attack: 55.0
      Defense: 50.0
      Sp. Atk: 36.0
      Sp. Def: 30.0
      Speed: 43
      Generation: 5
      Legendary: false
    - index: 579
      '#': 520
      Name: Tranquill
      Type 1: Normal
      Type 2: Flying
      Total: 358
      HP: 62.0
      Attack: 77.0
      Defense: 62.0
      Sp. Atk: 50.0
      Sp. Def: 42.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 580
      '#': 521
      Name: Unfezant
      Type 1: Normal
      Type 2: Flying
      Total: 488
      HP: 80.0
      Attack: 115.0
      Defense: 80.0
      Sp. Atk: 65.0
      Sp. Def: 55.0
      Speed: 93
      Generation: 5
      Legendary: false
    - index: 581
      '#': 522
      Name: Blitzle
      Type 1: Electric
      Type 2: null
      Total: 295
      HP: 45.0
      Attack: 60.0
      Defense: 32.0
      Sp. Atk: 50.0
      Sp. Def: 32.0
      Speed: 76
      Generation: 5
      Legendary: false
    - index: 582
      '#': 523
      Name: Zebstrika
      Type 1: Electric
      Type 2: null
      Total: 497
      HP: 75.0
      Attack: 100.0
      Defense: 63.0
      Sp. Atk: 80.0
      Sp. Def: 63.0
      Speed: 116
      Generation: 5
      Legendary: false
    - index: 583
      '#': 524
      Name: Roggenrola
      Type 1: Rock
      Type 2: null
      Total: 280
      HP: 55.0
      Attack: 75.0
      Defense: 85.0
      Sp. Atk: 25.0
      Sp. Def: 25.0
      Speed: 15
      Generation: 5
      Legendary: false
    - index: 584
      '#': 525
      Name: Boldore
      Type 1: Rock
      Type 2: null
      Total: 390
      HP: 70.0
      Attack: 105.0
      Defense: 105.0
      Sp. Atk: 50.0
      Sp. Def: 40.0
      Speed: 20
      Generation: 5
      Legendary: false
    - index: 585
      '#': 526
      Name: Gigalith
      Type 1: Rock
      Type 2: null
      Total: 515
      HP: 85.0
      Attack: 135.0
      Defense: 130.0
      Sp. Atk: 60.0
      Sp. Def: 80.0
      Speed: 25
      Generation: 5
      Legendary: false
    - index: 586
      '#': 527
      Name: Woobat
      Type 1: Psychic
      Type 2: Flying
      Total: 313
      HP: 55.0
      Attack: 45.0
      Defense: 43.0
      Sp. Atk: 55.0
      Sp. Def: 43.0
      Speed: 72
      Generation: 5
      Legendary: false
    - index: 587
      '#': 528
      Name: Swoobat
      Type 1: Psychic
      Type 2: Flying
      Total: 425
      HP: 67.0
      Attack: 57.0
      Defense: 55.0
      Sp. Atk: 77.0
      Sp. Def: 55.0
      Speed: 114
      Generation: 5
      Legendary: false
    - index: 588
      '#': 529
      Name: Drilbur
      Type 1: Ground
      Type 2: null
      Total: 328
      HP: 60.0
      Attack: 85.0
      Defense: 40.0
      Sp. Atk: 30.0
      Sp. Def: 45.0
      Speed: 68
      Generation: 5
      Legendary: false
    - index: 589
      '#': 530
      Name: Excadrill
      Type 1: Ground
      Type 2: Steel
      Total: 508
      HP: 110.0
      Attack: 135.0
      Defense: 60.0
      Sp. Atk: 50.0
      Sp. Def: 65.0
      Speed: 88
      Generation: 5
      Legendary: false
    - index: 590
      '#': 531
      Name: Audino
      Type 1: Normal
      Type 2: null
      Total: 445
      HP: 103.0
      Attack: 60.0
      Defense: 86.0
      Sp. Atk: 60.0
      Sp. Def: 86.0
      Speed: 50
      Generation: 5
      Legendary: false
    - index: 591
      '#': 531
      Name: AudinoMega Audino
      Type 1: Normal
      Type 2: Fairy
      Total: 545
      HP: 103.0
      Attack: 60.0
      Defense: 126.0
      Sp. Atk: 80.0
      Sp. Def: 126.0
      Speed: 50
      Generation: 5
      Legendary: false
    - index: 592
      '#': 532
      Name: Timburr
      Type 1: Fighting
      Type 2: null
      Total: 305
      HP: 75.0
      Attack: 80.0
      Defense: 55.0
      Sp. Atk: 25.0
      Sp. Def: 35.0
      Speed: 35
      Generation: 5
      Legendary: false
    - index: 593
      '#': 533
      Name: Gurdurr
      Type 1: Fighting
      Type 2: null
      Total: 405
      HP: 85.0
      Attack: 105.0
      Defense: 85.0
      Sp. Atk: 40.0
      Sp. Def: 50.0
      Speed: 40
      Generation: 5
      Legendary: false
    - index: 594
      '#': 534
      Name: Conkeldurr
      Type 1: Fighting
      Type 2: null
      Total: 505
      HP: 105.0
      Attack: 140.0
      Defense: 95.0
      Sp. Atk: 55.0
      Sp. Def: 65.0
      Speed: 45
      Generation: 5
      Legendary: false
    - index: 595
      '#': 535
      Name: Tympole
      Type 1: Water
      Type 2: null
      Total: 294
      HP: 50.0
      Attack: 50.0
      Defense: 40.0
      Sp. Atk: 50.0
      Sp. Def: 40.0
      Speed: 64
      Generation: 5
      Legendary: false
    - index: 596
      '#': 536
      Name: Palpitoad
      Type 1: Water
      Type 2: Ground
      Total: 384
      HP: 75.0
      Attack: 65.0
      Defense: 55.0
      Sp. Atk: 65.0
      Sp. Def: 55.0
      Speed: 69
      Generation: 5
      Legendary: false
    - index: 597
      '#': 537
      Name: Seismitoad
      Type 1: Water
      Type 2: Ground
      Total: 509
      HP: 105.0
      Attack: 95.0
      Defense: 75.0
      Sp. Atk: 85.0
      Sp. Def: 75.0
      Speed: 74
      Generation: 5
      Legendary: false
    - index: 598
      '#': 538
      Name: Throh
      Type 1: Fighting
      Type 2: null
      Total: 465
      HP: 120.0
      Attack: 100.0
      Defense: 85.0
      Sp. Atk: 30.0
      Sp. Def: 85.0
      Speed: 45
      Generation: 5
      Legendary: false
    - index: 599
      '#': 539
      Name: Sawk
      Type 1: Fighting
      Type 2: null
      Total: 465
      HP: 75.0
      Attack: 125.0
      Defense: 75.0
      Sp. Atk: 30.0
      Sp. Def: 75.0
      Speed: 85
      Generation: 5
      Legendary: false
    - index: 600
      '#': 540
      Name: Sewaddle
      Type 1: Bug
      Type 2: Grass
      Total: 310
      HP: 45.0
      Attack: 53.0
      Defense: 70.0
      Sp. Atk: 40.0
      Sp. Def: 60.0
      Speed: 42
      Generation: 5
      Legendary: false
    - index: 601
      '#': 541
      Name: Swadloon
      Type 1: Bug
      Type 2: Grass
      Total: 380
      HP: 55.0
      Attack: 63.0
      Defense: 90.0
      Sp. Atk: 50.0
      Sp. Def: 80.0
      Speed: 42
      Generation: 5
      Legendary: false
    - index: 602
      '#': 542
      Name: Leavanny
      Type 1: Bug
      Type 2: Grass
      Total: 500
      HP: 75.0
      Attack: 103.0
      Defense: 80.0
      Sp. Atk: 70.0
      Sp. Def: 80.0
      Speed: 92
      Generation: 5
      Legendary: false
    - index: 603
      '#': 543
      Name: Venipede
      Type 1: Bug
      Type 2: Poison
      Total: 260
      HP: 30.0
      Attack: 45.0
      Defense: 59.0
      Sp. Atk: 30.0
      Sp. Def: 39.0
      Speed: 57
      Generation: 5
      Legendary: false
    - index: 604
      '#': 544
      Name: Whirlipede
      Type 1: Bug
      Type 2: Poison
      Total: 360
      HP: 40.0
      Attack: 55.0
      Defense: 99.0
      Sp. Atk: 40.0
      Sp. Def: 79.0
      Speed: 47
      Generation: 5
      Legendary: false
    - index: 605
      '#': 545
      Name: Scolipede
      Type 1: Bug
      Type 2: Poison
      Total: 485
      HP: 60.0
      Attack: 100.0
      Defense: 89.0
      Sp. Atk: 55.0
      Sp. Def: 69.0
      Speed: 112
      Generation: 5
      Legendary: false
    - index: 606
      '#': 546
      Name: Cottonee
      Type 1: Grass
      Type 2: Fairy
      Total: 280
      HP: 40.0
      Attack: 27.0
      Defense: 60.0
      Sp. Atk: 37.0
      Sp. Def: 50.0
      Speed: 66
      Generation: 5
      Legendary: false
    - index: 607
      '#': 547
      Name: Whimsicott
      Type 1: Grass
      Type 2: Fairy
      Total: 480
      HP: 60.0
      Attack: 67.0
      Defense: 85.0
      Sp. Atk: 77.0
      Sp. Def: 75.0
      Speed: 116
      Generation: 5
      Legendary: false
    - index: 608
      '#': 548
      Name: Petilil
      Type 1: Grass
      Type 2: null
      Total: 280
      HP: 45.0
      Attack: 35.0
      Defense: 50.0
      Sp. Atk: 70.0
      Sp. Def: 50.0
      Speed: 30
      Generation: 5
      Legendary: false
    - index: 609
      '#': 549
      Name: Lilligant
      Type 1: Grass
      Type 2: null
      Total: 480
      HP: 70.0
      Attack: 60.0
      Defense: 75.0
      Sp. Atk: 110.0
      Sp. Def: 75.0
      Speed: 90
      Generation: 5
      Legendary: false
    - index: 610
      '#': 550
      Name: Basculin
      Type 1: Water
      Type 2: null
      Total: 460
      HP: 70.0
      Attack: 92.0
      Defense: 65.0
      Sp. Atk: 80.0
      Sp. Def: 55.0
      Speed: 98
      Generation: 5
      Legendary: false
    - index: 611
      '#': 551
      Name: Sandile
      Type 1: Ground
      Type 2: Dark
      Total: 292
      HP: 50.0
      Attack: 72.0
      Defense: 35.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 612
      '#': 552
      Name: Krokorok
      Type 1: Ground
      Type 2: Dark
      Total: 351
      HP: 60.0
      Attack: 82.0
      Defense: 45.0
      Sp. Atk: 45.0
      Sp. Def: 45.0
      Speed: 74
      Generation: 5
      Legendary: false
    - index: 613
      '#': 553
      Name: Krookodile
      Type 1: Ground
      Type 2: Dark
      Total: 519
      HP: 95.0
      Attack: 117.0
      Defense: 80.0
      Sp. Atk: 65.0
      Sp. Def: 70.0
      Speed: 92
      Generation: 5
      Legendary: false
    - index: 614
      '#': 554
      Name: Darumaka
      Type 1: Fire
      Type 2: null
      Total: 315
      HP: 70.0
      Attack: 90.0
      Defense: 45.0
      Sp. Atk: 15.0
      Sp. Def: 45.0
      Speed: 50
      Generation: 5
      Legendary: false
    - index: 615
      '#': 555
      Name: DarmanitanStandard Mode
      Type 1: Fire
      Type 2: null
      Total: 480
      HP: 105.0
      Attack: 140.0
      Defense: 55.0
      Sp. Atk: 30.0
      Sp. Def: 55.0
      Speed: 95
      Generation: 5
      Legendary: false
    - index: 616
      '#': 555
      Name: DarmanitanZen Mode
      Type 1: Fire
      Type 2: Psychic
      Total: 540
      HP: 105.0
      Attack: 30.0
      Defense: 105.0
      Sp. Atk: 140.0
      Sp. Def: 105.0
      Speed: 55
      Generation: 5
      Legendary: false
    - index: 617
      '#': 556
      Name: Maractus
      Type 1: Grass
      Type 2: null
      Total: 461
      HP: 75.0
      Attack: 86.0
      Defense: 67.0
      Sp. Atk: 106.0
      Sp. Def: 67.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 618
      '#': 557
      Name: Dwebble
      Type 1: Bug
      Type 2: Rock
      Total: 325
      HP: 50.0
      Attack: 65.0
      Defense: 85.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 55
      Generation: 5
      Legendary: false
    - index: 619
      '#': 558
      Name: Crustle
      Type 1: Bug
      Type 2: Rock
      Total: 475
      HP: 70.0
      Attack: 95.0
      Defense: 125.0
      Sp. Atk: 65.0
      Sp. Def: 75.0
      Speed: 45
      Generation: 5
      Legendary: false
    - index: 620
      '#': 559
      Name: Scraggy
      Type 1: Dark
      Type 2: Fighting
      Total: 348
      HP: 50.0
      Attack: 75.0
      Defense: 70.0
      Sp. Atk: 35.0
      Sp. Def: 70.0
      Speed: 48
      Generation: 5
      Legendary: false
    - index: 621
      '#': 560
      Name: Scrafty
      Type 1: Dark
      Type 2: Fighting
      Total: 488
      HP: 65.0
      Attack: 90.0
      Defense: 115.0
      Sp. Atk: 45.0
      Sp. Def: 115.0
      Speed: 58
      Generation: 5
      Legendary: false
    - index: 622
      '#': 561
      Name: Sigilyph
      Type 1: Psychic
      Type 2: Flying
      Total: 490
      HP: 72.0
      Attack: 58.0
      Defense: 80.0
      Sp. Atk: 103.0
      Sp. Def: 80.0
      Speed: 97
      Generation: 5
      Legendary: false
    - index: 623
      '#': 562
      Name: Yamask
      Type 1: Ghost
      Type 2: null
      Total: 303
      HP: 38.0
      Attack: 30.0
      Defense: 85.0
      Sp. Atk: 55.0
      Sp. Def: 65.0
      Speed: 30
      Generation: 5
      Legendary: false
    - index: 624
      '#': 563
      Name: Cofagrigus
      Type 1: Ghost
      Type 2: null
      Total: 483
      HP: 58.0
      Attack: 50.0
      Defense: 145.0
      Sp. Atk: 95.0
      Sp. Def: 105.0
      Speed: 30
      Generation: 5
      Legendary: false
    - index: 625
      '#': 564
      Name: Tirtouga
      Type 1: Water
      Type 2: Rock
      Total: 355
      HP: 54.0
      Attack: 78.0
      Defense: 103.0
      Sp. Atk: 53.0
      Sp. Def: 45.0
      Speed: 22
      Generation: 5
      Legendary: false
    - index: 626
      '#': 565
      Name: Carracosta
      Type 1: Water
      Type 2: Rock
      Total: 495
      HP: 74.0
      Attack: 108.0
      Defense: 133.0
      Sp. Atk: 83.0
      Sp. Def: 65.0
      Speed: 32
      Generation: 5
      Legendary: false
    - index: 627
      '#': 566
      Name: Archen
      Type 1: Rock
      Type 2: Flying
      Total: 401
      HP: 55.0
      Attack: 112.0
      Defense: 45.0
      Sp. Atk: 74.0
      Sp. Def: 45.0
      Speed: 70
      Generation: 5
      Legendary: false
    - index: 628
      '#': 567
      Name: Archeops
      Type 1: Rock
      Type 2: Flying
      Total: 567
      HP: 75.0
      Attack: 140.0
      Defense: 65.0
      Sp. Atk: 112.0
      Sp. Def: 65.0
      Speed: 110
      Generation: 5
      Legendary: false
    - index: 629
      '#': 568
      Name: Trubbish
      Type 1: Poison
      Type 2: null
      Total: 329
      HP: 50.0
      Attack: 50.0
      Defense: 62.0
      Sp. Atk: 40.0
      Sp. Def: 62.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 630
      '#': 569
      Name: Garbodor
      Type 1: Poison
      Type 2: null
      Total: 474
      HP: 80.0
      Attack: 95.0
      Defense: 82.0
      Sp. Atk: 60.0
      Sp. Def: 82.0
      Speed: 75
      Generation: 5
      Legendary: false
    - index: 631
      '#': 570
      Name: Zorua
      Type 1: Dark
      Type 2: null
      Total: 330
      HP: 40.0
      Attack: 65.0
      Defense: 40.0
      Sp. Atk: 80.0
      Sp. Def: 40.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 632
      '#': 571
      Name: Zoroark
      Type 1: Dark
      Type 2: null
      Total: 510
      HP: 60.0
      Attack: 105.0
      Defense: 60.0
      Sp. Atk: 120.0
      Sp. Def: 60.0
      Speed: 105
      Generation: 5
      Legendary: false
    - index: 633
      '#': 572
      Name: Minccino
      Type 1: Normal
      Type 2: null
      Total: 300
      HP: 55.0
      Attack: 50.0
      Defense: 40.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 75
      Generation: 5
      Legendary: false
    - index: 634
      '#': 573
      Name: Cinccino
      Type 1: Normal
      Type 2: null
      Total: 470
      HP: 75.0
      Attack: 95.0
      Defense: 60.0
      Sp. Atk: 65.0
      Sp. Def: 60.0
      Speed: 115
      Generation: 5
      Legendary: false
    - index: 635
      '#': 574
      Name: Gothita
      Type 1: Psychic
      Type 2: null
      Total: 290
      HP: 45.0
      Attack: 30.0
      Defense: 50.0
      Sp. Atk: 55.0
      Sp. Def: 65.0
      Speed: 45
      Generation: 5
      Legendary: false
    - index: 636
      '#': 575
      Name: Gothorita
      Type 1: Psychic
      Type 2: null
      Total: 390
      HP: 60.0
      Attack: 45.0
      Defense: 70.0
      Sp. Atk: 75.0
      Sp. Def: 85.0
      Speed: 55
      Generation: 5
      Legendary: false
    - index: 637
      '#': 576
      Name: Gothitelle
      Type 1: Psychic
      Type 2: null
      Total: 490
      HP: 70.0
      Attack: 55.0
      Defense: 95.0
      Sp. Atk: 95.0
      Sp. Def: 110.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 638
      '#': 577
      Name: Solosis
      Type 1: Psychic
      Type 2: null
      Total: 290
      HP: 45.0
      Attack: 30.0
      Defense: 40.0
      Sp. Atk: 105.0
      Sp. Def: 50.0
      Speed: 20
      Generation: 5
      Legendary: false
    - index: 639
      '#': 578
      Name: Duosion
      Type 1: Psychic
      Type 2: null
      Total: 370
      HP: 65.0
      Attack: 40.0
      Defense: 50.0
      Sp. Atk: 125.0
      Sp. Def: 60.0
      Speed: 30
      Generation: 5
      Legendary: false
    - index: 640
      '#': 579
      Name: Reuniclus
      Type 1: Psychic
      Type 2: null
      Total: 490
      HP: 110.0
      Attack: 65.0
      Defense: 75.0
      Sp. Atk: 125.0
      Sp. Def: 85.0
      Speed: 30
      Generation: 5
      Legendary: false
    - index: 641
      '#': 580
      Name: Ducklett
      Type 1: Water
      Type 2: Flying
      Total: 305
      HP: 62.0
      Attack: 44.0
      Defense: 50.0
      Sp. Atk: 44.0
      Sp. Def: 50.0
      Speed: 55
      Generation: 5
      Legendary: false
    - index: 642
      '#': 581
      Name: Swanna
      Type 1: Water
      Type 2: Flying
      Total: 473
      HP: 75.0
      Attack: 87.0
      Defense: 63.0
      Sp. Atk: 87.0
      Sp. Def: 63.0
      Speed: 98
      Generation: 5
      Legendary: false
    - index: 643
      '#': 582
      Name: Vanillite
      Type 1: Ice
      Type 2: null
      Total: 305
      HP: 36.0
      Attack: 50.0
      Defense: 50.0
      Sp. Atk: 65.0
      Sp. Def: 60.0
      Speed: 44
      Generation: 5
      Legendary: false
    - index: 644
      '#': 583
      Name: Vanillish
      Type 1: Ice
      Type 2: null
      Total: 395
      HP: 51.0
      Attack: 65.0
      Defense: 65.0
      Sp. Atk: 80.0
      Sp. Def: 75.0
      Speed: 59
      Generation: 5
      Legendary: false
    - index: 645
      '#': 584
      Name: Vanilluxe
      Type 1: Ice
      Type 2: null
      Total: 535
      HP: 71.0
      Attack: 95.0
      Defense: 85.0
      Sp. Atk: 110.0
      Sp. Def: 95.0
      Speed: 79
      Generation: 5
      Legendary: false
    - index: 646
      '#': 585
      Name: Deerling
      Type 1: Normal
      Type 2: Grass
      Total: 335
      HP: 60.0
      Attack: 60.0
      Defense: 50.0
      Sp. Atk: 40.0
      Sp. Def: 50.0
      Speed: 75
      Generation: 5
      Legendary: false
    - index: 647
      '#': 586
      Name: Sawsbuck
      Type 1: Normal
      Type 2: Grass
      Total: 475
      HP: 80.0
      Attack: 100.0
      Defense: 70.0
      Sp. Atk: 60.0
      Sp. Def: 70.0
      Speed: 95
      Generation: 5
      Legendary: false
    - index: 648
      '#': 587
      Name: Emolga
      Type 1: Electric
      Type 2: Flying
      Total: 428
      HP: 55.0
      Attack: 75.0
      Defense: 60.0
      Sp. Atk: 75.0
      Sp. Def: 60.0
      Speed: 103
      Generation: 5
      Legendary: false
    - index: 649
      '#': 588
      Name: Karrablast
      Type 1: Bug
      Type 2: null
      Total: 315
      HP: 50.0
      Attack: 75.0
      Defense: 45.0
      Sp. Atk: 40.0
      Sp. Def: 45.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 650
      '#': 589
      Name: Escavalier
      Type 1: Bug
      Type 2: Steel
      Total: 495
      HP: 70.0
      Attack: 135.0
      Defense: 105.0
      Sp. Atk: 60.0
      Sp. Def: 105.0
      Speed: 20
      Generation: 5
      Legendary: false
    - index: 651
      '#': 590
      Name: Foongus
      Type 1: Grass
      Type 2: Poison
      Total: 294
      HP: 69.0
      Attack: 55.0
      Defense: 45.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 15
      Generation: 5
      Legendary: false
    - index: 652
      '#': 591
      Name: Amoonguss
      Type 1: Grass
      Type 2: Poison
      Total: 464
      HP: 114.0
      Attack: 85.0
      Defense: 70.0
      Sp. Atk: 85.0
      Sp. Def: 80.0
      Speed: 30
      Generation: 5
      Legendary: false
    - index: 653
      '#': 592
      Name: Frillish
      Type 1: Water
      Type 2: Ghost
      Total: 335
      HP: 55.0
      Attack: 40.0
      Defense: 50.0
      Sp. Atk: 65.0
      Sp. Def: 85.0
      Speed: 40
      Generation: 5
      Legendary: false
    - index: 654
      '#': 593
      Name: Jellicent
      Type 1: Water
      Type 2: Ghost
      Total: 480
      HP: 100.0
      Attack: 60.0
      Defense: 70.0
      Sp. Atk: 85.0
      Sp. Def: 105.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 655
      '#': 594
      Name: Alomomola
      Type 1: Water
      Type 2: null
      Total: 470
      HP: 165.0
      Attack: 75.0
      Defense: 80.0
      Sp. Atk: 40.0
      Sp. Def: 45.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 656
      '#': 595
      Name: Joltik
      Type 1: Bug
      Type 2: Electric
      Total: 319
      HP: 50.0
      Attack: 47.0
      Defense: 50.0
      Sp. Atk: 57.0
      Sp. Def: 50.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 657
      '#': 596
      Name: Galvantula
      Type 1: Bug
      Type 2: Electric
      Total: 472
      HP: 70.0
      Attack: 77.0
      Defense: 60.0
      Sp. Atk: 97.0
      Sp. Def: 60.0
      Speed: 108
      Generation: 5
      Legendary: false
    - index: 658
      '#': 597
      Name: Ferroseed
      Type 1: Grass
      Type 2: Steel
      Total: 305
      HP: 44.0
      Attack: 50.0
      Defense: 91.0
      Sp. Atk: 24.0
      Sp. Def: 86.0
      Speed: 10
      Generation: 5
      Legendary: false
    - index: 659
      '#': 598
      Name: Ferrothorn
      Type 1: Grass
      Type 2: Steel
      Total: 489
      HP: 74.0
      Attack: 94.0
      Defense: 131.0
      Sp. Atk: 54.0
      Sp. Def: 116.0
      Speed: 20
      Generation: 5
      Legendary: false
    - index: 660
      '#': 599
      Name: Klink
      Type 1: Steel
      Type 2: null
      Total: 300
      HP: 40.0
      Attack: 55.0
      Defense: 70.0
      Sp. Atk: 45.0
      Sp. Def: 60.0
      Speed: 30
      Generation: 5
      Legendary: false
    - index: 661
      '#': 600
      Name: Klang
      Type 1: Steel
      Type 2: null
      Total: 440
      HP: 60.0
      Attack: 80.0
      Defense: 95.0
      Sp. Atk: 70.0
      Sp. Def: 85.0
      Speed: 50
      Generation: 5
      Legendary: false
    - index: 662
      '#': 601
      Name: Klinklang
      Type 1: Steel
      Type 2: null
      Total: 520
      HP: 60.0
      Attack: 100.0
      Defense: 115.0
      Sp. Atk: 70.0
      Sp. Def: 85.0
      Speed: 90
      Generation: 5
      Legendary: false
    - index: 663
      '#': 602
      Name: Tynamo
      Type 1: Electric
      Type 2: null
      Total: 275
      HP: 35.0
      Attack: 55.0
      Defense: 40.0
      Sp. Atk: 45.0
      Sp. Def: 40.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 664
      '#': 603
      Name: Eelektrik
      Type 1: Electric
      Type 2: null
      Total: 405
      HP: 65.0
      Attack: 85.0
      Defense: 70.0
      Sp. Atk: 75.0
      Sp. Def: 70.0
      Speed: 40
      Generation: 5
      Legendary: false
    - index: 665
      '#': 604
      Name: Eelektross
      Type 1: Electric
      Type 2: null
      Total: 515
      HP: 85.0
      Attack: 115.0
      Defense: 80.0
      Sp. Atk: 105.0
      Sp. Def: 80.0
      Speed: 50
      Generation: 5
      Legendary: false
    - index: 666
      '#': 605
      Name: Elgyem
      Type 1: Psychic
      Type 2: null
      Total: 335
      HP: 55.0
      Attack: 55.0
      Defense: 55.0
      Sp. Atk: 85.0
      Sp. Def: 55.0
      Speed: 30
      Generation: 5
      Legendary: false
    - index: 667
      '#': 606
      Name: Beheeyem
      Type 1: Psychic
      Type 2: null
      Total: 485
      HP: 75.0
      Attack: 75.0
      Defense: 75.0
      Sp. Atk: 125.0
      Sp. Def: 95.0
      Speed: 40
      Generation: 5
      Legendary: false
    - index: 668
      '#': 607
      Name: Litwick
      Type 1: Ghost
      Type 2: Fire
      Total: 275
      HP: 50.0
      Attack: 30.0
      Defense: 55.0
      Sp. Atk: 65.0
      Sp. Def: 55.0
      Speed: 20
      Generation: 5
      Legendary: false
    - index: 669
      '#': 608
      Name: Lampent
      Type 1: Ghost
      Type 2: Fire
      Total: 370
      HP: 60.0
      Attack: 40.0
      Defense: 60.0
      Sp. Atk: 95.0
      Sp. Def: 60.0
      Speed: 55
      Generation: 5
      Legendary: false
    - index: 670
      '#': 609
      Name: Chandelure
      Type 1: Ghost
      Type 2: Fire
      Total: 520
      HP: 60.0
      Attack: 55.0
      Defense: 90.0
      Sp. Atk: 145.0
      Sp. Def: 90.0
      Speed: 80
      Generation: 5
      Legendary: false
    - index: 671
      '#': 610
      Name: Axew
      Type 1: Dragon
      Type 2: null
      Total: 320
      HP: 46.0
      Attack: 87.0
      Defense: 60.0
      Sp. Atk: 30.0
      Sp. Def: 40.0
      Speed: 57
      Generation: 5
      Legendary: false
    - index: 672
      '#': 611
      Name: Fraxure
      Type 1: Dragon
      Type 2: null
      Total: 410
      HP: 66.0
      Attack: 117.0
      Defense: 70.0
      Sp. Atk: 40.0
      Sp. Def: 50.0
      Speed: 67
      Generation: 5
      Legendary: false
    - index: 673
      '#': 612
      Name: Haxorus
      Type 1: Dragon
      Type 2: null
      Total: 540
      HP: 76.0
      Attack: 147.0
      Defense: 90.0
      Sp. Atk: 60.0
      Sp. Def: 70.0
      Speed: 97
      Generation: 5
      Legendary: false
    - index: 674
      '#': 613
      Name: Cubchoo
      Type 1: Ice
      Type 2: null
      Total: 305
      HP: 55.0
      Attack: 70.0
      Defense: 40.0
      Sp. Atk: 60.0
      Sp. Def: 40.0
      Speed: 40
      Generation: 5
      Legendary: false
    - index: 675
      '#': 614
      Name: Beartic
      Type 1: Ice
      Type 2: null
      Total: 485
      HP: 95.0
      Attack: 110.0
      Defense: 80.0
      Sp. Atk: 70.0
      Sp. Def: 80.0
      Speed: 50
      Generation: 5
      Legendary: false
    - index: 676
      '#': 615
      Name: Cryogonal
      Type 1: Ice
      Type 2: null
      Total: 485
      HP: 70.0
      Attack: 50.0
      Defense: 30.0
      Sp. Atk: 95.0
      Sp. Def: 135.0
      Speed: 105
      Generation: 5
      Legendary: false
    - index: 677
      '#': 616
      Name: Shelmet
      Type 1: Bug
      Type 2: null
      Total: 305
      HP: 50.0
      Attack: 40.0
      Defense: 85.0
      Sp. Atk: 40.0
      Sp. Def: 65.0
      Speed: 25
      Generation: 5
      Legendary: false
    - index: 678
      '#': 617
      Name: Accelgor
      Type 1: Bug
      Type 2: null
      Total: 495
      HP: 80.0
      Attack: 70.0
      Defense: 40.0
      Sp. Atk: 100.0
      Sp. Def: 60.0
      Speed: 145
      Generation: 5
      Legendary: false
    - index: 679
      '#': 618
      Name: Stunfisk
      Type 1: Ground
      Type 2: Electric
      Total: 471
      HP: 109.0
      Attack: 66.0
      Defense: 84.0
      Sp. Atk: 81.0
      Sp. Def: 99.0
      Speed: 32
      Generation: 5
      Legendary: false
    - index: 680
      '#': 619
      Name: Mienfoo
      Type 1: Fighting
      Type 2: null
      Total: 350
      HP: 45.0
      Attack: 85.0
      Defense: 50.0
      Sp. Atk: 55.0
      Sp. Def: 50.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 681
      '#': 620
      Name: Mienshao
      Type 1: Fighting
      Type 2: null
      Total: 510
      HP: 65.0
      Attack: 125.0
      Defense: 60.0
      Sp. Atk: 95.0
      Sp. Def: 60.0
      Speed: 105
      Generation: 5
      Legendary: false
    - index: 682
      '#': 621
      Name: Druddigon
      Type 1: Dragon
      Type 2: null
      Total: 485
      HP: 77.0
      Attack: 120.0
      Defense: 90.0
      Sp. Atk: 60.0
      Sp. Def: 90.0
      Speed: 48
      Generation: 5
      Legendary: false
    - index: 683
      '#': 622
      Name: Golett
      Type 1: Ground
      Type 2: Ghost
      Total: 303
      HP: 59.0
      Attack: 74.0
      Defense: 50.0
      Sp. Atk: 35.0
      Sp. Def: 50.0
      Speed: 35
      Generation: 5
      Legendary: false
    - index: 684
      '#': 623
      Name: Golurk
      Type 1: Ground
      Type 2: Ghost
      Total: 483
      HP: 89.0
      Attack: 124.0
      Defense: 80.0
      Sp. Atk: 55.0
      Sp. Def: 80.0
      Speed: 55
      Generation: 5
      Legendary: false
    - index: 685
      '#': 624
      Name: Pawniard
      Type 1: Dark
      Type 2: Steel
      Total: 340
      HP: 45.0
      Attack: 85.0
      Defense: 70.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 686
      '#': 625
      Name: Bisharp
      Type 1: Dark
      Type 2: Steel
      Total: 490
      HP: 65.0
      Attack: 125.0
      Defense: 100.0
      Sp. Atk: 60.0
      Sp. Def: 70.0
      Speed: 70
      Generation: 5
      Legendary: false
    - index: 687
      '#': 626
      Name: Bouffalant
      Type 1: Normal
      Type 2: null
      Total: 490
      HP: 95.0
      Attack: 110.0
      Defense: 95.0
      Sp. Atk: 40.0
      Sp. Def: 95.0
      Speed: 55
      Generation: 5
      Legendary: false
    - index: 688
      '#': 627
      Name: Rufflet
      Type 1: Normal
      Type 2: Flying
      Total: 350
      HP: 70.0
      Attack: 83.0
      Defense: 50.0
      Sp. Atk: 37.0
      Sp. Def: 50.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 689
      '#': 628
      Name: Braviary
      Type 1: Normal
      Type 2: Flying
      Total: 510
      HP: 100.0
      Attack: 123.0
      Defense: 75.0
      Sp. Atk: 57.0
      Sp. Def: 75.0
      Speed: 80
      Generation: 5
      Legendary: false
    - index: 690
      '#': 629
      Name: Vullaby
      Type 1: Dark
      Type 2: Flying
      Total: 370
      HP: 70.0
      Attack: 55.0
      Defense: 75.0
      Sp. Atk: 45.0
      Sp. Def: 65.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 691
      '#': 630
      Name: Mandibuzz
      Type 1: Dark
      Type 2: Flying
      Total: 510
      HP: 110.0
      Attack: 65.0
      Defense: 105.0
      Sp. Atk: 55.0
      Sp. Def: 95.0
      Speed: 80
      Generation: 5
      Legendary: false
    - index: 692
      '#': 631
      Name: Heatmor
      Type 1: Fire
      Type 2: null
      Total: 484
      HP: 85.0
      Attack: 97.0
      Defense: 66.0
      Sp. Atk: 105.0
      Sp. Def: 66.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 693
      '#': 632
      Name: Durant
      Type 1: Bug
      Type 2: Steel
      Total: 484
      HP: 58.0
      Attack: 109.0
      Defense: 112.0
      Sp. Atk: 48.0
      Sp. Def: 48.0
      Speed: 109
      Generation: 5
      Legendary: false
    - index: 694
      '#': 633
      Name: Deino
      Type 1: Dark
      Type 2: Dragon
      Total: 300
      HP: 52.0
      Attack: 65.0
      Defense: 50.0
      Sp. Atk: 45.0
      Sp. Def: 50.0
      Speed: 38
      Generation: 5
      Legendary: false
    - index: 695
      '#': 634
      Name: Zweilous
      Type 1: Dark
      Type 2: Dragon
      Total: 420
      HP: 72.0
      Attack: 85.0
      Defense: 70.0
      Sp. Atk: 65.0
      Sp. Def: 70.0
      Speed: 58
      Generation: 5
      Legendary: false
    - index: 696
      '#': 635
      Name: Hydreigon
      Type 1: Dark
      Type 2: Dragon
      Total: 600
      HP: 92.0
      Attack: 105.0
      Defense: 90.0
      Sp. Atk: 125.0
      Sp. Def: 90.0
      Speed: 98
      Generation: 5
      Legendary: false
    - index: 697
      '#': 636
      Name: Larvesta
      Type 1: Bug
      Type 2: Fire
      Total: 360
      HP: 55.0
      Attack: 85.0
      Defense: 55.0
      Sp. Atk: 50.0
      Sp. Def: 55.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 698
      '#': 637
      Name: Volcarona
      Type 1: Bug
      Type 2: Fire
      Total: 550
      HP: 85.0
      Attack: 60.0
      Defense: 65.0
      Sp. Atk: 135.0
      Sp. Def: 105.0
      Speed: 100
      Generation: 5
      Legendary: false
    - index: 699
      '#': 638
      Name: Cobalion
      Type 1: Steel
      Type 2: Fighting
      Total: 580
      HP: 91.0
      Attack: 90.0
      Defense: 129.0
      Sp. Atk: 90.0
      Sp. Def: 72.0
      Speed: 108
      Generation: 5
      Legendary: true
    - index: 700
      '#': 639
      Name: Terrakion
      Type 1: Rock
      Type 2: Fighting
      Total: 580
      HP: 91.0
      Attack: 129.0
      Defense: 90.0
      Sp. Atk: 72.0
      Sp. Def: 90.0
      Speed: 108
      Generation: 5
      Legendary: true
    - index: 701
      '#': 640
      Name: Virizion
      Type 1: Grass
      Type 2: Fighting
      Total: 580
      HP: 91.0
      Attack: 90.0
      Defense: 72.0
      Sp. Atk: 90.0
      Sp. Def: 129.0
      Speed: 108
      Generation: 5
      Legendary: true
    - index: 702
      '#': 641
      Name: TornadusIncarnate Forme
      Type 1: Flying
      Type 2: null
      Total: 580
      HP: 79.0
      Attack: 115.0
      Defense: 70.0
      Sp. Atk: 125.0
      Sp. Def: 80.0
      Speed: 111
      Generation: 5
      Legendary: true
    - index: 703
      '#': 641
      Name: TornadusTherian Forme
      Type 1: Flying
      Type 2: null
      Total: 580
      HP: 79.0
      Attack: 100.0
      Defense: 80.0
      Sp. Atk: 110.0
      Sp. Def: 90.0
      Speed: 121
      Generation: 5
      Legendary: true
    - index: 704
      '#': 642
      Name: ThundurusIncarnate Forme
      Type 1: Electric
      Type 2: Flying
      Total: 580
      HP: 79.0
      Attack: 115.0
      Defense: 70.0
      Sp. Atk: 125.0
      Sp. Def: 80.0
      Speed: 111
      Generation: 5
      Legendary: true
    - index: 705
      '#': 642
      Name: ThundurusTherian Forme
      Type 1: Electric
      Type 2: Flying
      Total: 580
      HP: 79.0
      Attack: 105.0
      Defense: 70.0
      Sp. Atk: 145.0
      Sp. Def: 80.0
      Speed: 101
      Generation: 5
      Legendary: true
    - index: 706
      '#': 643
      Name: Reshiram
      Type 1: Dragon
      Type 2: Fire
      Total: 680
      HP: 100.0
      Attack: 120.0
      Defense: 100.0
      Sp. Atk: 150.0
      Sp. Def: 120.0
      Speed: 90
      Generation: 5
      Legendary: true
    - index: 707
      '#': 644
      Name: Zekrom
      Type 1: Dragon
      Type 2: Electric
      Total: 680
      HP: 100.0
      Attack: 150.0
      Defense: 120.0
      Sp. Atk: 120.0
      Sp. Def: 100.0
      Speed: 90
      Generation: 5
      Legendary: true
    - index: 708
      '#': 645
      Name: LandorusIncarnate Forme
      Type 1: Ground
      Type 2: Flying
      Total: 600
      HP: 89.0
      Attack: 125.0
      Defense: 90.0
      Sp. Atk: 115.0
      Sp. Def: 80.0
      Speed: 101
      Generation: 5
      Legendary: true
    - index: 709
      '#': 645
      Name: LandorusTherian Forme
      Type 1: Ground
      Type 2: Flying
      Total: 600
      HP: 89.0
      Attack: 145.0
      Defense: 90.0
      Sp. Atk: 105.0
      Sp. Def: 80.0
      Speed: 91
      Generation: 5
      Legendary: true
    - index: 710
      '#': 646
      Name: Kyurem
      Type 1: Dragon
      Type 2: Ice
      Total: 660
      HP: 125.0
      Attack: 130.0
      Defense: 90.0
      Sp. Atk: 130.0
      Sp. Def: 90.0
      Speed: 95
      Generation: 5
      Legendary: true
    - index: 711
      '#': 646
      Name: KyuremBlack Kyurem
      Type 1: Dragon
      Type 2: Ice
      Total: 700
      HP: 125.0
      Attack: 170.0
      Defense: 100.0
      Sp. Atk: 120.0
      Sp. Def: 90.0
      Speed: 95
      Generation: 5
      Legendary: true
    - index: 712
      '#': 646
      Name: KyuremWhite Kyurem
      Type 1: Dragon
      Type 2: Ice
      Total: 700
      HP: 125.0
      Attack: 120.0
      Defense: 90.0
      Sp. Atk: 170.0
      Sp. Def: 100.0
      Speed: 95
      Generation: 5
      Legendary: true
    - index: 713
      '#': 647
      Name: KeldeoOrdinary Forme
      Type 1: Water
      Type 2: Fighting
      Total: 580
      HP: 91.0
      Attack: 72.0
      Defense: 90.0
      Sp. Atk: 129.0
      Sp. Def: 90.0
      Speed: 108
      Generation: 5
      Legendary: false
    - index: 714
      '#': 647
      Name: KeldeoResolute Forme
      Type 1: Water
      Type 2: Fighting
      Total: 580
      HP: 91.0
      Attack: 72.0
      Defense: 90.0
      Sp. Atk: 129.0
      Sp. Def: 90.0
      Speed: 108
      Generation: 5
      Legendary: false
    - index: 715
      '#': 648
      Name: MeloettaAria Forme
      Type 1: Normal
      Type 2: Psychic
      Total: 600
      HP: 100.0
      Attack: 77.0
      Defense: 77.0
      Sp. Atk: 128.0
      Sp. Def: 128.0
      Speed: 90
      Generation: 5
      Legendary: false
    - index: 716
      '#': 648
      Name: MeloettaPirouette Forme
      Type 1: Normal
      Type 2: Fighting
      Total: 600
      HP: 100.0
      Attack: 128.0
      Defense: 90.0
      Sp. Atk: 77.0
      Sp. Def: 77.0
      Speed: 128
      Generation: 5
      Legendary: false
    - index: 717
      '#': 649
      Name: Genesect
      Type 1: Bug
      Type 2: Steel
      Total: 600
      HP: 71.0
      Attack: 120.0
      Defense: 95.0
      Sp. Atk: 120.0
      Sp. Def: 95.0
      Speed: 99
      Generation: 5
      Legendary: false
    - index: 718
      '#': 650
      Name: Chespin
      Type 1: Grass
      Type 2: null
      Total: 313
      HP: 56.0
      Attack: 61.0
      Defense: 65.0
      Sp. Atk: 48.0
      Sp. Def: 45.0
      Speed: 38
      Generation: 6
      Legendary: false
    - index: 719
      '#': 651
      Name: Quilladin
      Type 1: Grass
      Type 2: null
      Total: 405
      HP: 61.0
      Attack: 78.0
      Defense: 95.0
      Sp. Atk: 56.0
      Sp. Def: 58.0
      Speed: 57
      Generation: 6
      Legendary: false
    - index: 720
      '#': 652
      Name: Chesnaught
      Type 1: Grass
      Type 2: Fighting
      Total: 530
      HP: 88.0
      Attack: 107.0
      Defense: 122.0
      Sp. Atk: 74.0
      Sp. Def: 75.0
      Speed: 64
      Generation: 6
      Legendary: false
    - index: 721
      '#': 653
      Name: Fennekin
      Type 1: Fire
      Type 2: null
      Total: 307
      HP: 40.0
      Attack: 45.0
      Defense: 40.0
      Sp. Atk: 62.0
      Sp. Def: 60.0
      Speed: 60
      Generation: 6
      Legendary: false
    - index: 722
      '#': 654
      Name: Braixen
      Type 1: Fire
      Type 2: null
      Total: 409
      HP: 59.0
      Attack: 59.0
      Defense: 58.0
      Sp. Atk: 90.0
      Sp. Def: 70.0
      Speed: 73
      Generation: 6
      Legendary: false
    - index: 723
      '#': 655
      Name: Delphox
      Type 1: Fire
      Type 2: Psychic
      Total: 534
      HP: 75.0
      Attack: 69.0
      Defense: 72.0
      Sp. Atk: 114.0
      Sp. Def: 100.0
      Speed: 104
      Generation: 6
      Legendary: false
    - index: 724
      '#': 656
      Name: Froakie
      Type 1: Water
      Type 2: null
      Total: 314
      HP: 41.0
      Attack: 56.0
      Defense: 40.0
      Sp. Atk: 62.0
      Sp. Def: 44.0
      Speed: 71
      Generation: 6
      Legendary: false
    - index: 725
      '#': 657
      Name: Frogadier
      Type 1: Water
      Type 2: null
      Total: 405
      HP: 54.0
      Attack: 63.0
      Defense: 52.0
      Sp. Atk: 83.0
      Sp. Def: 56.0
      Speed: 97
      Generation: 6
      Legendary: false
    - index: 726
      '#': 658
      Name: Greninja
      Type 1: Water
      Type 2: Dark
      Total: 530
      HP: 72.0
      Attack: 95.0
      Defense: 67.0
      Sp. Atk: 103.0
      Sp. Def: 71.0
      Speed: 122
      Generation: 6
      Legendary: false
    - index: 727
      '#': 659
      Name: Bunnelby
      Type 1: Normal
      Type 2: null
      Total: 237
      HP: 38.0
      Attack: 36.0
      Defense: 38.0
      Sp. Atk: 32.0
      Sp. Def: 36.0
      Speed: 57
      Generation: 6
      Legendary: false
    - index: 728
      '#': 660
      Name: Diggersby
      Type 1: Normal
      Type 2: Ground
      Total: 423
      HP: 85.0
      Attack: 56.0
      Defense: 77.0
      Sp. Atk: 50.0
      Sp. Def: 77.0
      Speed: 78
      Generation: 6
      Legendary: false
    - index: 729
      '#': 661
      Name: Fletchling
      Type 1: Normal
      Type 2: Flying
      Total: 278
      HP: 45.0
      Attack: 50.0
      Defense: 43.0
      Sp. Atk: 40.0
      Sp. Def: 38.0
      Speed: 62
      Generation: 6
      Legendary: false
    - index: 730
      '#': 662
      Name: Fletchinder
      Type 1: Fire
      Type 2: Flying
      Total: 382
      HP: 62.0
      Attack: 73.0
      Defense: 55.0
      Sp. Atk: 56.0
      Sp. Def: 52.0
      Speed: 84
      Generation: 6
      Legendary: false
    - index: 731
      '#': 663
      Name: Talonflame
      Type 1: Fire
      Type 2: Flying
      Total: 499
      HP: 78.0
      Attack: 81.0
      Defense: 71.0
      Sp. Atk: 74.0
      Sp. Def: 69.0
      Speed: 126
      Generation: 6
      Legendary: false
    - index: 732
      '#': 664
      Name: Scatterbug
      Type 1: Bug
      Type 2: null
      Total: 200
      HP: 38.0
      Attack: 35.0
      Defense: 40.0
      Sp. Atk: 27.0
      Sp. Def: 25.0
      Speed: 35
      Generation: 6
      Legendary: false
    - index: 733
      '#': 665
      Name: Spewpa
      Type 1: Bug
      Type 2: null
      Total: 213
      HP: 45.0
      Attack: 22.0
      Defense: 60.0
      Sp. Atk: 27.0
      Sp. Def: 30.0
      Speed: 29
      Generation: 6
      Legendary: false
    - index: 734
      '#': 666
      Name: Vivillon
      Type 1: Bug
      Type 2: Flying
      Total: 411
      HP: 80.0
      Attack: 52.0
      Defense: 50.0
      Sp. Atk: 90.0
      Sp. Def: 50.0
      Speed: 89
      Generation: 6
      Legendary: false
    - index: 735
      '#': 667
      Name: Litleo
      Type 1: Fire
      Type 2: Normal
      Total: 369
      HP: 62.0
      Attack: 50.0
      Defense: 58.0
      Sp. Atk: 73.0
      Sp. Def: 54.0
      Speed: 72
      Generation: 6
      Legendary: false
    - index: 736
      '#': 668
      Name: Pyroar
      Type 1: Fire
      Type 2: Normal
      Total: 507
      HP: 86.0
      Attack: 68.0
      Defense: 72.0
      Sp. Atk: 109.0
      Sp. Def: 66.0
      Speed: 106
      Generation: 6
      Legendary: false
    - index: 737
      '#': 669
      Name: Flabébé
      Type 1: Fairy
      Type 2: null
      Total: 303
      HP: 44.0
      Attack: 38.0
      Defense: 39.0
      Sp. Atk: 61.0
      Sp. Def: 79.0
      Speed: 42
      Generation: 6
      Legendary: false
    - index: 738
      '#': 670
      Name: Floette
      Type 1: Fairy
      Type 2: null
      Total: 371
      HP: 54.0
      Attack: 45.0
      Defense: 47.0
      Sp. Atk: 75.0
      Sp. Def: 98.0
      Speed: 52
      Generation: 6
      Legendary: false
    - index: 739
      '#': 671
      Name: Florges
      Type 1: Fairy
      Type 2: null
      Total: 552
      HP: 78.0
      Attack: 65.0
      Defense: 68.0
      Sp. Atk: 112.0
      Sp. Def: 154.0
      Speed: 75
      Generation: 6
      Legendary: false
    - index: 740
      '#': 672
      Name: Skiddo
      Type 1: Grass
      Type 2: null
      Total: 350
      HP: 66.0
      Attack: 65.0
      Defense: 48.0
      Sp. Atk: 62.0
      Sp. Def: 57.0
      Speed: 52
      Generation: 6
      Legendary: false
    - index: 741
      '#': 673
      Name: Gogoat
      Type 1: Grass
      Type 2: null
      Total: 531
      HP: 123.0
      Attack: 100.0
      Defense: 62.0
      Sp. Atk: 97.0
      Sp. Def: 81.0
      Speed: 68
      Generation: 6
      Legendary: false
    - index: 742
      '#': 674
      Name: Pancham
      Type 1: Fighting
      Type 2: null
      Total: 348
      HP: 67.0
      Attack: 82.0
      Defense: 62.0
      Sp. Atk: 46.0
      Sp. Def: 48.0
      Speed: 43
      Generation: 6
      Legendary: false
    - index: 743
      '#': 675
      Name: Pangoro
      Type 1: Fighting
      Type 2: Dark
      Total: 495
      HP: 95.0
      Attack: 124.0
      Defense: 78.0
      Sp. Atk: 69.0
      Sp. Def: 71.0
      Speed: 58
      Generation: 6
      Legendary: false
    - index: 744
      '#': 676
      Name: Furfrou
      Type 1: Normal
      Type 2: null
      Total: 472
      HP: 75.0
      Attack: 80.0
      Defense: 60.0
      Sp. Atk: 65.0
      Sp. Def: 90.0
      Speed: 102
      Generation: 6
      Legendary: false
    - index: 745
      '#': 677
      Name: Espurr
      Type 1: Psychic
      Type 2: null
      Total: 355
      HP: 62.0
      Attack: 48.0
      Defense: 54.0
      Sp. Atk: 63.0
      Sp. Def: 60.0
      Speed: 68
      Generation: 6
      Legendary: false
    - index: 746
      '#': 678
      Name: MeowsticMale
      Type 1: Psychic
      Type 2: null
      Total: 466
      HP: 74.0
      Attack: 48.0
      Defense: 76.0
      Sp. Atk: 83.0
      Sp. Def: 81.0
      Speed: 104
      Generation: 6
      Legendary: false
    - index: 747
      '#': 678
      Name: MeowsticFemale
      Type 1: Psychic
      Type 2: null
      Total: 466
      HP: 74.0
      Attack: 48.0
      Defense: 76.0
      Sp. Atk: 83.0
      Sp. Def: 81.0
      Speed: 104
      Generation: 6
      Legendary: false
    - index: 748
      '#': 679
      Name: Honedge
      Type 1: Steel
      Type 2: Ghost
      Total: 325
      HP: 45.0
      Attack: 80.0
      Defense: 100.0
      Sp. Atk: 35.0
      Sp. Def: 37.0
      Speed: 28
      Generation: 6
      Legendary: false
    - index: 749
      '#': 680
      Name: Doublade
      Type 1: Steel
      Type 2: Ghost
      Total: 448
      HP: 59.0
      Attack: 110.0
      Defense: 150.0
      Sp. Atk: 45.0
      Sp. Def: 49.0
      Speed: 35
      Generation: 6
      Legendary: false
    - index: 750
      '#': 681
      Name: AegislashBlade Forme
      Type 1: Steel
      Type 2: Ghost
      Total: 520
      HP: 60.0
      Attack: 150.0
      Defense: 50.0
      Sp. Atk: 150.0
      Sp. Def: 50.0
      Speed: 60
      Generation: 6
      Legendary: false
    - index: 751
      '#': 681
      Name: AegislashShield Forme
      Type 1: Steel
      Type 2: Ghost
      Total: 520
      HP: 60.0
      Attack: 50.0
      Defense: 150.0
      Sp. Atk: 50.0
      Sp. Def: 150.0
      Speed: 60
      Generation: 6
      Legendary: false
    - index: 752
      '#': 682
      Name: Spritzee
      Type 1: Fairy
      Type 2: null
      Total: 341
      HP: 78.0
      Attack: 52.0
      Defense: 60.0
      Sp. Atk: 63.0
      Sp. Def: 65.0
      Speed: 23
      Generation: 6
      Legendary: false
    - index: 753
      '#': 683
      Name: Aromatisse
      Type 1: Fairy
      Type 2: null
      Total: 462
      HP: 101.0
      Attack: 72.0
      Defense: 72.0
      Sp. Atk: 99.0
      Sp. Def: 89.0
      Speed: 29
      Generation: 6
      Legendary: false
    - index: 754
      '#': 684
      Name: Swirlix
      Type 1: Fairy
      Type 2: null
      Total: 341
      HP: 62.0
      Attack: 48.0
      Defense: 66.0
      Sp. Atk: 59.0
      Sp. Def: 57.0
      Speed: 49
      Generation: 6
      Legendary: false
    - index: 755
      '#': 685
      Name: Slurpuff
      Type 1: Fairy
      Type 2: null
      Total: 480
      HP: 82.0
      Attack: 80.0
      Defense: 86.0
      Sp. Atk: 85.0
      Sp. Def: 75.0
      Speed: 72
      Generation: 6
      Legendary: false
    - index: 756
      '#': 686
      Name: Inkay
      Type 1: Dark
      Type 2: Psychic
      Total: 288
      HP: 53.0
      Attack: 54.0
      Defense: 53.0
      Sp. Atk: 37.0
      Sp. Def: 46.0
      Speed: 45
      Generation: 6
      Legendary: false
    - index: 757
      '#': 687
      Name: Malamar
      Type 1: Dark
      Type 2: Psychic
      Total: 482
      HP: 86.0
      Attack: 92.0
      Defense: 88.0
      Sp. Atk: 68.0
      Sp. Def: 75.0
      Speed: 73
      Generation: 6
      Legendary: false
    - index: 758
      '#': 688
      Name: Binacle
      Type 1: Rock
      Type 2: Water
      Total: 306
      HP: 42.0
      Attack: 52.0
      Defense: 67.0
      Sp. Atk: 39.0
      Sp. Def: 56.0
      Speed: 50
      Generation: 6
      Legendary: false
    - index: 759
      '#': 689
      Name: Barbaracle
      Type 1: Rock
      Type 2: Water
      Total: 500
      HP: 72.0
      Attack: 105.0
      Defense: 115.0
      Sp. Atk: 54.0
      Sp. Def: 86.0
      Speed: 68
      Generation: 6
      Legendary: false
    - index: 760
      '#': 690
      Name: Skrelp
      Type 1: Poison
      Type 2: Water
      Total: 320
      HP: 50.0
      Attack: 60.0
      Defense: 60.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 30
      Generation: 6
      Legendary: false
    - index: 761
      '#': 691
      Name: Dragalge
      Type 1: Poison
      Type 2: Dragon
      Total: 494
      HP: 65.0
      Attack: 75.0
      Defense: 90.0
      Sp. Atk: 97.0
      Sp. Def: 123.0
      Speed: 44
      Generation: 6
      Legendary: false
    - index: 762
      '#': 692
      Name: Clauncher
      Type 1: Water
      Type 2: null
      Total: 330
      HP: 50.0
      Attack: 53.0
      Defense: 62.0
      Sp. Atk: 58.0
      Sp. Def: 63.0
      Speed: 44
      Generation: 6
      Legendary: false
    - index: 763
      '#': 693
      Name: Clawitzer
      Type 1: Water
      Type 2: null
      Total: 500
      HP: 71.0
      Attack: 73.0
      Defense: 88.0
      Sp. Atk: 120.0
      Sp. Def: 89.0
      Speed: 59
      Generation: 6
      Legendary: false
    - index: 764
      '#': 694
      Name: Helioptile
      Type 1: Electric
      Type 2: Normal
      Total: 289
      HP: 44.0
      Attack: 38.0
      Defense: 33.0
      Sp. Atk: 61.0
      Sp. Def: 43.0
      Speed: 70
      Generation: 6
      Legendary: false
    - index: 765
      '#': 695
      Name: Heliolisk
      Type 1: Electric
      Type 2: Normal
      Total: 481
      HP: 62.0
      Attack: 55.0
      Defense: 52.0
      Sp. Atk: 109.0
      Sp. Def: 94.0
      Speed: 109
      Generation: 6
      Legendary: false
    - index: 766
      '#': 696
      Name: Tyrunt
      Type 1: Rock
      Type 2: Dragon
      Total: 362
      HP: 58.0
      Attack: 89.0
      Defense: 77.0
      Sp. Atk: 45.0
      Sp. Def: 45.0
      Speed: 48
      Generation: 6
      Legendary: false
    - index: 767
      '#': 697
      Name: Tyrantrum
      Type 1: Rock
      Type 2: Dragon
      Total: 521
      HP: 82.0
      Attack: 121.0
      Defense: 119.0
      Sp. Atk: 69.0
      Sp. Def: 59.0
      Speed: 71
      Generation: 6
      Legendary: false
    - index: 768
      '#': 698
      Name: Amaura
      Type 1: Rock
      Type 2: Ice
      Total: 362
      HP: 77.0
      Attack: 59.0
      Defense: 50.0
      Sp. Atk: 67.0
      Sp. Def: 63.0
      Speed: 46
      Generation: 6
      Legendary: false
    - index: 769
      '#': 699
      Name: Aurorus
      Type 1: Rock
      Type 2: Ice
      Total: 521
      HP: 123.0
      Attack: 77.0
      Defense: 72.0
      Sp. Atk: 99.0
      Sp. Def: 92.0
      Speed: 58
      Generation: 6
      Legendary: false
    - index: 770
      '#': 700
      Name: Sylveon
      Type 1: Fairy
      Type 2: null
      Total: 525
      HP: 95.0
      Attack: 65.0
      Defense: 65.0
      Sp. Atk: 110.0
      Sp. Def: 130.0
      Speed: 60
      Generation: 6
      Legendary: false
    - index: 771
      '#': 701
      Name: Hawlucha
      Type 1: Fighting
      Type 2: Flying
      Total: 500
      HP: 78.0
      Attack: 92.0
      Defense: 75.0
      Sp. Atk: 74.0
      Sp. Def: 63.0
      Speed: 118
      Generation: 6
      Legendary: false
    - index: 772
      '#': 702
      Name: Dedenne
      Type 1: Electric
      Type 2: Fairy
      Total: 431
      HP: 67.0
      Attack: 58.0
      Defense: 57.0
      Sp. Atk: 81.0
      Sp. Def: 67.0
      Speed: 101
      Generation: 6
      Legendary: false
    - index: 773
      '#': 703
      Name: Carbink
      Type 1: Rock
      Type 2: Fairy
      Total: 500
      HP: 50.0
      Attack: 50.0
      Defense: 150.0
      Sp. Atk: 50.0
      Sp. Def: 150.0
      Speed: 50
      Generation: 6
      Legendary: false
    - index: 774
      '#': 704
      Name: Goomy
      Type 1: Dragon
      Type 2: null
      Total: 300
      HP: 45.0
      Attack: 50.0
      Defense: 35.0
      Sp. Atk: 55.0
      Sp. Def: 75.0
      Speed: 40
      Generation: 6
      Legendary: false
    - index: 775
      '#': 705
      Name: Sliggoo
      Type 1: Dragon
      Type 2: null
      Total: 452
      HP: 68.0
      Attack: 75.0
      Defense: 53.0
      Sp. Atk: 83.0
      Sp. Def: 113.0
      Speed: 60
      Generation: 6
      Legendary: false
    - index: 776
      '#': 706
      Name: Goodra
      Type 1: Dragon
      Type 2: null
      Total: 600
      HP: 90.0
      Attack: 100.0
      Defense: 70.0
      Sp. Atk: 110.0
      Sp. Def: 150.0
      Speed: 80
      Generation: 6
      Legendary: false
    - index: 777
      '#': 707
      Name: Klefki
      Type 1: Steel
      Type 2: Fairy
      Total: 470
      HP: 57.0
      Attack: 80.0
      Defense: 91.0
      Sp. Atk: 80.0
      Sp. Def: 87.0
      Speed: 75
      Generation: 6
      Legendary: false
    - index: 778
      '#': 708
      Name: Phantump
      Type 1: Ghost
      Type 2: Grass
      Total: 309
      HP: 43.0
      Attack: 70.0
      Defense: 48.0
      Sp. Atk: 50.0
      Sp. Def: 60.0
      Speed: 38
      Generation: 6
      Legendary: false
    - index: 779
      '#': 709
      Name: Trevenant
      Type 1: Ghost
      Type 2: Grass
      Total: 474
      HP: 85.0
      Attack: 110.0
      Defense: 76.0
      Sp. Atk: 65.0
      Sp. Def: 82.0
      Speed: 56
      Generation: 6
      Legendary: false
    - index: 780
      '#': 710
      Name: PumpkabooAverage Size
      Type 1: Ghost
      Type 2: Grass
      Total: 335
      HP: 49.0
      Attack: 66.0
      Defense: 70.0
      Sp. Atk: 44.0
      Sp. Def: 55.0
      Speed: 51
      Generation: 6
      Legendary: false
    - index: 781
      '#': 710
      Name: PumpkabooSmall Size
      Type 1: Ghost
      Type 2: Grass
      Total: 335
      HP: 44.0
      Attack: 66.0
      Defense: 70.0
      Sp. Atk: 44.0
      Sp. Def: 55.0
      Speed: 56
      Generation: 6
      Legendary: false
    - index: 782
      '#': 710
      Name: PumpkabooLarge Size
      Type 1: Ghost
      Type 2: Grass
      Total: 335
      HP: 54.0
      Attack: 66.0
      Defense: 70.0
      Sp. Atk: 44.0
      Sp. Def: 55.0
      Speed: 46
      Generation: 6
      Legendary: false
    - index: 783
      '#': 710
      Name: PumpkabooSuper Size
      Type 1: Ghost
      Type 2: Grass
      Total: 335
      HP: 59.0
      Attack: 66.0
      Defense: 70.0
      Sp. Atk: 44.0
      Sp. Def: 55.0
      Speed: 41
      Generation: 6
      Legendary: false
    - index: 784
      '#': 711
      Name: GourgeistAverage Size
      Type 1: Ghost
      Type 2: Grass
      Total: 494
      HP: 65.0
      Attack: 90.0
      Defense: 122.0
      Sp. Atk: 58.0
      Sp. Def: 75.0
      Speed: 84
      Generation: 6
      Legendary: false
    - index: 785
      '#': 711
      Name: GourgeistSmall Size
      Type 1: Ghost
      Type 2: Grass
      Total: 494
      HP: 55.0
      Attack: 85.0
      Defense: 122.0
      Sp. Atk: 58.0
      Sp. Def: 75.0
      Speed: 99
      Generation: 6
      Legendary: false
    - index: 786
      '#': 711
      Name: GourgeistLarge Size
      Type 1: Ghost
      Type 2: Grass
      Total: 494
      HP: 75.0
      Attack: 95.0
      Defense: 122.0
      Sp. Atk: 58.0
      Sp. Def: 75.0
      Speed: 69
      Generation: 6
      Legendary: false
    - index: 787
      '#': 711
      Name: GourgeistSuper Size
      Type 1: Ghost
      Type 2: Grass
      Total: 494
      HP: 85.0
      Attack: 100.0
      Defense: 122.0
      Sp. Atk: 58.0
      Sp. Def: 75.0
      Speed: 54
      Generation: 6
      Legendary: false
    - index: 788
      '#': 712
      Name: Bergmite
      Type 1: Ice
      Type 2: null
      Total: 304
      HP: 55.0
      Attack: 69.0
      Defense: 85.0
      Sp. Atk: 32.0
      Sp. Def: 35.0
      Speed: 28
      Generation: 6
      Legendary: false
    - index: 789
      '#': 713
      Name: Avalugg
      Type 1: Ice
      Type 2: null
      Total: 514
      HP: 95.0
      Attack: 117.0
      Defense: 184.0
      Sp. Atk: 44.0
      Sp. Def: 46.0
      Speed: 28
      Generation: 6
      Legendary: false
    - index: 790
      '#': 714
      Name: Noibat
      Type 1: Flying
      Type 2: Dragon
      Total: 245
      HP: 40.0
      Attack: 30.0
      Defense: 35.0
      Sp. Atk: 45.0
      Sp. Def: 40.0
      Speed: 55
      Generation: 6
      Legendary: false
    - index: 791
      '#': 715
      Name: Noivern
      Type 1: Flying
      Type 2: Dragon
      Total: 535
      HP: 85.0
      Attack: 70.0
      Defense: 80.0
      Sp. Atk: 97.0
      Sp. Def: 80.0
      Speed: 123
      Generation: 6
      Legendary: false
    - index: 792
      '#': 716
      Name: Xerneas
      Type 1: Fairy
      Type 2: null
      Total: 680
      HP: 126.0
      Attack: 131.0
      Defense: 95.0
      Sp. Atk: 131.0
      Sp. Def: 98.0
      Speed: 99
      Generation: 6
      Legendary: true
    - index: 793
      '#': 717
      Name: Yveltal
      Type 1: Dark
      Type 2: Flying
      Total: 680
      HP: 126.0
      Attack: 131.0
      Defense: 95.0
      Sp. Atk: 131.0
      Sp. Def: 98.0
      Speed: 99
      Generation: 6
      Legendary: true
    - index: 794
      '#': 718
      Name: Zygarde50% Forme
      Type 1: Dragon
      Type 2: Ground
      Total: 600
      HP: 108.0
      Attack: 100.0
      Defense: 121.0
      Sp. Atk: 81.0
      Sp. Def: 95.0
      Speed: 95
      Generation: 6
      Legendary: true
    - index: 795
      '#': 719
      Name: Diancie
      Type 1: Rock
      Type 2: Fairy
      Total: 600
      HP: 50.0
      Attack: 100.0
      Defense: 150.0
      Sp. Atk: 100.0
      Sp. Def: 150.0
      Speed: 50
      Generation: 6
      Legendary: true
    - index: 796
      '#': 719
      Name: DiancieMega Diancie
      Type 1: Rock
      Type 2: Fairy
      Total: 700
      HP: 50.0
      Attack: 160.0
      Defense: 110.0
      Sp. Atk: 160.0
      Sp. Def: 110.0
      Speed: 110
      Generation: 6
      Legendary: true
    - index: 797
      '#': 720
      Name: HoopaHoopa Confined
      Type 1: Psychic
      Type 2: Ghost
      Total: 600
      HP: 80.0
      Attack: 110.0
      Defense: 60.0
      Sp. Atk: 150.0
      Sp. Def: 130.0
      Speed: 70
      Generation: 6
      Legendary: true
    - index: 798
      '#': 720
      Name: HoopaHoopa Unbound
      Type 1: Psychic
      Type 2: Dark
      Total: 680
      HP: 80.0
      Attack: 160.0
      Defense: 60.0
      Sp. Atk: 170.0
      Sp. Def: 130.0
      Speed: 80
      Generation: 6
      Legendary: true
    - index: 799
      '#': 721
      Name: Volcanion
      Type 1: Fire
      Type 2: Water
      Total: 600
      HP: 80.0
      Attack: 110.0
      Defense: 120.0
      Sp. Atk: 130.0
      Sp. Def: 90.0
      Speed: 70
      Generation: 6
      Legendary: true
    params_vars_ptype: Dragon
    params_vars_ptype_op: 'not '
    params_vars_hp: 80
    params_vars_hp_op: of at most
    params_expected__type: dataframe_v2
    params_expected__value_schema_fields:
    - name: index
      type: integer
    - name: '#'
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
      type: number
    - name: Attack
      type: number
    - name: Defense
      type: number
    - name: Sp. Atk
      type: number
    - name: Sp. Def
      type: number
    - name: Speed
      type: integer
    - name: Generation
      type: integer
    - name: Legendary
      type: boolean
    params_expected__value_schema_primaryKey:
    - index
    params_expected__value_schema_pandas_version: 1.4.0
    params_expected__value_data:
    - index: 0
      '#': 1
      Name: Bulbasaur
      Type 1: Grass
      Type 2: Poison
      Total: 318
      HP: 45.0
      Attack: 49.0
      Defense: 49.0
      Sp. Atk: 65.0
      Sp. Def: 65.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 1
      '#': 2
      Name: Ivysaur
      Type 1: Grass
      Type 2: Poison
      Total: 405
      HP: 60.0
      Attack: 62.0
      Defense: 63.0
      Sp. Atk: 80.0
      Sp. Def: 80.0
      Speed: 60
      Generation: 1
      Legendary: false
    - index: 2
      '#': 3
      Name: Venusaur
      Type 1: Grass
      Type 2: Poison
      Total: 525
      HP: 80.0
      Attack: 82.0
      Defense: 83.0
      Sp. Atk: 100.0
      Sp. Def: 100.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 3
      '#': 3
      Name: VenusaurMega Venusaur
      Type 1: Grass
      Type 2: Poison
      Total: 625
      HP: 80.0
      Attack: 100.0
      Defense: 123.0
      Sp. Atk: 122.0
      Sp. Def: 120.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 4
      '#': 4
      Name: Charmander
      Type 1: Fire
      Type 2: null
      Total: 309
      HP: 39.0
      Attack: 52.0
      Defense: 43.0
      Sp. Atk: 60.0
      Sp. Def: 50.0
      Speed: 65
      Generation: 1
      Legendary: false
    - index: 5
      '#': 5
      Name: Charmeleon
      Type 1: Fire
      Type 2: null
      Total: 405
      HP: 58.0
      Attack: 64.0
      Defense: 58.0
      Sp. Atk: 80.0
      Sp. Def: 65.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 6
      '#': 6
      Name: Charizard
      Type 1: Fire
      Type 2: Flying
      Total: 534
      HP: 78.0
      Attack: 84.0
      Defense: 78.0
      Sp. Atk: 109.0
      Sp. Def: 85.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 8
      '#': 6
      Name: CharizardMega Charizard Y
      Type 1: Fire
      Type 2: Flying
      Total: 634
      HP: 78.0
      Attack: 104.0
      Defense: 78.0
      Sp. Atk: 159.0
      Sp. Def: 115.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 9
      '#': 7
      Name: Squirtle
      Type 1: Water
      Type 2: null
      Total: 314
      HP: 44.0
      Attack: 48.0
      Defense: 65.0
      Sp. Atk: 50.0
      Sp. Def: 64.0
      Speed: 43
      Generation: 1
      Legendary: false
    - index: 10
      '#': 8
      Name: Wartortle
      Type 1: Water
      Type 2: null
      Total: 405
      HP: 59.0
      Attack: 63.0
      Defense: 80.0
      Sp. Atk: 65.0
      Sp. Def: null
      Speed: 58
      Generation: 1
      Legendary: false
    - index: 11
      '#': 9
      Name: Blastoise
      Type 1: Water
      Type 2: null
      Total: 530
      HP: 79.0
      Attack: 83.0
      Defense: 100.0
      Sp. Atk: 85.0
      Sp. Def: 105.0
      Speed: 78
      Generation: 1
      Legendary: false
    - index: 12
      '#': 9
      Name: BlastoiseMega Blastoise
      Type 1: Water
      Type 2: null
      Total: 630
      HP: 79.0
      Attack: 103.0
      Defense: 120.0
      Sp. Atk: 135.0
      Sp. Def: 115.0
      Speed: 78
      Generation: 1
      Legendary: false
    - index: 13
      '#': 10
      Name: Caterpie
      Type 1: Bug
      Type 2: null
      Total: 195
      HP: 45.0
      Attack: 30.0
      Defense: null
      Sp. Atk: null
      Sp. Def: 20.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 14
      '#': 11
      Name: Metapod
      Type 1: Bug
      Type 2: null
      Total: 205
      HP: 50.0
      Attack: 20.0
      Defense: null
      Sp. Atk: 25.0
      Sp. Def: null
      Speed: 30
      Generation: 1
      Legendary: false
    - index: 16
      '#': 13
      Name: Weedle
      Type 1: Bug
      Type 2: Poison
      Total: 195
      HP: 40.0
      Attack: 35.0
      Defense: 30.0
      Sp. Atk: 20.0
      Sp. Def: null
      Speed: 50
      Generation: 1
      Legendary: false
    - index: 17
      '#': 14
      Name: Kakuna
      Type 1: Bug
      Type 2: Poison
      Total: 205
      HP: 45.0
      Attack: null
      Defense: 50.0
      Sp. Atk: null
      Sp. Def: 25.0
      Speed: 35
      Generation: 1
      Legendary: false
    - index: 18
      '#': 15
      Name: Beedrill
      Type 1: Bug
      Type 2: Poison
      Total: 395
      HP: 65.0
      Attack: 90.0
      Defense: 40.0
      Sp. Atk: 45.0
      Sp. Def: null
      Speed: 75
      Generation: 1
      Legendary: false
    - index: 19
      '#': 15
      Name: BeedrillMega Beedrill
      Type 1: Bug
      Type 2: Poison
      Total: 495
      HP: 65.0
      Attack: 150.0
      Defense: 40.0
      Sp. Atk: 15.0
      Sp. Def: 80.0
      Speed: 145
      Generation: 1
      Legendary: false
    - index: 20
      '#': 16
      Name: Pidgey
      Type 1: Normal
      Type 2: Flying
      Total: 251
      HP: 40.0
      Attack: 45.0
      Defense: 40.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 56
      Generation: 1
      Legendary: false
    - index: 21
      '#': 17
      Name: Pidgeotto
      Type 1: Normal
      Type 2: Flying
      Total: 349
      HP: 63.0
      Attack: 60.0
      Defense: 55.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 71
      Generation: 1
      Legendary: false
    - index: 24
      '#': 19
      Name: Rattata
      Type 1: Normal
      Type 2: null
      Total: 253
      HP: 30.0
      Attack: 56.0
      Defense: 35.0
      Sp. Atk: 25.0
      Sp. Def: 35.0
      Speed: 72
      Generation: 1
      Legendary: false
    - index: 25
      '#': 20
      Name: Raticate
      Type 1: Normal
      Type 2: null
      Total: 413
      HP: 55.0
      Attack: 81.0
      Defense: 60.0
      Sp. Atk: 50.0
      Sp. Def: 70.0
      Speed: 97
      Generation: 1
      Legendary: false
    - index: 26
      '#': 21
      Name: Spearow
      Type 1: Normal
      Type 2: Flying
      Total: 262
      HP: 40.0
      Attack: 60.0
      Defense: 30.0
      Sp. Atk: 31.0
      Sp. Def: 31.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 27
      '#': 22
      Name: Fearow
      Type 1: Normal
      Type 2: Flying
      Total: 442
      HP: 65.0
      Attack: 90.0
      Defense: 65.0
      Sp. Atk: 61.0
      Sp. Def: 61.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 28
      '#': 23
      Name: Ekans
      Type 1: Poison
      Type 2: null
      Total: 288
      HP: 35.0
      Attack: 60.0
      Defense: 44.0
      Sp. Atk: 40.0
      Sp. Def: 54.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 29
      '#': 24
      Name: Arbok
      Type 1: Poison
      Type 2: null
      Total: 438
      HP: 60.0
      Attack: 85.0
      Defense: 69.0
      Sp. Atk: 65.0
      Sp. Def: 79.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 30
      '#': 25
      Name: Pikachu
      Type 1: Electric
      Type 2: null
      Total: 320
      HP: 35.0
      Attack: 55.0
      Defense: 40.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 31
      '#': 26
      Name: Raichu
      Type 1: Electric
      Type 2: null
      Total: 485
      HP: 60.0
      Attack: 90.0
      Defense: 55.0
      Sp. Atk: 90.0
      Sp. Def: 80.0
      Speed: 110
      Generation: 1
      Legendary: false
    - index: 32
      '#': 27
      Name: Sandshrew
      Type 1: Ground
      Type 2: null
      Total: 300
      HP: 50.0
      Attack: 75.0
      Defense: 85.0
      Sp. Atk: 20.0
      Sp. Def: 30.0
      Speed: 40
      Generation: 1
      Legendary: false
    - index: 33
      '#': 28
      Name: Sandslash
      Type 1: Ground
      Type 2: null
      Total: 450
      HP: 75.0
      Attack: 100.0
      Defense: 110.0
      Sp. Atk: 45.0
      Sp. Def: 55.0
      Speed: 65
      Generation: 1
      Legendary: false
    - index: 34
      '#': 29
      Name: Nidoran♀
      Type 1: Poison
      Type 2: null
      Total: 275
      HP: 55.0
      Attack: 47.0
      Defense: 52.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 41
      Generation: 1
      Legendary: false
    - index: 35
      '#': 30
      Name: Nidorina
      Type 1: Poison
      Type 2: null
      Total: 365
      HP: 70.0
      Attack: 62.0
      Defense: 67.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 56
      Generation: 1
      Legendary: false
    - index: 37
      '#': 32
      Name: Nidoran♂
      Type 1: Poison
      Type 2: null
      Total: 273
      HP: 46.0
      Attack: 57.0
      Defense: 40.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 50
      Generation: 1
      Legendary: false
    - index: 38
      '#': 33
      Name: Nidorino
      Type 1: Poison
      Type 2: null
      Total: 365
      HP: 61.0
      Attack: 72.0
      Defense: 57.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 65
      Generation: 1
      Legendary: false
    - index: 40
      '#': 35
      Name: Clefairy
      Type 1: Fairy
      Type 2: null
      Total: 323
      HP: 70.0
      Attack: 45.0
      Defense: 48.0
      Sp. Atk: 60.0
      Sp. Def: 65.0
      Speed: 35
      Generation: 1
      Legendary: false
    - index: 42
      '#': 37
      Name: Vulpix
      Type 1: Fire
      Type 2: null
      Total: 299
      HP: 38.0
      Attack: 41.0
      Defense: 40.0
      Sp. Atk: 50.0
      Sp. Def: 65.0
      Speed: 65
      Generation: 1
      Legendary: false
    - index: 43
      '#': 38
      Name: Ninetales
      Type 1: Fire
      Type 2: null
      Total: 505
      HP: 73.0
      Attack: 76.0
      Defense: 75.0
      Sp. Atk: 81.0
      Sp. Def: 100.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 46
      '#': 41
      Name: Zubat
      Type 1: Poison
      Type 2: Flying
      Total: 245
      HP: 40.0
      Attack: 45.0
      Defense: 35.0
      Sp. Atk: 30.0
      Sp. Def: 40.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 47
      '#': 42
      Name: Golbat
      Type 1: Poison
      Type 2: Flying
      Total: 455
      HP: 75.0
      Attack: 80.0
      Defense: 70.0
      Sp. Atk: 65.0
      Sp. Def: 75.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 48
      '#': 43
      Name: Oddish
      Type 1: Grass
      Type 2: Poison
      Total: 320
      HP: 45.0
      Attack: 50.0
      Defense: 55.0
      Sp. Atk: 75.0
      Sp. Def: 65.0
      Speed: 30
      Generation: 1
      Legendary: false
    - index: 49
      '#': 44
      Name: Gloom
      Type 1: Grass
      Type 2: Poison
      Total: 395
      HP: 60.0
      Attack: 65.0
      Defense: 70.0
      Sp. Atk: 85.0
      Sp. Def: 75.0
      Speed: 40
      Generation: 1
      Legendary: false
    - index: 50
      '#': 45
      Name: Vileplume
      Type 1: Grass
      Type 2: Poison
      Total: 490
      HP: 75.0
      Attack: 80.0
      Defense: 85.0
      Sp. Atk: 110.0
      Sp. Def: 90.0
      Speed: 50
      Generation: 1
      Legendary: false
    - index: 51
      '#': 46
      Name: Paras
      Type 1: Bug
      Type 2: Grass
      Total: 285
      HP: 35.0
      Attack: 70.0
      Defense: 55.0
      Sp. Atk: 45.0
      Sp. Def: 55.0
      Speed: 25
      Generation: 1
      Legendary: false
    - index: 52
      '#': 47
      Name: Parasect
      Type 1: Bug
      Type 2: Grass
      Total: 405
      HP: 60.0
      Attack: 95.0
      Defense: 80.0
      Sp. Atk: 60.0
      Sp. Def: 80.0
      Speed: 30
      Generation: 1
      Legendary: false
    - index: 53
      '#': 48
      Name: Venonat
      Type 1: Bug
      Type 2: Poison
      Total: 305
      HP: 60.0
      Attack: 55.0
      Defense: 50.0
      Sp. Atk: 40.0
      Sp. Def: 55.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 54
      '#': 49
      Name: Venomoth
      Type 1: Bug
      Type 2: Poison
      Total: 450
      HP: 70.0
      Attack: 65.0
      Defense: 60.0
      Sp. Atk: 90.0
      Sp. Def: 75.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 55
      '#': 50
      Name: Diglett
      Type 1: Ground
      Type 2: null
      Total: 265
      HP: 10.0
      Attack: 55.0
      Defense: 25.0
      Sp. Atk: 35.0
      Sp. Def: 45.0
      Speed: 95
      Generation: 1
      Legendary: false
    - index: 56
      '#': 51
      Name: Dugtrio
      Type 1: Ground
      Type 2: null
      Total: 405
      HP: 35.0
      Attack: 80.0
      Defense: 50.0
      Sp. Atk: 50.0
      Sp. Def: 70.0
      Speed: 120
      Generation: 1
      Legendary: false
    - index: 57
      '#': 52
      Name: Meowth
      Type 1: Normal
      Type 2: null
      Total: 290
      HP: 40.0
      Attack: 45.0
      Defense: 35.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 58
      '#': 53
      Name: Persian
      Type 1: Normal
      Type 2: null
      Total: 440
      HP: 65.0
      Attack: 70.0
      Defense: 60.0
      Sp. Atk: 65.0
      Sp. Def: 65.0
      Speed: 115
      Generation: 1
      Legendary: false
    - index: 59
      '#': 54
      Name: Psyduck
      Type 1: Water
      Type 2: null
      Total: 320
      HP: 50.0
      Attack: 52.0
      Defense: 48.0
      Sp. Atk: 65.0
      Sp. Def: 50.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 60
      '#': 55
      Name: Golduck
      Type 1: Water
      Type 2: null
      Total: 500
      HP: 80.0
      Attack: 82.0
      Defense: 78.0
      Sp. Atk: 95.0
      Sp. Def: 80.0
      Speed: 85
      Generation: 1
      Legendary: false
    - index: 61
      '#': 56
      Name: Mankey
      Type 1: Fighting
      Type 2: null
      Total: 305
      HP: 40.0
      Attack: 80.0
      Defense: 35.0
      Sp. Atk: 35.0
      Sp. Def: 45.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 62
      '#': 57
      Name: Primeape
      Type 1: Fighting
      Type 2: null
      Total: 455
      HP: 65.0
      Attack: 105.0
      Defense: 60.0
      Sp. Atk: 60.0
      Sp. Def: 70.0
      Speed: 95
      Generation: 1
      Legendary: false
    - index: 63
      '#': 58
      Name: Growlithe
      Type 1: Fire
      Type 2: null
      Total: 350
      HP: 55.0
      Attack: 70.0
      Defense: 45.0
      Sp. Atk: 70.0
      Sp. Def: 50.0
      Speed: 60
      Generation: 1
      Legendary: false
    - index: 65
      '#': 60
      Name: Poliwag
      Type 1: Water
      Type 2: null
      Total: 300
      HP: 40.0
      Attack: 50.0
      Defense: 40.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 66
      '#': 61
      Name: Poliwhirl
      Type 1: Water
      Type 2: null
      Total: 385
      HP: 65.0
      Attack: 65.0
      Defense: 65.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 68
      '#': 63
      Name: Abra
      Type 1: Psychic
      Type 2: null
      Total: 310
      HP: 25.0
      Attack: 20.0
      Defense: 15.0
      Sp. Atk: 105.0
      Sp. Def: 55.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 69
      '#': 64
      Name: Kadabra
      Type 1: Psychic
      Type 2: null
      Total: 400
      HP: 40.0
      Attack: 35.0
      Defense: 30.0
      Sp. Atk: 120.0
      Sp. Def: 70.0
      Speed: 105
      Generation: 1
      Legendary: false
    - index: 70
      '#': 65
      Name: Alakazam
      Type 1: Psychic
      Type 2: null
      Total: 500
      HP: 55.0
      Attack: 50.0
      Defense: 45.0
      Sp. Atk: 135.0
      Sp. Def: 95.0
      Speed: 120
      Generation: 1
      Legendary: false
    - index: 71
      '#': 65
      Name: AlakazamMega Alakazam
      Type 1: Psychic
      Type 2: null
      Total: 590
      HP: 55.0
      Attack: 50.0
      Defense: 65.0
      Sp. Atk: 175.0
      Sp. Def: 95.0
      Speed: 150
      Generation: 1
      Legendary: false
    - index: 72
      '#': 66
      Name: Machop
      Type 1: Fighting
      Type 2: null
      Total: 305
      HP: 70.0
      Attack: 80.0
      Defense: 50.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 35
      Generation: 1
      Legendary: false
    - index: 73
      '#': 67
      Name: Machoke
      Type 1: Fighting
      Type 2: null
      Total: 405
      HP: 80.0
      Attack: 100.0
      Defense: 70.0
      Sp. Atk: 50.0
      Sp. Def: 60.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 75
      '#': 69
      Name: Bellsprout
      Type 1: Grass
      Type 2: Poison
      Total: 300
      HP: 50.0
      Attack: 75.0
      Defense: 35.0
      Sp. Atk: 70.0
      Sp. Def: 30.0
      Speed: 40
      Generation: 1
      Legendary: false
    - index: 76
      '#': 70
      Name: Weepinbell
      Type 1: Grass
      Type 2: Poison
      Total: 390
      HP: 65.0
      Attack: 90.0
      Defense: 50.0
      Sp. Atk: 85.0
      Sp. Def: 45.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 77
      '#': 71
      Name: Victreebel
      Type 1: Grass
      Type 2: Poison
      Total: 490
      HP: 80.0
      Attack: 105.0
      Defense: 65.0
      Sp. Atk: 100.0
      Sp. Def: 70.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 78
      '#': 72
      Name: Tentacool
      Type 1: Water
      Type 2: Poison
      Total: 335
      HP: 40.0
      Attack: 40.0
      Defense: 35.0
      Sp. Atk: 50.0
      Sp. Def: 100.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 79
      '#': 73
      Name: Tentacruel
      Type 1: Water
      Type 2: Poison
      Total: 515
      HP: 80.0
      Attack: 70.0
      Defense: 65.0
      Sp. Atk: 80.0
      Sp. Def: 120.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 80
      '#': 74
      Name: Geodude
      Type 1: Rock
      Type 2: Ground
      Total: 300
      HP: 40.0
      Attack: 80.0
      Defense: 100.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 20
      Generation: 1
      Legendary: false
    - index: 81
      '#': 75
      Name: Graveler
      Type 1: Rock
      Type 2: Ground
      Total: 390
      HP: 55.0
      Attack: 95.0
      Defense: 115.0
      Sp. Atk: 45.0
      Sp. Def: 45.0
      Speed: 35
      Generation: 1
      Legendary: false
    - index: 82
      '#': 76
      Name: Golem
      Type 1: Rock
      Type 2: Ground
      Total: 495
      HP: 80.0
      Attack: 120.0
      Defense: 130.0
      Sp. Atk: 55.0
      Sp. Def: 65.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 83
      '#': 77
      Name: Ponyta
      Type 1: Fire
      Type 2: null
      Total: 410
      HP: 50.0
      Attack: 85.0
      Defense: 55.0
      Sp. Atk: 65.0
      Sp. Def: 65.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 84
      '#': 78
      Name: Rapidash
      Type 1: Fire
      Type 2: null
      Total: 500
      HP: 65.0
      Attack: 100.0
      Defense: 70.0
      Sp. Atk: 80.0
      Sp. Def: 80.0
      Speed: 105
      Generation: 1
      Legendary: false
    - index: 88
      '#': 81
      Name: Magnemite
      Type 1: Electric
      Type 2: Steel
      Total: 325
      HP: 25.0
      Attack: 35.0
      Defense: 70.0
      Sp. Atk: 95.0
      Sp. Def: 55.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 89
      '#': 82
      Name: Magneton
      Type 1: Electric
      Type 2: Steel
      Total: 465
      HP: 50.0
      Attack: 60.0
      Defense: 95.0
      Sp. Atk: 120.0
      Sp. Def: 70.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 90
      '#': 83
      Name: Farfetch'd
      Type 1: Normal
      Type 2: Flying
      Total: 352
      HP: 52.0
      Attack: 65.0
      Defense: 55.0
      Sp. Atk: 58.0
      Sp. Def: 62.0
      Speed: 60
      Generation: 1
      Legendary: false
    - index: 91
      '#': 84
      Name: Doduo
      Type 1: Normal
      Type 2: Flying
      Total: 310
      HP: 35.0
      Attack: 85.0
      Defense: 45.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 75
      Generation: 1
      Legendary: false
    - index: 92
      '#': 85
      Name: Dodrio
      Type 1: Normal
      Type 2: Flying
      Total: 460
      HP: 60.0
      Attack: 110.0
      Defense: 70.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 93
      '#': 86
      Name: Seel
      Type 1: Water
      Type 2: null
      Total: 325
      HP: 65.0
      Attack: 45.0
      Defense: 55.0
      Sp. Atk: 45.0
      Sp. Def: 70.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 95
      '#': 88
      Name: Grimer
      Type 1: Poison
      Type 2: null
      Total: 325
      HP: 80.0
      Attack: 80.0
      Defense: 50.0
      Sp. Atk: 40.0
      Sp. Def: 50.0
      Speed: 25
      Generation: 1
      Legendary: false
    - index: 97
      '#': 90
      Name: Shellder
      Type 1: Water
      Type 2: null
      Total: 305
      HP: 30.0
      Attack: 65.0
      Defense: 100.0
      Sp. Atk: 45.0
      Sp. Def: 25.0
      Speed: 40
      Generation: 1
      Legendary: false
    - index: 98
      '#': 91
      Name: Cloyster
      Type 1: Water
      Type 2: Ice
      Total: 525
      HP: 50.0
      Attack: 95.0
      Defense: 180.0
      Sp. Atk: 85.0
      Sp. Def: 45.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 99
      '#': 92
      Name: Gastly
      Type 1: Ghost
      Type 2: Poison
      Total: 310
      HP: 30.0
      Attack: 35.0
      Defense: 30.0
      Sp. Atk: 100.0
      Sp. Def: 35.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 100
      '#': 93
      Name: Haunter
      Type 1: Ghost
      Type 2: Poison
      Total: 405
      HP: 45.0
      Attack: 50.0
      Defense: 45.0
      Sp. Atk: 115.0
      Sp. Def: 55.0
      Speed: 95
      Generation: 1
      Legendary: false
    - index: 101
      '#': 94
      Name: Gengar
      Type 1: Ghost
      Type 2: Poison
      Total: 500
      HP: 60.0
      Attack: 65.0
      Defense: 60.0
      Sp. Atk: 130.0
      Sp. Def: 75.0
      Speed: 110
      Generation: 1
      Legendary: false
    - index: 102
      '#': 94
      Name: GengarMega Gengar
      Type 1: Ghost
      Type 2: Poison
      Total: 600
      HP: 60.0
      Attack: 65.0
      Defense: 80.0
      Sp. Atk: 170.0
      Sp. Def: 95.0
      Speed: 130
      Generation: 1
      Legendary: false
    - index: 103
      '#': 95
      Name: Onix
      Type 1: Rock
      Type 2: Ground
      Total: 385
      HP: 35.0
      Attack: 45.0
      Defense: 160.0
      Sp. Atk: 30.0
      Sp. Def: 45.0
      Speed: 70
      Generation: 1
      Legendary: false
    - index: 104
      '#': 96
      Name: Drowzee
      Type 1: Psychic
      Type 2: null
      Total: 328
      HP: 60.0
      Attack: 48.0
      Defense: 45.0
      Sp. Atk: 43.0
      Sp. Def: 90.0
      Speed: 42
      Generation: 1
      Legendary: false
    - index: 106
      '#': 98
      Name: Krabby
      Type 1: Water
      Type 2: null
      Total: 325
      HP: 30.0
      Attack: 105.0
      Defense: 90.0
      Sp. Atk: 25.0
      Sp. Def: 25.0
      Speed: 50
      Generation: 1
      Legendary: false
    - index: 107
      '#': 99
      Name: Kingler
      Type 1: Water
      Type 2: null
      Total: 475
      HP: 55.0
      Attack: 130.0
      Defense: 115.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 75
      Generation: 1
      Legendary: false
    - index: 108
      '#': 100
      Name: Voltorb
      Type 1: Electric
      Type 2: null
      Total: 330
      HP: 40.0
      Attack: 30.0
      Defense: 50.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 100
      Generation: 1
      Legendary: false
    - index: 109
      '#': 101
      Name: Electrode
      Type 1: Electric
      Type 2: null
      Total: 480
      HP: 60.0
      Attack: 50.0
      Defense: 70.0
      Sp. Atk: 80.0
      Sp. Def: 80.0
      Speed: 140
      Generation: 1
      Legendary: false
    - index: 110
      '#': 102
      Name: Exeggcute
      Type 1: Grass
      Type 2: Psychic
      Total: 325
      HP: 60.0
      Attack: 40.0
      Defense: 80.0
      Sp. Atk: 60.0
      Sp. Def: 45.0
      Speed: 40
      Generation: 1
      Legendary: false
    - index: 112
      '#': 104
      Name: Cubone
      Type 1: Ground
      Type 2: null
      Total: 320
      HP: 50.0
      Attack: 50.0
      Defense: 95.0
      Sp. Atk: 40.0
      Sp. Def: 50.0
      Speed: 35
      Generation: 1
      Legendary: false
    - index: 113
      '#': 105
      Name: Marowak
      Type 1: Ground
      Type 2: null
      Total: 425
      HP: 60.0
      Attack: 80.0
      Defense: 110.0
      Sp. Atk: 50.0
      Sp. Def: 80.0
      Speed: 45
      Generation: 1
      Legendary: false
    - index: 114
      '#': 106
      Name: Hitmonlee
      Type 1: Fighting
      Type 2: null
      Total: 455
      HP: 50.0
      Attack: 120.0
      Defense: 53.0
      Sp. Atk: 35.0
      Sp. Def: 110.0
      Speed: 87
      Generation: 1
      Legendary: false
    - index: 115
      '#': 107
      Name: Hitmonchan
      Type 1: Fighting
      Type 2: null
      Total: 455
      HP: 50.0
      Attack: 105.0
      Defense: 79.0
      Sp. Atk: 35.0
      Sp. Def: 110.0
      Speed: 76
      Generation: 1
      Legendary: false
    - index: 117
      '#': 109
      Name: Koffing
      Type 1: Poison
      Type 2: null
      Total: 340
      HP: 40.0
      Attack: 65.0
      Defense: 95.0
      Sp. Atk: 60.0
      Sp. Def: 45.0
      Speed: 35
      Generation: 1
      Legendary: false
    - index: 118
      '#': 110
      Name: Weezing
      Type 1: Poison
      Type 2: null
      Total: 490
      HP: 65.0
      Attack: 90.0
      Defense: 120.0
      Sp. Atk: 85.0
      Sp. Def: 70.0
      Speed: 60
      Generation: 1
      Legendary: false
    - index: 119
      '#': 111
      Name: Rhyhorn
      Type 1: Ground
      Type 2: Rock
      Total: 345
      HP: 80.0
      Attack: 85.0
      Defense: 95.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 25
      Generation: 1
      Legendary: false
    - index: 122
      '#': 114
      Name: Tangela
      Type 1: Grass
      Type 2: null
      Total: 435
      HP: 65.0
      Attack: 55.0
      Defense: 115.0
      Sp. Atk: 100.0
      Sp. Def: 40.0
      Speed: 60
      Generation: 1
      Legendary: false
    - index: 125
      '#': 116
      Name: Horsea
      Type 1: Water
      Type 2: null
      Total: 295
      HP: 30.0
      Attack: 40.0
      Defense: 70.0
      Sp. Atk: 70.0
      Sp. Def: 25.0
      Speed: 60
      Generation: 1
      Legendary: false
    - index: 126
      '#': 117
      Name: Seadra
      Type 1: Water
      Type 2: null
      Total: 440
      HP: 55.0
      Attack: 65.0
      Defense: 95.0
      Sp. Atk: 95.0
      Sp. Def: 45.0
      Speed: 85
      Generation: 1
      Legendary: false
    - index: 127
      '#': 118
      Name: Goldeen
      Type 1: Water
      Type 2: null
      Total: 320
      HP: 45.0
      Attack: 67.0
      Defense: 60.0
      Sp. Atk: 35.0
      Sp. Def: 50.0
      Speed: 63
      Generation: 1
      Legendary: false
    - index: 128
      '#': 119
      Name: Seaking
      Type 1: Water
      Type 2: null
      Total: 450
      HP: 80.0
      Attack: 92.0
      Defense: 65.0
      Sp. Atk: 65.0
      Sp. Def: 80.0
      Speed: 68
      Generation: 1
      Legendary: false
    - index: 129
      '#': 120
      Name: Staryu
      Type 1: Water
      Type 2: null
      Total: 340
      HP: 30.0
      Attack: 45.0
      Defense: 55.0
      Sp. Atk: 70.0
      Sp. Def: 55.0
      Speed: 85
      Generation: 1
      Legendary: false
    - index: 130
      '#': 121
      Name: Starmie
      Type 1: Water
      Type 2: Psychic
      Total: 520
      HP: 60.0
      Attack: 75.0
      Defense: 85.0
      Sp. Atk: 100.0
      Sp. Def: 85.0
      Speed: 115
      Generation: 1
      Legendary: false
    - index: 131
      '#': 122
      Name: Mr. Mime
      Type 1: Psychic
      Type 2: Fairy
      Total: 460
      HP: 40.0
      Attack: 45.0
      Defense: 65.0
      Sp. Atk: 100.0
      Sp. Def: 120.0
      Speed: 90
      Generation: 1
      Legendary: false
    - index: 132
      '#': 123
      Name: Scyther
      Type 1: Bug
      Type 2: Flying
      Total: 500
      HP: 70.0
      Attack: 110.0
      Defense: 80.0
      Sp. Atk: 55.0
      Sp. Def: 80.0
      Speed: 105
      Generation: 1
      Legendary: false
    - index: 133
      '#': 124
      Name: Jynx
      Type 1: Ice
      Type 2: Psychic
      Total: 455
      HP: 65.0
      Attack: 50.0
      Defense: 35.0
      Sp. Atk: 115.0
      Sp. Def: 95.0
      Speed: 95
      Generation: 1
      Legendary: false
    - index: 134
      '#': 125
      Name: Electabuzz
      Type 1: Electric
      Type 2: null
      Total: 490
      HP: 65.0
      Attack: 83.0
      Defense: 57.0
      Sp. Atk: 95.0
      Sp. Def: 85.0
      Speed: 105
      Generation: 1
      Legendary: false
    - index: 135
      '#': 126
      Name: Magmar
      Type 1: Fire
      Type 2: null
      Total: 495
      HP: 65.0
      Attack: 95.0
      Defense: 57.0
      Sp. Atk: 100.0
      Sp. Def: 85.0
      Speed: 93
      Generation: 1
      Legendary: false
    - index: 136
      '#': 127
      Name: Pinsir
      Type 1: Bug
      Type 2: null
      Total: 500
      HP: 65.0
      Attack: 125.0
      Defense: 100.0
      Sp. Atk: 55.0
      Sp. Def: 70.0
      Speed: 85
      Generation: 1
      Legendary: false
    - index: 137
      '#': 127
      Name: PinsirMega Pinsir
      Type 1: Bug
      Type 2: Flying
      Total: 600
      HP: 65.0
      Attack: 155.0
      Defense: 120.0
      Sp. Atk: 65.0
      Sp. Def: 90.0
      Speed: 105
      Generation: 1
      Legendary: false
    - index: 138
      '#': 128
      Name: Tauros
      Type 1: Normal
      Type 2: null
      Total: 490
      HP: 75.0
      Attack: 100.0
      Defense: 95.0
      Sp. Atk: 40.0
      Sp. Def: 70.0
      Speed: 110
      Generation: 1
      Legendary: false
    - index: 139
      '#': 129
      Name: Magikarp
      Type 1: Water
      Type 2: null
      Total: 200
      HP: 20.0
      Attack: 10.0
      Defense: 55.0
      Sp. Atk: 15.0
      Sp. Def: 20.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 143
      '#': 132
      Name: Ditto
      Type 1: Normal
      Type 2: null
      Total: 288
      HP: 48.0
      Attack: 48.0
      Defense: 48.0
      Sp. Atk: 48.0
      Sp. Def: 48.0
      Speed: 48
      Generation: 1
      Legendary: false
    - index: 144
      '#': 133
      Name: Eevee
      Type 1: Normal
      Type 2: null
      Total: 325
      HP: 55.0
      Attack: 55.0
      Defense: 50.0
      Sp. Atk: 45.0
      Sp. Def: 65.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 146
      '#': 135
      Name: Jolteon
      Type 1: Electric
      Type 2: null
      Total: 525
      HP: 65.0
      Attack: 65.0
      Defense: 60.0
      Sp. Atk: 110.0
      Sp. Def: 95.0
      Speed: 130
      Generation: 1
      Legendary: false
    - index: 147
      '#': 136
      Name: Flareon
      Type 1: Fire
      Type 2: null
      Total: 525
      HP: 65.0
      Attack: 130.0
      Defense: 60.0
      Sp. Atk: 95.0
      Sp. Def: 110.0
      Speed: 65
      Generation: 1
      Legendary: false
    - index: 148
      '#': 137
      Name: Porygon
      Type 1: Normal
      Type 2: null
      Total: 395
      HP: 65.0
      Attack: 60.0
      Defense: 70.0
      Sp. Atk: 85.0
      Sp. Def: 75.0
      Speed: 40
      Generation: 1
      Legendary: false
    - index: 149
      '#': 138
      Name: Omanyte
      Type 1: Rock
      Type 2: Water
      Total: 355
      HP: 35.0
      Attack: 40.0
      Defense: 100.0
      Sp. Atk: 90.0
      Sp. Def: 55.0
      Speed: 35
      Generation: 1
      Legendary: false
    - index: 150
      '#': 139
      Name: Omastar
      Type 1: Rock
      Type 2: Water
      Total: 495
      HP: 70.0
      Attack: 60.0
      Defense: 125.0
      Sp. Atk: 115.0
      Sp. Def: 70.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 151
      '#': 140
      Name: Kabuto
      Type 1: Rock
      Type 2: Water
      Total: 355
      HP: 30.0
      Attack: 80.0
      Defense: 90.0
      Sp. Atk: 55.0
      Sp. Def: 45.0
      Speed: 55
      Generation: 1
      Legendary: false
    - index: 152
      '#': 141
      Name: Kabutops
      Type 1: Rock
      Type 2: Water
      Total: 495
      HP: 60.0
      Attack: 115.0
      Defense: 105.0
      Sp. Atk: 65.0
      Sp. Def: 70.0
      Speed: 80
      Generation: 1
      Legendary: false
    - index: 153
      '#': 142
      Name: Aerodactyl
      Type 1: Rock
      Type 2: Flying
      Total: 515
      HP: 80.0
      Attack: 105.0
      Defense: 65.0
      Sp. Atk: 60.0
      Sp. Def: 75.0
      Speed: 130
      Generation: 1
      Legendary: false
    - index: 154
      '#': 142
      Name: AerodactylMega Aerodactyl
      Type 1: Rock
      Type 2: Flying
      Total: 615
      HP: 80.0
      Attack: 135.0
      Defense: 85.0
      Sp. Atk: 70.0
      Sp. Def: 95.0
      Speed: 150
      Generation: 1
      Legendary: false
    - index: 166
      '#': 152
      Name: Chikorita
      Type 1: Grass
      Type 2: null
      Total: 318
      HP: 45.0
      Attack: 49.0
      Defense: 65.0
      Sp. Atk: 49.0
      Sp. Def: 65.0
      Speed: 45
      Generation: 2
      Legendary: false
    - index: 167
      '#': 153
      Name: Bayleef
      Type 1: Grass
      Type 2: null
      Total: 405
      HP: 60.0
      Attack: 62.0
      Defense: 80.0
      Sp. Atk: 63.0
      Sp. Def: 80.0
      Speed: 60
      Generation: 2
      Legendary: false
    - index: 168
      '#': 154
      Name: Meganium
      Type 1: Grass
      Type 2: null
      Total: 525
      HP: 80.0
      Attack: 82.0
      Defense: 100.0
      Sp. Atk: 83.0
      Sp. Def: 100.0
      Speed: 80
      Generation: 2
      Legendary: false
    - index: 169
      '#': 155
      Name: Cyndaquil
      Type 1: Fire
      Type 2: null
      Total: 309
      HP: 39.0
      Attack: 52.0
      Defense: 43.0
      Sp. Atk: 60.0
      Sp. Def: 50.0
      Speed: 65
      Generation: 2
      Legendary: false
    - index: 170
      '#': 156
      Name: Quilava
      Type 1: Fire
      Type 2: null
      Total: 405
      HP: 58.0
      Attack: 64.0
      Defense: 58.0
      Sp. Atk: 80.0
      Sp. Def: 65.0
      Speed: 80
      Generation: 2
      Legendary: false
    - index: 171
      '#': 157
      Name: Typhlosion
      Type 1: Fire
      Type 2: null
      Total: 534
      HP: 78.0
      Attack: 84.0
      Defense: 78.0
      Sp. Atk: 109.0
      Sp. Def: 85.0
      Speed: 100
      Generation: 2
      Legendary: false
    - index: 172
      '#': 158
      Name: Totodile
      Type 1: Water
      Type 2: null
      Total: 314
      HP: 50.0
      Attack: 65.0
      Defense: 64.0
      Sp. Atk: 44.0
      Sp. Def: 48.0
      Speed: 43
      Generation: 2
      Legendary: false
    - index: 173
      '#': 159
      Name: Croconaw
      Type 1: Water
      Type 2: null
      Total: 405
      HP: 65.0
      Attack: 80.0
      Defense: 80.0
      Sp. Atk: 59.0
      Sp. Def: 63.0
      Speed: 58
      Generation: 2
      Legendary: false
    - index: 175
      '#': 161
      Name: Sentret
      Type 1: Normal
      Type 2: null
      Total: 215
      HP: 35.0
      Attack: 46.0
      Defense: 34.0
      Sp. Atk: 35.0
      Sp. Def: 45.0
      Speed: 20
      Generation: 2
      Legendary: false
    - index: 177
      '#': 163
      Name: Hoothoot
      Type 1: Normal
      Type 2: Flying
      Total: 262
      HP: 60.0
      Attack: 30.0
      Defense: 30.0
      Sp. Atk: 36.0
      Sp. Def: 56.0
      Speed: 50
      Generation: 2
      Legendary: false
    - index: 179
      '#': 165
      Name: Ledyba
      Type 1: Bug
      Type 2: Flying
      Total: 265
      HP: 40.0
      Attack: 20.0
      Defense: 30.0
      Sp. Atk: 40.0
      Sp. Def: 80.0
      Speed: 55
      Generation: 2
      Legendary: false
    - index: 180
      '#': 166
      Name: Ledian
      Type 1: Bug
      Type 2: Flying
      Total: 390
      HP: 55.0
      Attack: 35.0
      Defense: 50.0
      Sp. Atk: 55.0
      Sp. Def: 110.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 181
      '#': 167
      Name: Spinarak
      Type 1: Bug
      Type 2: Poison
      Total: 250
      HP: 40.0
      Attack: 60.0
      Defense: 40.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 182
      '#': 168
      Name: Ariados
      Type 1: Bug
      Type 2: Poison
      Total: 390
      HP: 70.0
      Attack: 90.0
      Defense: 70.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 40
      Generation: 2
      Legendary: false
    - index: 184
      '#': 170
      Name: Chinchou
      Type 1: Water
      Type 2: Electric
      Total: 330
      HP: 75.0
      Attack: 38.0
      Defense: 38.0
      Sp. Atk: 56.0
      Sp. Def: 56.0
      Speed: 67
      Generation: 2
      Legendary: false
    - index: 186
      '#': 172
      Name: Pichu
      Type 1: Electric
      Type 2: null
      Total: 205
      HP: 20.0
      Attack: 40.0
      Defense: 15.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 60
      Generation: 2
      Legendary: false
    - index: 187
      '#': 173
      Name: Cleffa
      Type 1: Fairy
      Type 2: null
      Total: 218
      HP: 50.0
      Attack: 25.0
      Defense: 28.0
      Sp. Atk: 45.0
      Sp. Def: 55.0
      Speed: 15
      Generation: 2
      Legendary: false
    - index: 189
      '#': 175
      Name: Togepi
      Type 1: Fairy
      Type 2: null
      Total: 245
      HP: 35.0
      Attack: 20.0
      Defense: 65.0
      Sp. Atk: 40.0
      Sp. Def: 65.0
      Speed: 20
      Generation: 2
      Legendary: false
    - index: 190
      '#': 176
      Name: Togetic
      Type 1: Fairy
      Type 2: Flying
      Total: 405
      HP: 55.0
      Attack: 40.0
      Defense: 85.0
      Sp. Atk: 80.0
      Sp. Def: 105.0
      Speed: 40
      Generation: 2
      Legendary: false
    - index: 191
      '#': 177
      Name: Natu
      Type 1: Psychic
      Type 2: Flying
      Total: 320
      HP: 40.0
      Attack: 50.0
      Defense: 45.0
      Sp. Atk: 70.0
      Sp. Def: 45.0
      Speed: 70
      Generation: 2
      Legendary: false
    - index: 192
      '#': 178
      Name: Xatu
      Type 1: Psychic
      Type 2: Flying
      Total: 470
      HP: 65.0
      Attack: 75.0
      Defense: 70.0
      Sp. Atk: 95.0
      Sp. Def: 70.0
      Speed: 95
      Generation: 2
      Legendary: false
    - index: 193
      '#': 179
      Name: Mareep
      Type 1: Electric
      Type 2: null
      Total: 280
      HP: 55.0
      Attack: 40.0
      Defense: 40.0
      Sp. Atk: 65.0
      Sp. Def: 45.0
      Speed: 35
      Generation: 2
      Legendary: false
    - index: 194
      '#': 180
      Name: Flaaffy
      Type 1: Electric
      Type 2: null
      Total: 365
      HP: 70.0
      Attack: 55.0
      Defense: 55.0
      Sp. Atk: 80.0
      Sp. Def: 60.0
      Speed: 45
      Generation: 2
      Legendary: false
    - index: 197
      '#': 182
      Name: Bellossom
      Type 1: Grass
      Type 2: null
      Total: 490
      HP: 75.0
      Attack: 80.0
      Defense: 95.0
      Sp. Atk: 90.0
      Sp. Def: 100.0
      Speed: 50
      Generation: 2
      Legendary: false
    - index: 198
      '#': 183
      Name: Marill
      Type 1: Water
      Type 2: Fairy
      Total: 250
      HP: 70.0
      Attack: 20.0
      Defense: 50.0
      Sp. Atk: 20.0
      Sp. Def: 50.0
      Speed: 40
      Generation: 2
      Legendary: false
    - index: 200
      '#': 185
      Name: Sudowoodo
      Type 1: Rock
      Type 2: null
      Total: 410
      HP: 70.0
      Attack: 100.0
      Defense: 115.0
      Sp. Atk: 30.0
      Sp. Def: 65.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 202
      '#': 187
      Name: Hoppip
      Type 1: Grass
      Type 2: Flying
      Total: 250
      HP: 35.0
      Attack: 35.0
      Defense: 40.0
      Sp. Atk: 35.0
      Sp. Def: 55.0
      Speed: 50
      Generation: 2
      Legendary: false
    - index: 203
      '#': 188
      Name: Skiploom
      Type 1: Grass
      Type 2: Flying
      Total: 340
      HP: 55.0
      Attack: 45.0
      Defense: 50.0
      Sp. Atk: 45.0
      Sp. Def: 65.0
      Speed: 80
      Generation: 2
      Legendary: false
    - index: 204
      '#': 189
      Name: Jumpluff
      Type 1: Grass
      Type 2: Flying
      Total: 460
      HP: 75.0
      Attack: 55.0
      Defense: 70.0
      Sp. Atk: 55.0
      Sp. Def: 95.0
      Speed: 110
      Generation: 2
      Legendary: false
    - index: 205
      '#': 190
      Name: Aipom
      Type 1: Normal
      Type 2: null
      Total: 360
      HP: 55.0
      Attack: 70.0
      Defense: 55.0
      Sp. Atk: 40.0
      Sp. Def: 55.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 206
      '#': 191
      Name: Sunkern
      Type 1: Grass
      Type 2: null
      Total: 180
      HP: 30.0
      Attack: 30.0
      Defense: 30.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 207
      '#': 192
      Name: Sunflora
      Type 1: Grass
      Type 2: null
      Total: 425
      HP: 75.0
      Attack: 75.0
      Defense: 55.0
      Sp. Atk: 105.0
      Sp. Def: 85.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 208
      '#': 193
      Name: Yanma
      Type 1: Bug
      Type 2: Flying
      Total: 390
      HP: 65.0
      Attack: 65.0
      Defense: 45.0
      Sp. Atk: 75.0
      Sp. Def: 45.0
      Speed: 95
      Generation: 2
      Legendary: false
    - index: 209
      '#': 194
      Name: Wooper
      Type 1: Water
      Type 2: Ground
      Total: 210
      HP: 55.0
      Attack: 45.0
      Defense: 45.0
      Sp. Atk: 25.0
      Sp. Def: 25.0
      Speed: 15
      Generation: 2
      Legendary: false
    - index: 211
      '#': 196
      Name: Espeon
      Type 1: Psychic
      Type 2: null
      Total: 525
      HP: 65.0
      Attack: 65.0
      Defense: 60.0
      Sp. Atk: 130.0
      Sp. Def: 95.0
      Speed: 110
      Generation: 2
      Legendary: false
    - index: 213
      '#': 198
      Name: Murkrow
      Type 1: Dark
      Type 2: Flying
      Total: 405
      HP: 60.0
      Attack: 85.0
      Defense: 42.0
      Sp. Atk: 85.0
      Sp. Def: 42.0
      Speed: 91
      Generation: 2
      Legendary: false
    - index: 215
      '#': 200
      Name: Misdreavus
      Type 1: Ghost
      Type 2: null
      Total: 435
      HP: 60.0
      Attack: 60.0
      Defense: 60.0
      Sp. Atk: 85.0
      Sp. Def: 85.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 216
      '#': 201
      Name: Unown
      Type 1: Psychic
      Type 2: null
      Total: 336
      HP: 48.0
      Attack: 72.0
      Defense: 48.0
      Sp. Atk: 72.0
      Sp. Def: 48.0
      Speed: 48
      Generation: 2
      Legendary: false
    - index: 218
      '#': 203
      Name: Girafarig
      Type 1: Normal
      Type 2: Psychic
      Total: 455
      HP: 70.0
      Attack: 80.0
      Defense: 65.0
      Sp. Atk: 90.0
      Sp. Def: 65.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 219
      '#': 204
      Name: Pineco
      Type 1: Bug
      Type 2: null
      Total: 290
      HP: 50.0
      Attack: 65.0
      Defense: 90.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 15
      Generation: 2
      Legendary: false
    - index: 220
      '#': 205
      Name: Forretress
      Type 1: Bug
      Type 2: Steel
      Total: 465
      HP: 75.0
      Attack: 90.0
      Defense: 140.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 40
      Generation: 2
      Legendary: false
    - index: 222
      '#': 207
      Name: Gligar
      Type 1: Ground
      Type 2: Flying
      Total: 430
      HP: 65.0
      Attack: 75.0
      Defense: 105.0
      Sp. Atk: 35.0
      Sp. Def: 65.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 223
      '#': 208
      Name: Steelix
      Type 1: Steel
      Type 2: Ground
      Total: 510
      HP: 75.0
      Attack: 85.0
      Defense: 200.0
      Sp. Atk: 55.0
      Sp. Def: 65.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 224
      '#': 208
      Name: SteelixMega Steelix
      Type 1: Steel
      Type 2: Ground
      Total: 610
      HP: 75.0
      Attack: 125.0
      Defense: 230.0
      Sp. Atk: 55.0
      Sp. Def: 95.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 225
      '#': 209
      Name: Snubbull
      Type 1: Fairy
      Type 2: null
      Total: 300
      HP: 60.0
      Attack: 80.0
      Defense: 50.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 227
      '#': 211
      Name: Qwilfish
      Type 1: Water
      Type 2: Poison
      Total: 430
      HP: 65.0
      Attack: 95.0
      Defense: 75.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 228
      '#': 212
      Name: Scizor
      Type 1: Bug
      Type 2: Steel
      Total: 500
      HP: 70.0
      Attack: 130.0
      Defense: 100.0
      Sp. Atk: 55.0
      Sp. Def: 80.0
      Speed: 65
      Generation: 2
      Legendary: false
    - index: 229
      '#': 212
      Name: ScizorMega Scizor
      Type 1: Bug
      Type 2: Steel
      Total: 600
      HP: 70.0
      Attack: 150.0
      Defense: 140.0
      Sp. Atk: 65.0
      Sp. Def: 100.0
      Speed: 75
      Generation: 2
      Legendary: false
    - index: 230
      '#': 213
      Name: Shuckle
      Type 1: Bug
      Type 2: Rock
      Total: 505
      HP: 20.0
      Attack: 10.0
      Defense: 230.0
      Sp. Atk: 10.0
      Sp. Def: 230.0
      Speed: 5
      Generation: 2
      Legendary: false
    - index: 231
      '#': 214
      Name: Heracross
      Type 1: Bug
      Type 2: Fighting
      Total: 500
      HP: 80.0
      Attack: 125.0
      Defense: 75.0
      Sp. Atk: 40.0
      Sp. Def: 95.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 232
      '#': 214
      Name: HeracrossMega Heracross
      Type 1: Bug
      Type 2: Fighting
      Total: 600
      HP: 80.0
      Attack: 185.0
      Defense: 115.0
      Sp. Atk: 40.0
      Sp. Def: 105.0
      Speed: 75
      Generation: 2
      Legendary: false
    - index: 233
      '#': 215
      Name: Sneasel
      Type 1: Dark
      Type 2: Ice
      Total: 430
      HP: 55.0
      Attack: 95.0
      Defense: 55.0
      Sp. Atk: 35.0
      Sp. Def: 75.0
      Speed: 115
      Generation: 2
      Legendary: false
    - index: 234
      '#': 216
      Name: Teddiursa
      Type 1: Normal
      Type 2: null
      Total: 330
      HP: 60.0
      Attack: 80.0
      Defense: 50.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 40
      Generation: 2
      Legendary: false
    - index: 236
      '#': 218
      Name: Slugma
      Type 1: Fire
      Type 2: null
      Total: 250
      HP: 40.0
      Attack: 40.0
      Defense: 40.0
      Sp. Atk: 70.0
      Sp. Def: 40.0
      Speed: 20
      Generation: 2
      Legendary: false
    - index: 237
      '#': 219
      Name: Magcargo
      Type 1: Fire
      Type 2: Rock
      Total: 410
      HP: 50.0
      Attack: 50.0
      Defense: 120.0
      Sp. Atk: 80.0
      Sp. Def: 80.0
      Speed: 30
      Generation: 2
      Legendary: false
    - index: 238
      '#': 220
      Name: Swinub
      Type 1: Ice
      Type 2: Ground
      Total: 250
      HP: 50.0
      Attack: 50.0
      Defense: 40.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 50
      Generation: 2
      Legendary: false
    - index: 240
      '#': 222
      Name: Corsola
      Type 1: Water
      Type 2: Rock
      Total: 380
      HP: 55.0
      Attack: 55.0
      Defense: 85.0
      Sp. Atk: 65.0
      Sp. Def: 85.0
      Speed: 35
      Generation: 2
      Legendary: false
    - index: 241
      '#': 223
      Name: Remoraid
      Type 1: Water
      Type 2: null
      Total: 300
      HP: 35.0
      Attack: 65.0
      Defense: 35.0
      Sp. Atk: 65.0
      Sp. Def: 35.0
      Speed: 65
      Generation: 2
      Legendary: false
    - index: 242
      '#': 224
      Name: Octillery
      Type 1: Water
      Type 2: null
      Total: 480
      HP: 75.0
      Attack: 105.0
      Defense: 75.0
      Sp. Atk: 105.0
      Sp. Def: 75.0
      Speed: 45
      Generation: 2
      Legendary: false
    - index: 243
      '#': 225
      Name: Delibird
      Type 1: Ice
      Type 2: Flying
      Total: 330
      HP: 45.0
      Attack: 55.0
      Defense: 45.0
      Sp. Atk: 65.0
      Sp. Def: 45.0
      Speed: 75
      Generation: 2
      Legendary: false
    - index: 244
      '#': 226
      Name: Mantine
      Type 1: Water
      Type 2: Flying
      Total: 465
      HP: 65.0
      Attack: 40.0
      Defense: 70.0
      Sp. Atk: 80.0
      Sp. Def: 140.0
      Speed: 70
      Generation: 2
      Legendary: false
    - index: 245
      '#': 227
      Name: Skarmory
      Type 1: Steel
      Type 2: Flying
      Total: 465
      HP: 65.0
      Attack: 80.0
      Defense: 140.0
      Sp. Atk: 40.0
      Sp. Def: 70.0
      Speed: 70
      Generation: 2
      Legendary: false
    - index: 246
      '#': 228
      Name: Houndour
      Type 1: Dark
      Type 2: Fire
      Total: 330
      HP: 45.0
      Attack: 60.0
      Defense: 30.0
      Sp. Atk: 80.0
      Sp. Def: 50.0
      Speed: 65
      Generation: 2
      Legendary: false
    - index: 247
      '#': 229
      Name: Houndoom
      Type 1: Dark
      Type 2: Fire
      Total: 500
      HP: 75.0
      Attack: 90.0
      Defense: 50.0
      Sp. Atk: 110.0
      Sp. Def: 80.0
      Speed: 95
      Generation: 2
      Legendary: false
    - index: 248
      '#': 229
      Name: HoundoomMega Houndoom
      Type 1: Dark
      Type 2: Fire
      Total: 600
      HP: 75.0
      Attack: 90.0
      Defense: 90.0
      Sp. Atk: 140.0
      Sp. Def: 90.0
      Speed: 115
      Generation: 2
      Legendary: false
    - index: 253
      '#': 234
      Name: Stantler
      Type 1: Normal
      Type 2: null
      Total: 465
      HP: 73.0
      Attack: 95.0
      Defense: 62.0
      Sp. Atk: 85.0
      Sp. Def: 65.0
      Speed: 85
      Generation: 2
      Legendary: false
    - index: 254
      '#': 235
      Name: Smeargle
      Type 1: Normal
      Type 2: null
      Total: 250
      HP: 55.0
      Attack: 20.0
      Defense: 35.0
      Sp. Atk: 20.0
      Sp. Def: 45.0
      Speed: 75
      Generation: 2
      Legendary: false
    - index: 255
      '#': 236
      Name: Tyrogue
      Type 1: Fighting
      Type 2: null
      Total: 210
      HP: 35.0
      Attack: 35.0
      Defense: 35.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 35
      Generation: 2
      Legendary: false
    - index: 256
      '#': 237
      Name: Hitmontop
      Type 1: Fighting
      Type 2: null
      Total: 455
      HP: 50.0
      Attack: 95.0
      Defense: 95.0
      Sp. Atk: 35.0
      Sp. Def: 110.0
      Speed: 70
      Generation: 2
      Legendary: false
    - index: 257
      '#': 238
      Name: Smoochum
      Type 1: Ice
      Type 2: Psychic
      Total: 305
      HP: 45.0
      Attack: 30.0
      Defense: 15.0
      Sp. Atk: 85.0
      Sp. Def: 65.0
      Speed: 65
      Generation: 2
      Legendary: false
    - index: 258
      '#': 239
      Name: Elekid
      Type 1: Electric
      Type 2: null
      Total: 360
      HP: 45.0
      Attack: 63.0
      Defense: 37.0
      Sp. Atk: 65.0
      Sp. Def: 55.0
      Speed: 95
      Generation: 2
      Legendary: false
    - index: 259
      '#': 240
      Name: Magby
      Type 1: Fire
      Type 2: null
      Total: 365
      HP: 45.0
      Attack: 75.0
      Defense: 37.0
      Sp. Atk: 70.0
      Sp. Def: 55.0
      Speed: 83
      Generation: 2
      Legendary: false
    - index: 265
      '#': 246
      Name: Larvitar
      Type 1: Rock
      Type 2: Ground
      Total: 300
      HP: 50.0
      Attack: 64.0
      Defense: 50.0
      Sp. Atk: 45.0
      Sp. Def: 50.0
      Speed: 41
      Generation: 2
      Legendary: false
    - index: 266
      '#': 247
      Name: Pupitar
      Type 1: Rock
      Type 2: Ground
      Total: 410
      HP: 70.0
      Attack: 84.0
      Defense: 70.0
      Sp. Atk: 65.0
      Sp. Def: 70.0
      Speed: 51
      Generation: 2
      Legendary: false
    - index: 272
      '#': 252
      Name: Treecko
      Type 1: Grass
      Type 2: null
      Total: 310
      HP: 40.0
      Attack: 45.0
      Defense: 35.0
      Sp. Atk: 65.0
      Sp. Def: 55.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 273
      '#': 253
      Name: Grovyle
      Type 1: Grass
      Type 2: null
      Total: 405
      HP: 50.0
      Attack: 65.0
      Defense: 45.0
      Sp. Atk: 85.0
      Sp. Def: 65.0
      Speed: 95
      Generation: 3
      Legendary: false
    - index: 274
      '#': 254
      Name: Sceptile
      Type 1: Grass
      Type 2: null
      Total: 530
      HP: 70.0
      Attack: 85.0
      Defense: 65.0
      Sp. Atk: 105.0
      Sp. Def: 85.0
      Speed: 120
      Generation: 3
      Legendary: false
    - index: 276
      '#': 255
      Name: Torchic
      Type 1: Fire
      Type 2: null
      Total: 310
      HP: 45.0
      Attack: 60.0
      Defense: 40.0
      Sp. Atk: 70.0
      Sp. Def: 50.0
      Speed: 45
      Generation: 3
      Legendary: false
    - index: 277
      '#': 256
      Name: Combusken
      Type 1: Fire
      Type 2: Fighting
      Total: 405
      HP: 60.0
      Attack: 85.0
      Defense: 60.0
      Sp. Atk: 85.0
      Sp. Def: 60.0
      Speed: 55
      Generation: 3
      Legendary: false
    - index: 278
      '#': 257
      Name: Blaziken
      Type 1: Fire
      Type 2: Fighting
      Total: 530
      HP: 80.0
      Attack: 120.0
      Defense: 70.0
      Sp. Atk: 110.0
      Sp. Def: 70.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 279
      '#': 257
      Name: BlazikenMega Blaziken
      Type 1: Fire
      Type 2: Fighting
      Total: 630
      HP: 80.0
      Attack: 160.0
      Defense: 80.0
      Sp. Atk: 130.0
      Sp. Def: 80.0
      Speed: 100
      Generation: 3
      Legendary: false
    - index: 280
      '#': 258
      Name: Mudkip
      Type 1: Water
      Type 2: null
      Total: 310
      HP: 50.0
      Attack: 70.0
      Defense: 50.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 281
      '#': 259
      Name: Marshtomp
      Type 1: Water
      Type 2: Ground
      Total: 405
      HP: 70.0
      Attack: 85.0
      Defense: 70.0
      Sp. Atk: 60.0
      Sp. Def: 70.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 284
      '#': 261
      Name: Poochyena
      Type 1: Dark
      Type 2: null
      Total: 220
      HP: 35.0
      Attack: 55.0
      Defense: 35.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 35
      Generation: 3
      Legendary: false
    - index: 285
      '#': 262
      Name: Mightyena
      Type 1: Dark
      Type 2: null
      Total: 420
      HP: 70.0
      Attack: 90.0
      Defense: 70.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 286
      '#': 263
      Name: Zigzagoon
      Type 1: Normal
      Type 2: null
      Total: 240
      HP: 38.0
      Attack: 30.0
      Defense: 41.0
      Sp. Atk: 30.0
      Sp. Def: 41.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 287
      '#': 264
      Name: Linoone
      Type 1: Normal
      Type 2: null
      Total: 420
      HP: 78.0
      Attack: 70.0
      Defense: 61.0
      Sp. Atk: 50.0
      Sp. Def: 61.0
      Speed: 100
      Generation: 3
      Legendary: false
    - index: 288
      '#': 265
      Name: Wurmple
      Type 1: Bug
      Type 2: null
      Total: 195
      HP: 45.0
      Attack: 45.0
      Defense: 35.0
      Sp. Atk: 20.0
      Sp. Def: 30.0
      Speed: 20
      Generation: 3
      Legendary: false
    - index: 289
      '#': 266
      Name: Silcoon
      Type 1: Bug
      Type 2: null
      Total: 205
      HP: 50.0
      Attack: 35.0
      Defense: 55.0
      Sp. Atk: 25.0
      Sp. Def: 25.0
      Speed: 15
      Generation: 3
      Legendary: false
    - index: 290
      '#': 267
      Name: Beautifly
      Type 1: Bug
      Type 2: Flying
      Total: 395
      HP: 60.0
      Attack: 70.0
      Defense: 50.0
      Sp. Atk: 100.0
      Sp. Def: 50.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 291
      '#': 268
      Name: Cascoon
      Type 1: Bug
      Type 2: null
      Total: 205
      HP: 50.0
      Attack: 35.0
      Defense: 55.0
      Sp. Atk: 25.0
      Sp. Def: 25.0
      Speed: 15
      Generation: 3
      Legendary: false
    - index: 292
      '#': 269
      Name: Dustox
      Type 1: Bug
      Type 2: Poison
      Total: 385
      HP: 60.0
      Attack: 50.0
      Defense: 70.0
      Sp. Atk: 50.0
      Sp. Def: 90.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 293
      '#': 270
      Name: Lotad
      Type 1: Water
      Type 2: Grass
      Total: 220
      HP: 40.0
      Attack: 30.0
      Defense: 30.0
      Sp. Atk: 40.0
      Sp. Def: 50.0
      Speed: 30
      Generation: 3
      Legendary: false
    - index: 294
      '#': 271
      Name: Lombre
      Type 1: Water
      Type 2: Grass
      Total: 340
      HP: 60.0
      Attack: 50.0
      Defense: 50.0
      Sp. Atk: 60.0
      Sp. Def: 70.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 295
      '#': 272
      Name: Ludicolo
      Type 1: Water
      Type 2: Grass
      Total: 480
      HP: 80.0
      Attack: 70.0
      Defense: 70.0
      Sp. Atk: 90.0
      Sp. Def: 100.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 296
      '#': 273
      Name: Seedot
      Type 1: Grass
      Type 2: null
      Total: 220
      HP: 40.0
      Attack: 40.0
      Defense: 50.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 30
      Generation: 3
      Legendary: false
    - index: 297
      '#': 274
      Name: Nuzleaf
      Type 1: Grass
      Type 2: Dark
      Total: 340
      HP: 70.0
      Attack: 70.0
      Defense: 40.0
      Sp. Atk: 60.0
      Sp. Def: 40.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 299
      '#': 276
      Name: Taillow
      Type 1: Normal
      Type 2: Flying
      Total: 270
      HP: 40.0
      Attack: 55.0
      Defense: 30.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 85
      Generation: 3
      Legendary: false
    - index: 300
      '#': 277
      Name: Swellow
      Type 1: Normal
      Type 2: Flying
      Total: 430
      HP: 60.0
      Attack: 85.0
      Defense: 60.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 125
      Generation: 3
      Legendary: false
    - index: 301
      '#': 278
      Name: Wingull
      Type 1: Water
      Type 2: Flying
      Total: 270
      HP: 40.0
      Attack: 30.0
      Defense: 30.0
      Sp. Atk: 55.0
      Sp. Def: 30.0
      Speed: 85
      Generation: 3
      Legendary: false
    - index: 302
      '#': 279
      Name: Pelipper
      Type 1: Water
      Type 2: Flying
      Total: 430
      HP: 60.0
      Attack: 50.0
      Defense: 100.0
      Sp. Atk: 85.0
      Sp. Def: 70.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 303
      '#': 280
      Name: Ralts
      Type 1: Psychic
      Type 2: Fairy
      Total: 198
      HP: 28.0
      Attack: 25.0
      Defense: 25.0
      Sp. Atk: 45.0
      Sp. Def: 35.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 304
      '#': 281
      Name: Kirlia
      Type 1: Psychic
      Type 2: Fairy
      Total: 278
      HP: 38.0
      Attack: 35.0
      Defense: 35.0
      Sp. Atk: 65.0
      Sp. Def: 55.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 305
      '#': 282
      Name: Gardevoir
      Type 1: Psychic
      Type 2: Fairy
      Total: 518
      HP: 68.0
      Attack: 65.0
      Defense: 65.0
      Sp. Atk: 125.0
      Sp. Def: 115.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 306
      '#': 282
      Name: GardevoirMega Gardevoir
      Type 1: Psychic
      Type 2: Fairy
      Total: 618
      HP: 68.0
      Attack: 85.0
      Defense: 65.0
      Sp. Atk: 165.0
      Sp. Def: 135.0
      Speed: 100
      Generation: 3
      Legendary: false
    - index: 307
      '#': 283
      Name: Surskit
      Type 1: Bug
      Type 2: Water
      Total: 269
      HP: 40.0
      Attack: 30.0
      Defense: 32.0
      Sp. Atk: 50.0
      Sp. Def: 52.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 308
      '#': 284
      Name: Masquerain
      Type 1: Bug
      Type 2: Flying
      Total: 414
      HP: 70.0
      Attack: 60.0
      Defense: 62.0
      Sp. Atk: 80.0
      Sp. Def: 82.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 309
      '#': 285
      Name: Shroomish
      Type 1: Grass
      Type 2: null
      Total: 295
      HP: 60.0
      Attack: 40.0
      Defense: 60.0
      Sp. Atk: 40.0
      Sp. Def: 60.0
      Speed: 35
      Generation: 3
      Legendary: false
    - index: 310
      '#': 286
      Name: Breloom
      Type 1: Grass
      Type 2: Fighting
      Total: 460
      HP: 60.0
      Attack: 130.0
      Defense: 80.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 311
      '#': 287
      Name: Slakoth
      Type 1: Normal
      Type 2: null
      Total: 280
      HP: 60.0
      Attack: 60.0
      Defense: 60.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 30
      Generation: 3
      Legendary: false
    - index: 312
      '#': 288
      Name: Vigoroth
      Type 1: Normal
      Type 2: null
      Total: 440
      HP: 80.0
      Attack: 80.0
      Defense: 80.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 90
      Generation: 3
      Legendary: false
    - index: 314
      '#': 290
      Name: Nincada
      Type 1: Bug
      Type 2: Ground
      Total: 266
      HP: 31.0
      Attack: 45.0
      Defense: 90.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 315
      '#': 291
      Name: Ninjask
      Type 1: Bug
      Type 2: Flying
      Total: 456
      HP: 61.0
      Attack: 90.0
      Defense: 45.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 160
      Generation: 3
      Legendary: false
    - index: 316
      '#': 292
      Name: Shedinja
      Type 1: Bug
      Type 2: Ghost
      Total: 236
      HP: 1.0
      Attack: 90.0
      Defense: 45.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 317
      '#': 293
      Name: Whismur
      Type 1: Normal
      Type 2: null
      Total: 240
      HP: 64.0
      Attack: 51.0
      Defense: 23.0
      Sp. Atk: 51.0
      Sp. Def: 23.0
      Speed: 28
      Generation: 3
      Legendary: false
    - index: 320
      '#': 296
      Name: Makuhita
      Type 1: Fighting
      Type 2: null
      Total: 237
      HP: 72.0
      Attack: 60.0
      Defense: 30.0
      Sp. Atk: 20.0
      Sp. Def: 30.0
      Speed: 25
      Generation: 3
      Legendary: false
    - index: 322
      '#': 298
      Name: Azurill
      Type 1: Normal
      Type 2: Fairy
      Total: 190
      HP: 50.0
      Attack: 20.0
      Defense: 40.0
      Sp. Atk: 20.0
      Sp. Def: 40.0
      Speed: 20
      Generation: 3
      Legendary: false
    - index: 323
      '#': 299
      Name: Nosepass
      Type 1: Rock
      Type 2: null
      Total: 375
      HP: 30.0
      Attack: 45.0
      Defense: 135.0
      Sp. Atk: 45.0
      Sp. Def: 90.0
      Speed: 30
      Generation: 3
      Legendary: false
    - index: 324
      '#': 300
      Name: Skitty
      Type 1: Normal
      Type 2: null
      Total: 260
      HP: 50.0
      Attack: 45.0
      Defense: 45.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 325
      '#': 301
      Name: Delcatty
      Type 1: Normal
      Type 2: null
      Total: 380
      HP: 70.0
      Attack: 65.0
      Defense: 65.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 326
      '#': 302
      Name: Sableye
      Type 1: Dark
      Type 2: Ghost
      Total: 380
      HP: 50.0
      Attack: 75.0
      Defense: 75.0
      Sp. Atk: 65.0
      Sp. Def: 65.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 327
      '#': 302
      Name: SableyeMega Sableye
      Type 1: Dark
      Type 2: Ghost
      Total: 480
      HP: 50.0
      Attack: 85.0
      Defense: 125.0
      Sp. Atk: 85.0
      Sp. Def: 115.0
      Speed: 20
      Generation: 3
      Legendary: false
    - index: 328
      '#': 303
      Name: Mawile
      Type 1: Steel
      Type 2: Fairy
      Total: 380
      HP: 50.0
      Attack: 85.0
      Defense: 85.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 329
      '#': 303
      Name: MawileMega Mawile
      Type 1: Steel
      Type 2: Fairy
      Total: 480
      HP: 50.0
      Attack: 105.0
      Defense: 125.0
      Sp. Atk: 55.0
      Sp. Def: 95.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 330
      '#': 304
      Name: Aron
      Type 1: Steel
      Type 2: Rock
      Total: 330
      HP: 50.0
      Attack: 70.0
      Defense: 100.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 30
      Generation: 3
      Legendary: false
    - index: 331
      '#': 305
      Name: Lairon
      Type 1: Steel
      Type 2: Rock
      Total: 430
      HP: 60.0
      Attack: 90.0
      Defense: 140.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 332
      '#': 306
      Name: Aggron
      Type 1: Steel
      Type 2: Rock
      Total: 530
      HP: 70.0
      Attack: 110.0
      Defense: 180.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 333
      '#': 306
      Name: AggronMega Aggron
      Type 1: Steel
      Type 2: null
      Total: 630
      HP: 70.0
      Attack: 140.0
      Defense: 230.0
      Sp. Atk: 60.0
      Sp. Def: 80.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 334
      '#': 307
      Name: Meditite
      Type 1: Fighting
      Type 2: Psychic
      Total: 280
      HP: 30.0
      Attack: 40.0
      Defense: 55.0
      Sp. Atk: 40.0
      Sp. Def: 55.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 335
      '#': 308
      Name: Medicham
      Type 1: Fighting
      Type 2: Psychic
      Total: 410
      HP: 60.0
      Attack: 60.0
      Defense: 75.0
      Sp. Atk: 60.0
      Sp. Def: 75.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 336
      '#': 308
      Name: MedichamMega Medicham
      Type 1: Fighting
      Type 2: Psychic
      Total: 510
      HP: 60.0
      Attack: 100.0
      Defense: 85.0
      Sp. Atk: 80.0
      Sp. Def: 85.0
      Speed: 100
      Generation: 3
      Legendary: false
    - index: 337
      '#': 309
      Name: Electrike
      Type 1: Electric
      Type 2: null
      Total: 295
      HP: 40.0
      Attack: 45.0
      Defense: 40.0
      Sp. Atk: 65.0
      Sp. Def: 40.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 338
      '#': 310
      Name: Manectric
      Type 1: Electric
      Type 2: null
      Total: 475
      HP: 70.0
      Attack: 75.0
      Defense: 60.0
      Sp. Atk: 105.0
      Sp. Def: 60.0
      Speed: 105
      Generation: 3
      Legendary: false
    - index: 339
      '#': 310
      Name: ManectricMega Manectric
      Type 1: Electric
      Type 2: null
      Total: 575
      HP: 70.0
      Attack: 75.0
      Defense: 80.0
      Sp. Atk: 135.0
      Sp. Def: 80.0
      Speed: 135
      Generation: 3
      Legendary: false
    - index: 340
      '#': 311
      Name: Plusle
      Type 1: Electric
      Type 2: null
      Total: 405
      HP: 60.0
      Attack: 50.0
      Defense: 40.0
      Sp. Atk: 85.0
      Sp. Def: 75.0
      Speed: 95
      Generation: 3
      Legendary: false
    - index: 341
      '#': 312
      Name: Minun
      Type 1: Electric
      Type 2: null
      Total: 405
      HP: 60.0
      Attack: 40.0
      Defense: 50.0
      Sp. Atk: 75.0
      Sp. Def: 85.0
      Speed: 95
      Generation: 3
      Legendary: false
    - index: 342
      '#': 313
      Name: Volbeat
      Type 1: Bug
      Type 2: null
      Total: 400
      HP: 65.0
      Attack: 73.0
      Defense: 55.0
      Sp. Atk: 47.0
      Sp. Def: 75.0
      Speed: 85
      Generation: 3
      Legendary: false
    - index: 343
      '#': 314
      Name: Illumise
      Type 1: Bug
      Type 2: null
      Total: 400
      HP: 65.0
      Attack: 47.0
      Defense: 55.0
      Sp. Atk: 73.0
      Sp. Def: 75.0
      Speed: 85
      Generation: 3
      Legendary: false
    - index: 344
      '#': 315
      Name: Roselia
      Type 1: Grass
      Type 2: Poison
      Total: 400
      HP: 50.0
      Attack: 60.0
      Defense: 45.0
      Sp. Atk: 100.0
      Sp. Def: 80.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 345
      '#': 316
      Name: Gulpin
      Type 1: Poison
      Type 2: null
      Total: 302
      HP: 70.0
      Attack: 43.0
      Defense: 53.0
      Sp. Atk: 43.0
      Sp. Def: 53.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 347
      '#': 318
      Name: Carvanha
      Type 1: Water
      Type 2: Dark
      Total: 305
      HP: 45.0
      Attack: 90.0
      Defense: 20.0
      Sp. Atk: 65.0
      Sp. Def: 20.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 348
      '#': 319
      Name: Sharpedo
      Type 1: Water
      Type 2: Dark
      Total: 460
      HP: 70.0
      Attack: 120.0
      Defense: 40.0
      Sp. Atk: 95.0
      Sp. Def: 40.0
      Speed: 95
      Generation: 3
      Legendary: false
    - index: 349
      '#': 319
      Name: SharpedoMega Sharpedo
      Type 1: Water
      Type 2: Dark
      Total: 560
      HP: 70.0
      Attack: 140.0
      Defense: 70.0
      Sp. Atk: 110.0
      Sp. Def: 65.0
      Speed: 105
      Generation: 3
      Legendary: false
    - index: 352
      '#': 322
      Name: Numel
      Type 1: Fire
      Type 2: Ground
      Total: 305
      HP: 60.0
      Attack: 60.0
      Defense: 40.0
      Sp. Atk: 65.0
      Sp. Def: 45.0
      Speed: 35
      Generation: 3
      Legendary: false
    - index: 353
      '#': 323
      Name: Camerupt
      Type 1: Fire
      Type 2: Ground
      Total: 460
      HP: 70.0
      Attack: 100.0
      Defense: 70.0
      Sp. Atk: 105.0
      Sp. Def: 75.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 354
      '#': 323
      Name: CameruptMega Camerupt
      Type 1: Fire
      Type 2: Ground
      Total: 560
      HP: 70.0
      Attack: 120.0
      Defense: 100.0
      Sp. Atk: 145.0
      Sp. Def: 105.0
      Speed: 20
      Generation: 3
      Legendary: false
    - index: 355
      '#': 324
      Name: Torkoal
      Type 1: Fire
      Type 2: null
      Total: 470
      HP: 70.0
      Attack: 85.0
      Defense: 140.0
      Sp. Atk: 85.0
      Sp. Def: 70.0
      Speed: 20
      Generation: 3
      Legendary: false
    - index: 356
      '#': 325
      Name: Spoink
      Type 1: Psychic
      Type 2: null
      Total: 330
      HP: 60.0
      Attack: 25.0
      Defense: 35.0
      Sp. Atk: 70.0
      Sp. Def: 80.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 357
      '#': 326
      Name: Grumpig
      Type 1: Psychic
      Type 2: null
      Total: 470
      HP: 80.0
      Attack: 45.0
      Defense: 65.0
      Sp. Atk: 90.0
      Sp. Def: 110.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 358
      '#': 327
      Name: Spinda
      Type 1: Normal
      Type 2: null
      Total: 360
      HP: 60.0
      Attack: 60.0
      Defense: 60.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 359
      '#': 328
      Name: Trapinch
      Type 1: Ground
      Type 2: null
      Total: 290
      HP: 45.0
      Attack: 100.0
      Defense: 45.0
      Sp. Atk: 45.0
      Sp. Def: 45.0
      Speed: 10
      Generation: 3
      Legendary: false
    - index: 362
      '#': 331
      Name: Cacnea
      Type 1: Grass
      Type 2: null
      Total: 335
      HP: 50.0
      Attack: 85.0
      Defense: 40.0
      Sp. Atk: 85.0
      Sp. Def: 40.0
      Speed: 35
      Generation: 3
      Legendary: false
    - index: 363
      '#': 332
      Name: Cacturne
      Type 1: Grass
      Type 2: Dark
      Total: 475
      HP: 70.0
      Attack: 115.0
      Defense: 60.0
      Sp. Atk: 115.0
      Sp. Def: 60.0
      Speed: 55
      Generation: 3
      Legendary: false
    - index: 364
      '#': 333
      Name: Swablu
      Type 1: Normal
      Type 2: Flying
      Total: 310
      HP: 45.0
      Attack: 40.0
      Defense: 60.0
      Sp. Atk: 40.0
      Sp. Def: 75.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 367
      '#': 335
      Name: Zangoose
      Type 1: Normal
      Type 2: null
      Total: 458
      HP: 73.0
      Attack: 115.0
      Defense: 60.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 90
      Generation: 3
      Legendary: false
    - index: 368
      '#': 336
      Name: Seviper
      Type 1: Poison
      Type 2: null
      Total: 458
      HP: 73.0
      Attack: 100.0
      Defense: 60.0
      Sp. Atk: 100.0
      Sp. Def: 60.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 369
      '#': 337
      Name: Lunatone
      Type 1: Rock
      Type 2: Psychic
      Total: 440
      HP: 70.0
      Attack: 55.0
      Defense: 65.0
      Sp. Atk: 95.0
      Sp. Def: 85.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 370
      '#': 338
      Name: Solrock
      Type 1: Rock
      Type 2: Psychic
      Total: 440
      HP: 70.0
      Attack: 95.0
      Defense: 85.0
      Sp. Atk: 55.0
      Sp. Def: 65.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 371
      '#': 339
      Name: Barboach
      Type 1: Water
      Type 2: Ground
      Total: 288
      HP: 50.0
      Attack: 48.0
      Defense: 43.0
      Sp. Atk: 46.0
      Sp. Def: 41.0
      Speed: 60
      Generation: 3
      Legendary: false
    - index: 373
      '#': 341
      Name: Corphish
      Type 1: Water
      Type 2: null
      Total: 308
      HP: 43.0
      Attack: 80.0
      Defense: 65.0
      Sp. Atk: 50.0
      Sp. Def: 35.0
      Speed: 35
      Generation: 3
      Legendary: false
    - index: 374
      '#': 342
      Name: Crawdaunt
      Type 1: Water
      Type 2: Dark
      Total: 468
      HP: 63.0
      Attack: 120.0
      Defense: 85.0
      Sp. Atk: 90.0
      Sp. Def: 55.0
      Speed: 55
      Generation: 3
      Legendary: false
    - index: 375
      '#': 343
      Name: Baltoy
      Type 1: Ground
      Type 2: Psychic
      Total: 300
      HP: 40.0
      Attack: 40.0
      Defense: 55.0
      Sp. Atk: 40.0
      Sp. Def: 70.0
      Speed: 55
      Generation: 3
      Legendary: false
    - index: 376
      '#': 344
      Name: Claydol
      Type 1: Ground
      Type 2: Psychic
      Total: 500
      HP: 60.0
      Attack: 70.0
      Defense: 105.0
      Sp. Atk: 70.0
      Sp. Def: 120.0
      Speed: 75
      Generation: 3
      Legendary: false
    - index: 377
      '#': 345
      Name: Lileep
      Type 1: Rock
      Type 2: Grass
      Total: 355
      HP: 66.0
      Attack: 41.0
      Defense: 77.0
      Sp. Atk: 61.0
      Sp. Def: 87.0
      Speed: 23
      Generation: 3
      Legendary: false
    - index: 379
      '#': 347
      Name: Anorith
      Type 1: Rock
      Type 2: Bug
      Total: 355
      HP: 45.0
      Attack: 95.0
      Defense: 50.0
      Sp. Atk: 40.0
      Sp. Def: 50.0
      Speed: 75
      Generation: 3
      Legendary: false
    - index: 380
      '#': 348
      Name: Armaldo
      Type 1: Rock
      Type 2: Bug
      Total: 495
      HP: 75.0
      Attack: 125.0
      Defense: 100.0
      Sp. Atk: 70.0
      Sp. Def: 80.0
      Speed: 45
      Generation: 3
      Legendary: false
    - index: 381
      '#': 349
      Name: Feebas
      Type 1: Water
      Type 2: null
      Total: 200
      HP: 20.0
      Attack: 15.0
      Defense: 20.0
      Sp. Atk: 10.0
      Sp. Def: 55.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 383
      '#': 351
      Name: Castform
      Type 1: Normal
      Type 2: null
      Total: 420
      HP: 70.0
      Attack: 70.0
      Defense: 70.0
      Sp. Atk: 70.0
      Sp. Def: 70.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 384
      '#': 352
      Name: Kecleon
      Type 1: Normal
      Type 2: null
      Total: 440
      HP: 60.0
      Attack: 90.0
      Defense: 70.0
      Sp. Atk: 60.0
      Sp. Def: 120.0
      Speed: 40
      Generation: 3
      Legendary: false
    - index: 385
      '#': 353
      Name: Shuppet
      Type 1: Ghost
      Type 2: null
      Total: 295
      HP: 44.0
      Attack: 75.0
      Defense: 35.0
      Sp. Atk: 63.0
      Sp. Def: 33.0
      Speed: 45
      Generation: 3
      Legendary: false
    - index: 386
      '#': 354
      Name: Banette
      Type 1: Ghost
      Type 2: null
      Total: 455
      HP: 64.0
      Attack: 115.0
      Defense: 65.0
      Sp. Atk: 83.0
      Sp. Def: 63.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 387
      '#': 354
      Name: BanetteMega Banette
      Type 1: Ghost
      Type 2: null
      Total: 555
      HP: 64.0
      Attack: 165.0
      Defense: 75.0
      Sp. Atk: 93.0
      Sp. Def: 83.0
      Speed: 75
      Generation: 3
      Legendary: false
    - index: 388
      '#': 355
      Name: Duskull
      Type 1: Ghost
      Type 2: null
      Total: 295
      HP: 20.0
      Attack: 40.0
      Defense: 90.0
      Sp. Atk: 30.0
      Sp. Def: 90.0
      Speed: 25
      Generation: 3
      Legendary: false
    - index: 389
      '#': 356
      Name: Dusclops
      Type 1: Ghost
      Type 2: null
      Total: 455
      HP: 40.0
      Attack: 70.0
      Defense: 130.0
      Sp. Atk: 60.0
      Sp. Def: 130.0
      Speed: 25
      Generation: 3
      Legendary: false
    - index: 391
      '#': 358
      Name: Chimecho
      Type 1: Psychic
      Type 2: null
      Total: 425
      HP: 65.0
      Attack: 50.0
      Defense: 70.0
      Sp. Atk: 95.0
      Sp. Def: 80.0
      Speed: 65
      Generation: 3
      Legendary: false
    - index: 392
      '#': 359
      Name: Absol
      Type 1: Dark
      Type 2: null
      Total: 465
      HP: 65.0
      Attack: 130.0
      Defense: 60.0
      Sp. Atk: 75.0
      Sp. Def: 60.0
      Speed: 75
      Generation: 3
      Legendary: false
    - index: 393
      '#': 359
      Name: AbsolMega Absol
      Type 1: Dark
      Type 2: null
      Total: 565
      HP: 65.0
      Attack: 150.0
      Defense: 60.0
      Sp. Atk: 115.0
      Sp. Def: 60.0
      Speed: 115
      Generation: 3
      Legendary: false
    - index: 395
      '#': 361
      Name: Snorunt
      Type 1: Ice
      Type 2: null
      Total: 300
      HP: 50.0
      Attack: 50.0
      Defense: 50.0
      Sp. Atk: 50.0
      Sp. Def: 50.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 396
      '#': 362
      Name: Glalie
      Type 1: Ice
      Type 2: null
      Total: 480
      HP: 80.0
      Attack: 80.0
      Defense: 80.0
      Sp. Atk: 80.0
      Sp. Def: 80.0
      Speed: 80
      Generation: 3
      Legendary: false
    - index: 397
      '#': 362
      Name: GlalieMega Glalie
      Type 1: Ice
      Type 2: null
      Total: 580
      HP: 80.0
      Attack: 120.0
      Defense: 80.0
      Sp. Atk: 120.0
      Sp. Def: 80.0
      Speed: 100
      Generation: 3
      Legendary: false
    - index: 398
      '#': 363
      Name: Spheal
      Type 1: Ice
      Type 2: Water
      Total: 290
      HP: 70.0
      Attack: 40.0
      Defense: 50.0
      Sp. Atk: 55.0
      Sp. Def: 50.0
      Speed: 25
      Generation: 3
      Legendary: false
    - index: 401
      '#': 366
      Name: Clamperl
      Type 1: Water
      Type 2: null
      Total: 345
      HP: 35.0
      Attack: 64.0
      Defense: 85.0
      Sp. Atk: 74.0
      Sp. Def: 55.0
      Speed: 32
      Generation: 3
      Legendary: false
    - index: 402
      '#': 367
      Name: Huntail
      Type 1: Water
      Type 2: null
      Total: 485
      HP: 55.0
      Attack: 104.0
      Defense: 105.0
      Sp. Atk: 94.0
      Sp. Def: 75.0
      Speed: 52
      Generation: 3
      Legendary: false
    - index: 403
      '#': 368
      Name: Gorebyss
      Type 1: Water
      Type 2: null
      Total: 485
      HP: 55.0
      Attack: 84.0
      Defense: 105.0
      Sp. Atk: 114.0
      Sp. Def: 75.0
      Speed: 52
      Generation: 3
      Legendary: false
    - index: 405
      '#': 370
      Name: Luvdisc
      Type 1: Water
      Type 2: null
      Total: 330
      HP: 43.0
      Attack: 30.0
      Defense: 55.0
      Sp. Atk: 40.0
      Sp. Def: 65.0
      Speed: 97
      Generation: 3
      Legendary: false
    - index: 410
      '#': 374
      Name: Beldum
      Type 1: Steel
      Type 2: Psychic
      Total: 300
      HP: 40.0
      Attack: 55.0
      Defense: 80.0
      Sp. Atk: 35.0
      Sp. Def: 60.0
      Speed: 30
      Generation: 3
      Legendary: false
    - index: 411
      '#': 375
      Name: Metang
      Type 1: Steel
      Type 2: Psychic
      Total: 420
      HP: 60.0
      Attack: 75.0
      Defense: 100.0
      Sp. Atk: 55.0
      Sp. Def: 80.0
      Speed: 50
      Generation: 3
      Legendary: false
    - index: 412
      '#': 376
      Name: Metagross
      Type 1: Steel
      Type 2: Psychic
      Total: 600
      HP: 80.0
      Attack: 135.0
      Defense: 130.0
      Sp. Atk: 95.0
      Sp. Def: 90.0
      Speed: 70
      Generation: 3
      Legendary: false
    - index: 413
      '#': 376
      Name: MetagrossMega Metagross
      Type 1: Steel
      Type 2: Psychic
      Total: 700
      HP: 80.0
      Attack: 145.0
      Defense: 150.0
      Sp. Atk: 105.0
      Sp. Def: 110.0
      Speed: 110
      Generation: 3
      Legendary: false
    - index: 414
      '#': 377
      Name: Regirock
      Type 1: Rock
      Type 2: null
      Total: 580
      HP: 80.0
      Attack: 100.0
      Defense: 200.0
      Sp. Atk: 50.0
      Sp. Def: 100.0
      Speed: 50
      Generation: 3
      Legendary: true
    - index: 415
      '#': 378
      Name: Regice
      Type 1: Ice
      Type 2: null
      Total: 580
      HP: 80.0
      Attack: 50.0
      Defense: 100.0
      Sp. Atk: 100.0
      Sp. Def: 200.0
      Speed: 50
      Generation: 3
      Legendary: true
    - index: 416
      '#': 379
      Name: Registeel
      Type 1: Steel
      Type 2: null
      Total: 580
      HP: 80.0
      Attack: 75.0
      Defense: 150.0
      Sp. Atk: 75.0
      Sp. Def: 150.0
      Speed: 50
      Generation: 3
      Legendary: true
    - index: 428
      '#': 386
      Name: DeoxysNormal Forme
      Type 1: Psychic
      Type 2: null
      Total: 600
      HP: 50.0
      Attack: 150.0
      Defense: 50.0
      Sp. Atk: 150.0
      Sp. Def: 50.0
      Speed: 150
      Generation: 3
      Legendary: true
    - index: 429
      '#': 386
      Name: DeoxysAttack Forme
      Type 1: Psychic
      Type 2: null
      Total: 600
      HP: 50.0
      Attack: 180.0
      Defense: 20.0
      Sp. Atk: 180.0
      Sp. Def: 20.0
      Speed: 150
      Generation: 3
      Legendary: true
    - index: 430
      '#': 386
      Name: DeoxysDefense Forme
      Type 1: Psychic
      Type 2: null
      Total: 600
      HP: 50.0
      Attack: 70.0
      Defense: 160.0
      Sp. Atk: 70.0
      Sp. Def: 160.0
      Speed: 90
      Generation: 3
      Legendary: true
    - index: 431
      '#': 386
      Name: DeoxysSpeed Forme
      Type 1: Psychic
      Type 2: null
      Total: 600
      HP: 50.0
      Attack: 95.0
      Defense: 90.0
      Sp. Atk: 95.0
      Sp. Def: 90.0
      Speed: 180
      Generation: 3
      Legendary: true
    - index: 432
      '#': 387
      Name: Turtwig
      Type 1: Grass
      Type 2: null
      Total: 318
      HP: 55.0
      Attack: 68.0
      Defense: 64.0
      Sp. Atk: 45.0
      Sp. Def: 55.0
      Speed: 31
      Generation: 4
      Legendary: false
    - index: 433
      '#': 388
      Name: Grotle
      Type 1: Grass
      Type 2: null
      Total: 405
      HP: 75.0
      Attack: 89.0
      Defense: 85.0
      Sp. Atk: 55.0
      Sp. Def: 65.0
      Speed: 36
      Generation: 4
      Legendary: false
    - index: 435
      '#': 390
      Name: Chimchar
      Type 1: Fire
      Type 2: null
      Total: 309
      HP: 44.0
      Attack: 58.0
      Defense: 44.0
      Sp. Atk: 58.0
      Sp. Def: 44.0
      Speed: 61
      Generation: 4
      Legendary: false
    - index: 436
      '#': 391
      Name: Monferno
      Type 1: Fire
      Type 2: Fighting
      Total: 405
      HP: 64.0
      Attack: 78.0
      Defense: 52.0
      Sp. Atk: 78.0
      Sp. Def: 52.0
      Speed: 81
      Generation: 4
      Legendary: false
    - index: 437
      '#': 392
      Name: Infernape
      Type 1: Fire
      Type 2: Fighting
      Total: 534
      HP: 76.0
      Attack: 104.0
      Defense: 71.0
      Sp. Atk: 104.0
      Sp. Def: 71.0
      Speed: 108
      Generation: 4
      Legendary: false
    - index: 438
      '#': 393
      Name: Piplup
      Type 1: Water
      Type 2: null
      Total: 314
      HP: 53.0
      Attack: 51.0
      Defense: 53.0
      Sp. Atk: 61.0
      Sp. Def: 56.0
      Speed: 40
      Generation: 4
      Legendary: false
    - index: 439
      '#': 394
      Name: Prinplup
      Type 1: Water
      Type 2: null
      Total: 405
      HP: 64.0
      Attack: 66.0
      Defense: 68.0
      Sp. Atk: 81.0
      Sp. Def: 76.0
      Speed: 50
      Generation: 4
      Legendary: false
    - index: 441
      '#': 396
      Name: Starly
      Type 1: Normal
      Type 2: Flying
      Total: 245
      HP: 40.0
      Attack: 55.0
      Defense: 30.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 60
      Generation: 4
      Legendary: false
    - index: 442
      '#': 397
      Name: Staravia
      Type 1: Normal
      Type 2: Flying
      Total: 340
      HP: 55.0
      Attack: 75.0
      Defense: 50.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 80
      Generation: 4
      Legendary: false
    - index: 444
      '#': 399
      Name: Bidoof
      Type 1: Normal
      Type 2: null
      Total: 250
      HP: 59.0
      Attack: 45.0
      Defense: 40.0
      Sp. Atk: 35.0
      Sp. Def: 40.0
      Speed: 31
      Generation: 4
      Legendary: false
    - index: 445
      '#': 400
      Name: Bibarel
      Type 1: Normal
      Type 2: Water
      Total: 410
      HP: 79.0
      Attack: 85.0
      Defense: 60.0
      Sp. Atk: 55.0
      Sp. Def: 60.0
      Speed: 71
      Generation: 4
      Legendary: false
    - index: 446
      '#': 401
      Name: Kricketot
      Type 1: Bug
      Type 2: null
      Total: 194
      HP: 37.0
      Attack: 25.0
      Defense: 41.0
      Sp. Atk: 25.0
      Sp. Def: 41.0
      Speed: 25
      Generation: 4
      Legendary: false
    - index: 447
      '#': 402
      Name: Kricketune
      Type 1: Bug
      Type 2: null
      Total: 384
      HP: 77.0
      Attack: 85.0
      Defense: 51.0
      Sp. Atk: 55.0
      Sp. Def: 51.0
      Speed: 65
      Generation: 4
      Legendary: false
    - index: 448
      '#': 403
      Name: Shinx
      Type 1: Electric
      Type 2: null
      Total: 263
      HP: 45.0
      Attack: 65.0
      Defense: 34.0
      Sp. Atk: 40.0
      Sp. Def: 34.0
      Speed: 45
      Generation: 4
      Legendary: false
    - index: 449
      '#': 404
      Name: Luxio
      Type 1: Electric
      Type 2: null
      Total: 363
      HP: 60.0
      Attack: 85.0
      Defense: 49.0
      Sp. Atk: 60.0
      Sp. Def: 49.0
      Speed: 60
      Generation: 4
      Legendary: false
    - index: 450
      '#': 405
      Name: Luxray
      Type 1: Electric
      Type 2: null
      Total: 523
      HP: 80.0
      Attack: 120.0
      Defense: 79.0
      Sp. Atk: 95.0
      Sp. Def: 79.0
      Speed: 70
      Generation: 4
      Legendary: false
    - index: 451
      '#': 406
      Name: Budew
      Type 1: Grass
      Type 2: Poison
      Total: 280
      HP: 40.0
      Attack: 30.0
      Defense: 35.0
      Sp. Atk: 50.0
      Sp. Def: 70.0
      Speed: 55
      Generation: 4
      Legendary: false
    - index: 452
      '#': 407
      Name: Roserade
      Type 1: Grass
      Type 2: Poison
      Total: 515
      HP: 60.0
      Attack: 70.0
      Defense: 65.0
      Sp. Atk: 125.0
      Sp. Def: 105.0
      Speed: 90
      Generation: 4
      Legendary: false
    - index: 453
      '#': 408
      Name: Cranidos
      Type 1: Rock
      Type 2: null
      Total: 350
      HP: 67.0
      Attack: 125.0
      Defense: 40.0
      Sp. Atk: 30.0
      Sp. Def: 30.0
      Speed: 58
      Generation: 4
      Legendary: false
    - index: 455
      '#': 410
      Name: Shieldon
      Type 1: Rock
      Type 2: Steel
      Total: 350
      HP: 30.0
      Attack: 42.0
      Defense: 118.0
      Sp. Atk: 42.0
      Sp. Def: 88.0
      Speed: 30
      Generation: 4
      Legendary: false
    - index: 456
      '#': 411
      Name: Bastiodon
      Type 1: Rock
      Type 2: Steel
      Total: 495
      HP: 60.0
      Attack: 52.0
      Defense: 168.0
      Sp. Atk: 47.0
      Sp. Def: 138.0
      Speed: 30
      Generation: 4
      Legendary: false
    - index: 457
      '#': 412
      Name: Burmy
      Type 1: Bug
      Type 2: null
      Total: 224
      HP: 40.0
      Attack: 29.0
      Defense: 45.0
      Sp. Atk: 29.0
      Sp. Def: 45.0
      Speed: 36
      Generation: 4
      Legendary: false
    - index: 458
      '#': 413
      Name: WormadamPlant Cloak
      Type 1: Bug
      Type 2: Grass
      Total: 424
      HP: 60.0
      Attack: 59.0
      Defense: 85.0
      Sp. Atk: 79.0
      Sp. Def: 105.0
      Speed: 36
      Generation: 4
      Legendary: false
    - index: 459
      '#': 413
      Name: WormadamSandy Cloak
      Type 1: Bug
      Type 2: Ground
      Total: 424
      HP: 60.0
      Attack: 79.0
      Defense: 105.0
      Sp. Atk: 59.0
      Sp. Def: 85.0
      Speed: 36
      Generation: 4
      Legendary: false
    - index: 460
      '#': 413
      Name: WormadamTrash Cloak
      Type 1: Bug
      Type 2: Steel
      Total: 424
      HP: 60.0
      Attack: 69.0
      Defense: 95.0
      Sp. Atk: 69.0
      Sp. Def: 95.0
      Speed: 36
      Generation: 4
      Legendary: false
    - index: 461
      '#': 414
      Name: Mothim
      Type 1: Bug
      Type 2: Flying
      Total: 424
      HP: 70.0
      Attack: 94.0
      Defense: 50.0
      Sp. Atk: 94.0
      Sp. Def: 50.0
      Speed: 66
      Generation: 4
      Legendary: false
    - index: 462
      '#': 415
      Name: Combee
      Type 1: Bug
      Type 2: Flying
      Total: 244
      HP: 30.0
      Attack: 30.0
      Defense: 42.0
      Sp. Atk: 30.0
      Sp. Def: 42.0
      Speed: 70
      Generation: 4
      Legendary: false
    - index: 463
      '#': 416
      Name: Vespiquen
      Type 1: Bug
      Type 2: Flying
      Total: 474
      HP: 70.0
      Attack: 80.0
      Defense: 102.0
      Sp. Atk: 80.0
      Sp. Def: 102.0
      Speed: 40
      Generation: 4
      Legendary: false
    - index: 464
      '#': 417
      Name: Pachirisu
      Type 1: Electric
      Type 2: null
      Total: 405
      HP: 60.0
      Attack: 45.0
      Defense: 70.0
      Sp. Atk: 45.0
      Sp. Def: 90.0
      Speed: 95
      Generation: 4
      Legendary: false
    - index: 465
      '#': 418
      Name: Buizel
      Type 1: Water
      Type 2: null
      Total: 330
      HP: 55.0
      Attack: 65.0
      Defense: 35.0
      Sp. Atk: 60.0
      Sp. Def: 30.0
      Speed: 85
      Generation: 4
      Legendary: false
    - index: 467
      '#': 420
      Name: Cherubi
      Type 1: Grass
      Type 2: null
      Total: 275
      HP: 45.0
      Attack: 35.0
      Defense: 45.0
      Sp. Atk: 62.0
      Sp. Def: 53.0
      Speed: 35
      Generation: 4
      Legendary: false
    - index: 468
      '#': 421
      Name: Cherrim
      Type 1: Grass
      Type 2: null
      Total: 450
      HP: 70.0
      Attack: 60.0
      Defense: 70.0
      Sp. Atk: 87.0
      Sp. Def: 78.0
      Speed: 85
      Generation: 4
      Legendary: false
    - index: 469
      '#': 422
      Name: Shellos
      Type 1: Water
      Type 2: null
      Total: 325
      HP: 76.0
      Attack: 48.0
      Defense: 48.0
      Sp. Atk: 57.0
      Sp. Def: 62.0
      Speed: 34
      Generation: 4
      Legendary: false
    - index: 471
      '#': 424
      Name: Ambipom
      Type 1: Normal
      Type 2: null
      Total: 482
      HP: 75.0
      Attack: 100.0
      Defense: 66.0
      Sp. Atk: 60.0
      Sp. Def: 66.0
      Speed: 115
      Generation: 4
      Legendary: false
    - index: 474
      '#': 427
      Name: Buneary
      Type 1: Normal
      Type 2: null
      Total: 350
      HP: 55.0
      Attack: 66.0
      Defense: 44.0
      Sp. Atk: 44.0
      Sp. Def: 56.0
      Speed: 85
      Generation: 4
      Legendary: false
    - index: 475
      '#': 428
      Name: Lopunny
      Type 1: Normal
      Type 2: null
      Total: 480
      HP: 65.0
      Attack: 76.0
      Defense: 84.0
      Sp. Atk: 54.0
      Sp. Def: 96.0
      Speed: 105
      Generation: 4
      Legendary: false
    - index: 476
      '#': 428
      Name: LopunnyMega Lopunny
      Type 1: Normal
      Type 2: Fighting
      Total: 580
      HP: 65.0
      Attack: 136.0
      Defense: 94.0
      Sp. Atk: 54.0
      Sp. Def: 96.0
      Speed: 135
      Generation: 4
      Legendary: false
    - index: 477
      '#': 429
      Name: Mismagius
      Type 1: Ghost
      Type 2: null
      Total: 495
      HP: 60.0
      Attack: 60.0
      Defense: 60.0
      Sp. Atk: 105.0
      Sp. Def: 105.0
      Speed: 105
      Generation: 4
      Legendary: false
    - index: 479
      '#': 431
      Name: Glameow
      Type 1: Normal
      Type 2: null
      Total: 310
      HP: 49.0
      Attack: 55.0
      Defense: 42.0
      Sp. Atk: 42.0
      Sp. Def: 37.0
      Speed: 85
      Generation: 4
      Legendary: false
    - index: 480
      '#': 432
      Name: Purugly
      Type 1: Normal
      Type 2: null
      Total: 452
      HP: 71.0
      Attack: 82.0
      Defense: 64.0
      Sp. Atk: 64.0
      Sp. Def: 59.0
      Speed: 112
      Generation: 4
      Legendary: false
    - index: 481
      '#': 433
      Name: Chingling
      Type 1: Psychic
      Type 2: null
      Total: 285
      HP: 45.0
      Attack: 30.0
      Defense: 50.0
      Sp. Atk: 65.0
      Sp. Def: 50.0
      Speed: 45
      Generation: 4
      Legendary: false
    - index: 482
      '#': 434
      Name: Stunky
      Type 1: Poison
      Type 2: Dark
      Total: 329
      HP: 63.0
      Attack: 63.0
      Defense: 47.0
      Sp. Atk: 41.0
      Sp. Def: 41.0
      Speed: 74
      Generation: 4
      Legendary: false
    - index: 484
      '#': 436
      Name: Bronzor
      Type 1: Steel
      Type 2: Psychic
      Total: 300
      HP: 57.0
      Attack: 24.0
      Defense: 86.0
      Sp. Atk: 24.0
      Sp. Def: 86.0
      Speed: 23
      Generation: 4
      Legendary: false
    - index: 485
      '#': 437
      Name: Bronzong
      Type 1: Steel
      Type 2: Psychic
      Total: 500
      HP: 67.0
      Attack: 89.0
      Defense: 116.0
      Sp. Atk: 79.0
      Sp. Def: 116.0
      Speed: 33
      Generation: 4
      Legendary: false
    - index: 486
      '#': 438
      Name: Bonsly
      Type 1: Rock
      Type 2: null
      Total: 290
      HP: 50.0
      Attack: 80.0
      Defense: 95.0
      Sp. Atk: 10.0
      Sp. Def: 45.0
      Speed: 10
      Generation: 4
      Legendary: false
    - index: 487
      '#': 439
      Name: Mime Jr.
      Type 1: Psychic
      Type 2: Fairy
      Total: 310
      HP: 20.0
      Attack: 25.0
      Defense: 45.0
      Sp. Atk: 70.0
      Sp. Def: 90.0
      Speed: 60
      Generation: 4
      Legendary: false
    - index: 489
      '#': 441
      Name: Chatot
      Type 1: Normal
      Type 2: Flying
      Total: 411
      HP: 76.0
      Attack: 65.0
      Defense: 45.0
      Sp. Atk: 92.0
      Sp. Def: 42.0
      Speed: 91
      Generation: 4
      Legendary: false
    - index: 490
      '#': 442
      Name: Spiritomb
      Type 1: Ghost
      Type 2: Dark
      Total: 485
      HP: 50.0
      Attack: 92.0
      Defense: 108.0
      Sp. Atk: 92.0
      Sp. Def: 108.0
      Speed: 35
      Generation: 4
      Legendary: false
    - index: 496
      '#': 447
      Name: Riolu
      Type 1: Fighting
      Type 2: null
      Total: 285
      HP: 40.0
      Attack: 70.0
      Defense: 40.0
      Sp. Atk: 35.0
      Sp. Def: 40.0
      Speed: 60
      Generation: 4
      Legendary: false
    - index: 497
      '#': 448
      Name: Lucario
      Type 1: Fighting
      Type 2: Steel
      Total: 525
      HP: 70.0
      Attack: 110.0
      Defense: 70.0
      Sp. Atk: 115.0
      Sp. Def: 70.0
      Speed: 90
      Generation: 4
      Legendary: false
    - index: 498
      '#': 448
      Name: LucarioMega Lucario
      Type 1: Fighting
      Type 2: Steel
      Total: 625
      HP: 70.0
      Attack: 145.0
      Defense: 88.0
      Sp. Atk: 140.0
      Sp. Def: 70.0
      Speed: 112
      Generation: 4
      Legendary: false
    - index: 499
      '#': 449
      Name: Hippopotas
      Type 1: Ground
      Type 2: null
      Total: 330
      HP: 68.0
      Attack: 72.0
      Defense: 78.0
      Sp. Atk: 38.0
      Sp. Def: 42.0
      Speed: 32
      Generation: 4
      Legendary: false
    - index: 501
      '#': 451
      Name: Skorupi
      Type 1: Poison
      Type 2: Bug
      Total: 330
      HP: 40.0
      Attack: 50.0
      Defense: 90.0
      Sp. Atk: 30.0
      Sp. Def: 55.0
      Speed: 65
      Generation: 4
      Legendary: false
    - index: 502
      '#': 452
      Name: Drapion
      Type 1: Poison
      Type 2: Dark
      Total: 500
      HP: 70.0
      Attack: 90.0
      Defense: 110.0
      Sp. Atk: 60.0
      Sp. Def: 75.0
      Speed: 95
      Generation: 4
      Legendary: false
    - index: 503
      '#': 453
      Name: Croagunk
      Type 1: Poison
      Type 2: Fighting
      Total: 300
      HP: 48.0
      Attack: 61.0
      Defense: 40.0
      Sp. Atk: 61.0
      Sp. Def: 40.0
      Speed: 50
      Generation: 4
      Legendary: false
    - index: 505
      '#': 455
      Name: Carnivine
      Type 1: Grass
      Type 2: null
      Total: 454
      HP: 74.0
      Attack: 100.0
      Defense: 72.0
      Sp. Atk: 90.0
      Sp. Def: 72.0
      Speed: 46
      Generation: 4
      Legendary: false
    - index: 506
      '#': 456
      Name: Finneon
      Type 1: Water
      Type 2: null
      Total: 330
      HP: 49.0
      Attack: 49.0
      Defense: 56.0
      Sp. Atk: 49.0
      Sp. Def: 61.0
      Speed: 66
      Generation: 4
      Legendary: false
    - index: 507
      '#': 457
      Name: Lumineon
      Type 1: Water
      Type 2: null
      Total: 460
      HP: 69.0
      Attack: 69.0
      Defense: 76.0
      Sp. Atk: 69.0
      Sp. Def: 86.0
      Speed: 91
      Generation: 4
      Legendary: false
    - index: 508
      '#': 458
      Name: Mantyke
      Type 1: Water
      Type 2: Flying
      Total: 345
      HP: 45.0
      Attack: 20.0
      Defense: 50.0
      Sp. Atk: 60.0
      Sp. Def: 120.0
      Speed: 50
      Generation: 4
      Legendary: false
    - index: 509
      '#': 459
      Name: Snover
      Type 1: Grass
      Type 2: Ice
      Total: 334
      HP: 60.0
      Attack: 62.0
      Defense: 50.0
      Sp. Atk: 62.0
      Sp. Def: 60.0
      Speed: 40
      Generation: 4
      Legendary: false
    - index: 512
      '#': 461
      Name: Weavile
      Type 1: Dark
      Type 2: Ice
      Total: 510
      HP: 70.0
      Attack: 120.0
      Defense: 65.0
      Sp. Atk: 45.0
      Sp. Def: 85.0
      Speed: 125
      Generation: 4
      Legendary: false
    - index: 513
      '#': 462
      Name: Magnezone
      Type 1: Electric
      Type 2: Steel
      Total: 535
      HP: 70.0
      Attack: 70.0
      Defense: 115.0
      Sp. Atk: 130.0
      Sp. Def: 90.0
      Speed: 60
      Generation: 4
      Legendary: false
    - index: 517
      '#': 466
      Name: Electivire
      Type 1: Electric
      Type 2: null
      Total: 540
      HP: 75.0
      Attack: 123.0
      Defense: 67.0
      Sp. Atk: 95.0
      Sp. Def: 85.0
      Speed: 95
      Generation: 4
      Legendary: false
    - index: 518
      '#': 467
      Name: Magmortar
      Type 1: Fire
      Type 2: null
      Total: 540
      HP: 75.0
      Attack: 95.0
      Defense: 67.0
      Sp. Atk: 125.0
      Sp. Def: 95.0
      Speed: 83
      Generation: 4
      Legendary: false
    - index: 521
      '#': 470
      Name: Leafeon
      Type 1: Grass
      Type 2: null
      Total: 525
      HP: 65.0
      Attack: 110.0
      Defense: 130.0
      Sp. Atk: 60.0
      Sp. Def: 65.0
      Speed: 95
      Generation: 4
      Legendary: false
    - index: 522
      '#': 471
      Name: Glaceon
      Type 1: Ice
      Type 2: null
      Total: 525
      HP: 65.0
      Attack: 60.0
      Defense: 110.0
      Sp. Atk: 130.0
      Sp. Def: 95.0
      Speed: 65
      Generation: 4
      Legendary: false
    - index: 523
      '#': 472
      Name: Gliscor
      Type 1: Ground
      Type 2: Flying
      Total: 510
      HP: 75.0
      Attack: 95.0
      Defense: 125.0
      Sp. Atk: 45.0
      Sp. Def: 75.0
      Speed: 95
      Generation: 4
      Legendary: false
    - index: 526
      '#': 475
      Name: Gallade
      Type 1: Psychic
      Type 2: Fighting
      Total: 518
      HP: 68.0
      Attack: 125.0
      Defense: 65.0
      Sp. Atk: 65.0
      Sp. Def: 115.0
      Speed: 80
      Generation: 4
      Legendary: false
    - index: 527
      '#': 475
      Name: GalladeMega Gallade
      Type 1: Psychic
      Type 2: Fighting
      Total: 618
      HP: 68.0
      Attack: 165.0
      Defense: 95.0
      Sp. Atk: 65.0
      Sp. Def: 115.0
      Speed: 110
      Generation: 4
      Legendary: false
    - index: 528
      '#': 476
      Name: Probopass
      Type 1: Rock
      Type 2: Steel
      Total: 525
      HP: 60.0
      Attack: 55.0
      Defense: 145.0
      Sp. Atk: 75.0
      Sp. Def: 150.0
      Speed: 40
      Generation: 4
      Legendary: false
    - index: 529
      '#': 477
      Name: Dusknoir
      Type 1: Ghost
      Type 2: null
      Total: 525
      HP: 45.0
      Attack: 100.0
      Defense: 135.0
      Sp. Atk: 65.0
      Sp. Def: 135.0
      Speed: 45
      Generation: 4
      Legendary: false
    - index: 530
      '#': 478
      Name: Froslass
      Type 1: Ice
      Type 2: Ghost
      Total: 480
      HP: 70.0
      Attack: 80.0
      Defense: 70.0
      Sp. Atk: 80.0
      Sp. Def: 70.0
      Speed: 110
      Generation: 4
      Legendary: false
    - index: 531
      '#': 479
      Name: Rotom
      Type 1: Electric
      Type 2: Ghost
      Total: 440
      HP: 50.0
      Attack: 50.0
      Defense: 77.0
      Sp. Atk: 95.0
      Sp. Def: 77.0
      Speed: 91
      Generation: 4
      Legendary: false
    - index: 532
      '#': 479
      Name: RotomHeat Rotom
      Type 1: Electric
      Type 2: Fire
      Total: 520
      HP: 50.0
      Attack: 65.0
      Defense: 107.0
      Sp. Atk: 105.0
      Sp. Def: 107.0
      Speed: 86
      Generation: 4
      Legendary: false
    - index: 533
      '#': 479
      Name: RotomWash Rotom
      Type 1: Electric
      Type 2: Water
      Total: 520
      HP: 50.0
      Attack: 65.0
      Defense: 107.0
      Sp. Atk: 105.0
      Sp. Def: 107.0
      Speed: 86
      Generation: 4
      Legendary: false
    - index: 534
      '#': 479
      Name: RotomFrost Rotom
      Type 1: Electric
      Type 2: Ice
      Total: 520
      HP: 50.0
      Attack: 65.0
      Defense: 107.0
      Sp. Atk: 105.0
      Sp. Def: 107.0
      Speed: 86
      Generation: 4
      Legendary: false
    - index: 535
      '#': 479
      Name: RotomFan Rotom
      Type 1: Electric
      Type 2: Flying
      Total: 520
      HP: 50.0
      Attack: 65.0
      Defense: 107.0
      Sp. Atk: 105.0
      Sp. Def: 107.0
      Speed: 86
      Generation: 4
      Legendary: false
    - index: 536
      '#': 479
      Name: RotomMow Rotom
      Type 1: Electric
      Type 2: Grass
      Total: 520
      HP: 50.0
      Attack: 65.0
      Defense: 107.0
      Sp. Atk: 105.0
      Sp. Def: 107.0
      Speed: 86
      Generation: 4
      Legendary: false
    - index: 537
      '#': 480
      Name: Uxie
      Type 1: Psychic
      Type 2: null
      Total: 580
      HP: 75.0
      Attack: 75.0
      Defense: 130.0
      Sp. Atk: 75.0
      Sp. Def: 130.0
      Speed: 95
      Generation: 4
      Legendary: true
    - index: 538
      '#': 481
      Name: Mesprit
      Type 1: Psychic
      Type 2: null
      Total: 580
      HP: 80.0
      Attack: 105.0
      Defense: 105.0
      Sp. Atk: 105.0
      Sp. Def: 105.0
      Speed: 80
      Generation: 4
      Legendary: true
    - index: 539
      '#': 482
      Name: Azelf
      Type 1: Psychic
      Type 2: null
      Total: 580
      HP: 75.0
      Attack: 125.0
      Defense: 70.0
      Sp. Atk: 125.0
      Sp. Def: 70.0
      Speed: 115
      Generation: 4
      Legendary: true
    - index: 547
      '#': 489
      Name: Phione
      Type 1: Water
      Type 2: null
      Total: 480
      HP: 80.0
      Attack: 80.0
      Defense: 80.0
      Sp. Atk: 80.0
      Sp. Def: 80.0
      Speed: 80
      Generation: 4
      Legendary: false
    - index: 549
      '#': 491
      Name: Darkrai
      Type 1: Dark
      Type 2: null
      Total: 600
      HP: 70.0
      Attack: 90.0
      Defense: 90.0
      Sp. Atk: 135.0
      Sp. Def: 90.0
      Speed: 125
      Generation: 4
      Legendary: true
    - index: 554
      '#': 495
      Name: Snivy
      Type 1: Grass
      Type 2: null
      Total: 308
      HP: 45.0
      Attack: 45.0
      Defense: 55.0
      Sp. Atk: 45.0
      Sp. Def: 55.0
      Speed: 63
      Generation: 5
      Legendary: false
    - index: 555
      '#': 496
      Name: Servine
      Type 1: Grass
      Type 2: null
      Total: 413
      HP: 60.0
      Attack: 60.0
      Defense: 75.0
      Sp. Atk: 60.0
      Sp. Def: 75.0
      Speed: 83
      Generation: 5
      Legendary: false
    - index: 556
      '#': 497
      Name: Serperior
      Type 1: Grass
      Type 2: null
      Total: 528
      HP: 75.0
      Attack: 75.0
      Defense: 95.0
      Sp. Atk: 75.0
      Sp. Def: 95.0
      Speed: 113
      Generation: 5
      Legendary: false
    - index: 557
      '#': 498
      Name: Tepig
      Type 1: Fire
      Type 2: null
      Total: 308
      HP: 65.0
      Attack: 63.0
      Defense: 45.0
      Sp. Atk: 45.0
      Sp. Def: 45.0
      Speed: 45
      Generation: 5
      Legendary: false
    - index: 560
      '#': 501
      Name: Oshawott
      Type 1: Water
      Type 2: null
      Total: 308
      HP: 55.0
      Attack: 55.0
      Defense: 45.0
      Sp. Atk: 63.0
      Sp. Def: 45.0
      Speed: 45
      Generation: 5
      Legendary: false
    - index: 561
      '#': 502
      Name: Dewott
      Type 1: Water
      Type 2: null
      Total: 413
      HP: 75.0
      Attack: 75.0
      Defense: 60.0
      Sp. Atk: 83.0
      Sp. Def: 60.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 563
      '#': 504
      Name: Patrat
      Type 1: Normal
      Type 2: null
      Total: 255
      HP: 45.0
      Attack: 55.0
      Defense: 39.0
      Sp. Atk: 35.0
      Sp. Def: 39.0
      Speed: 42
      Generation: 5
      Legendary: false
    - index: 564
      '#': 505
      Name: Watchog
      Type 1: Normal
      Type 2: null
      Total: 420
      HP: 60.0
      Attack: 85.0
      Defense: 69.0
      Sp. Atk: 60.0
      Sp. Def: 69.0
      Speed: 77
      Generation: 5
      Legendary: false
    - index: 565
      '#': 506
      Name: Lillipup
      Type 1: Normal
      Type 2: null
      Total: 275
      HP: 45.0
      Attack: 60.0
      Defense: 45.0
      Sp. Atk: 25.0
      Sp. Def: 45.0
      Speed: 55
      Generation: 5
      Legendary: false
    - index: 566
      '#': 507
      Name: Herdier
      Type 1: Normal
      Type 2: null
      Total: 370
      HP: 65.0
      Attack: 80.0
      Defense: 65.0
      Sp. Atk: 35.0
      Sp. Def: 65.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 568
      '#': 509
      Name: Purrloin
      Type 1: Dark
      Type 2: null
      Total: 281
      HP: 41.0
      Attack: 50.0
      Defense: 37.0
      Sp. Atk: 50.0
      Sp. Def: 37.0
      Speed: 66
      Generation: 5
      Legendary: false
    - index: 569
      '#': 510
      Name: Liepard
      Type 1: Dark
      Type 2: null
      Total: 446
      HP: 64.0
      Attack: 88.0
      Defense: 50.0
      Sp. Atk: 88.0
      Sp. Def: 50.0
      Speed: 106
      Generation: 5
      Legendary: false
    - index: 570
      '#': 511
      Name: Pansage
      Type 1: Grass
      Type 2: null
      Total: 316
      HP: 50.0
      Attack: 53.0
      Defense: 48.0
      Sp. Atk: 53.0
      Sp. Def: 48.0
      Speed: 64
      Generation: 5
      Legendary: false
    - index: 571
      '#': 512
      Name: Simisage
      Type 1: Grass
      Type 2: null
      Total: 498
      HP: 75.0
      Attack: 98.0
      Defense: 63.0
      Sp. Atk: 98.0
      Sp. Def: 63.0
      Speed: 101
      Generation: 5
      Legendary: false
    - index: 572
      '#': 513
      Name: Pansear
      Type 1: Fire
      Type 2: null
      Total: 316
      HP: 50.0
      Attack: 53.0
      Defense: 48.0
      Sp. Atk: 53.0
      Sp. Def: 48.0
      Speed: 64
      Generation: 5
      Legendary: false
    - index: 573
      '#': 514
      Name: Simisear
      Type 1: Fire
      Type 2: null
      Total: 498
      HP: 75.0
      Attack: 98.0
      Defense: 63.0
      Sp. Atk: 98.0
      Sp. Def: 63.0
      Speed: 101
      Generation: 5
      Legendary: false
    - index: 574
      '#': 515
      Name: Panpour
      Type 1: Water
      Type 2: null
      Total: 316
      HP: 50.0
      Attack: 53.0
      Defense: 48.0
      Sp. Atk: 53.0
      Sp. Def: 48.0
      Speed: 64
      Generation: 5
      Legendary: false
    - index: 575
      '#': 516
      Name: Simipour
      Type 1: Water
      Type 2: null
      Total: 498
      HP: 75.0
      Attack: 98.0
      Defense: 63.0
      Sp. Atk: 98.0
      Sp. Def: 63.0
      Speed: 101
      Generation: 5
      Legendary: false
    - index: 576
      '#': 517
      Name: Munna
      Type 1: Psychic
      Type 2: null
      Total: 292
      HP: 76.0
      Attack: 25.0
      Defense: 45.0
      Sp. Atk: 67.0
      Sp. Def: 55.0
      Speed: 24
      Generation: 5
      Legendary: false
    - index: 578
      '#': 519
      Name: Pidove
      Type 1: Normal
      Type 2: Flying
      Total: 264
      HP: 50.0
      Attack: 55.0
      Defense: 50.0
      Sp. Atk: 36.0
      Sp. Def: 30.0
      Speed: 43
      Generation: 5
      Legendary: false
    - index: 579
      '#': 520
      Name: Tranquill
      Type 1: Normal
      Type 2: Flying
      Total: 358
      HP: 62.0
      Attack: 77.0
      Defense: 62.0
      Sp. Atk: 50.0
      Sp. Def: 42.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 580
      '#': 521
      Name: Unfezant
      Type 1: Normal
      Type 2: Flying
      Total: 488
      HP: 80.0
      Attack: 115.0
      Defense: 80.0
      Sp. Atk: 65.0
      Sp. Def: 55.0
      Speed: 93
      Generation: 5
      Legendary: false
    - index: 581
      '#': 522
      Name: Blitzle
      Type 1: Electric
      Type 2: null
      Total: 295
      HP: 45.0
      Attack: 60.0
      Defense: 32.0
      Sp. Atk: 50.0
      Sp. Def: 32.0
      Speed: 76
      Generation: 5
      Legendary: false
    - index: 582
      '#': 523
      Name: Zebstrika
      Type 1: Electric
      Type 2: null
      Total: 497
      HP: 75.0
      Attack: 100.0
      Defense: 63.0
      Sp. Atk: 80.0
      Sp. Def: 63.0
      Speed: 116
      Generation: 5
      Legendary: false
    - index: 583
      '#': 524
      Name: Roggenrola
      Type 1: Rock
      Type 2: null
      Total: 280
      HP: 55.0
      Attack: 75.0
      Defense: 85.0
      Sp. Atk: 25.0
      Sp. Def: 25.0
      Speed: 15
      Generation: 5
      Legendary: false
    - index: 584
      '#': 525
      Name: Boldore
      Type 1: Rock
      Type 2: null
      Total: 390
      HP: 70.0
      Attack: 105.0
      Defense: 105.0
      Sp. Atk: 50.0
      Sp. Def: 40.0
      Speed: 20
      Generation: 5
      Legendary: false
    - index: 586
      '#': 527
      Name: Woobat
      Type 1: Psychic
      Type 2: Flying
      Total: 313
      HP: 55.0
      Attack: 45.0
      Defense: 43.0
      Sp. Atk: 55.0
      Sp. Def: 43.0
      Speed: 72
      Generation: 5
      Legendary: false
    - index: 587
      '#': 528
      Name: Swoobat
      Type 1: Psychic
      Type 2: Flying
      Total: 425
      HP: 67.0
      Attack: 57.0
      Defense: 55.0
      Sp. Atk: 77.0
      Sp. Def: 55.0
      Speed: 114
      Generation: 5
      Legendary: false
    - index: 588
      '#': 529
      Name: Drilbur
      Type 1: Ground
      Type 2: null
      Total: 328
      HP: 60.0
      Attack: 85.0
      Defense: 40.0
      Sp. Atk: 30.0
      Sp. Def: 45.0
      Speed: 68
      Generation: 5
      Legendary: false
    - index: 592
      '#': 532
      Name: Timburr
      Type 1: Fighting
      Type 2: null
      Total: 305
      HP: 75.0
      Attack: 80.0
      Defense: 55.0
      Sp. Atk: 25.0
      Sp. Def: 35.0
      Speed: 35
      Generation: 5
      Legendary: false
    - index: 595
      '#': 535
      Name: Tympole
      Type 1: Water
      Type 2: null
      Total: 294
      HP: 50.0
      Attack: 50.0
      Defense: 40.0
      Sp. Atk: 50.0
      Sp. Def: 40.0
      Speed: 64
      Generation: 5
      Legendary: false
    - index: 596
      '#': 536
      Name: Palpitoad
      Type 1: Water
      Type 2: Ground
      Total: 384
      HP: 75.0
      Attack: 65.0
      Defense: 55.0
      Sp. Atk: 65.0
      Sp. Def: 55.0
      Speed: 69
      Generation: 5
      Legendary: false
    - index: 599
      '#': 539
      Name: Sawk
      Type 1: Fighting
      Type 2: null
      Total: 465
      HP: 75.0
      Attack: 125.0
      Defense: 75.0
      Sp. Atk: 30.0
      Sp. Def: 75.0
      Speed: 85
      Generation: 5
      Legendary: false
    - index: 600
      '#': 540
      Name: Sewaddle
      Type 1: Bug
      Type 2: Grass
      Total: 310
      HP: 45.0
      Attack: 53.0
      Defense: 70.0
      Sp. Atk: 40.0
      Sp. Def: 60.0
      Speed: 42
      Generation: 5
      Legendary: false
    - index: 601
      '#': 541
      Name: Swadloon
      Type 1: Bug
      Type 2: Grass
      Total: 380
      HP: 55.0
      Attack: 63.0
      Defense: 90.0
      Sp. Atk: 50.0
      Sp. Def: 80.0
      Speed: 42
      Generation: 5
      Legendary: false
    - index: 602
      '#': 542
      Name: Leavanny
      Type 1: Bug
      Type 2: Grass
      Total: 500
      HP: 75.0
      Attack: 103.0
      Defense: 80.0
      Sp. Atk: 70.0
      Sp. Def: 80.0
      Speed: 92
      Generation: 5
      Legendary: false
    - index: 603
      '#': 543
      Name: Venipede
      Type 1: Bug
      Type 2: Poison
      Total: 260
      HP: 30.0
      Attack: 45.0
      Defense: 59.0
      Sp. Atk: 30.0
      Sp. Def: 39.0
      Speed: 57
      Generation: 5
      Legendary: false
    - index: 604
      '#': 544
      Name: Whirlipede
      Type 1: Bug
      Type 2: Poison
      Total: 360
      HP: 40.0
      Attack: 55.0
      Defense: 99.0
      Sp. Atk: 40.0
      Sp. Def: 79.0
      Speed: 47
      Generation: 5
      Legendary: false
    - index: 605
      '#': 545
      Name: Scolipede
      Type 1: Bug
      Type 2: Poison
      Total: 485
      HP: 60.0
      Attack: 100.0
      Defense: 89.0
      Sp. Atk: 55.0
      Sp. Def: 69.0
      Speed: 112
      Generation: 5
      Legendary: false
    - index: 606
      '#': 546
      Name: Cottonee
      Type 1: Grass
      Type 2: Fairy
      Total: 280
      HP: 40.0
      Attack: 27.0
      Defense: 60.0
      Sp. Atk: 37.0
      Sp. Def: 50.0
      Speed: 66
      Generation: 5
      Legendary: false
    - index: 607
      '#': 547
      Name: Whimsicott
      Type 1: Grass
      Type 2: Fairy
      Total: 480
      HP: 60.0
      Attack: 67.0
      Defense: 85.0
      Sp. Atk: 77.0
      Sp. Def: 75.0
      Speed: 116
      Generation: 5
      Legendary: false
    - index: 608
      '#': 548
      Name: Petilil
      Type 1: Grass
      Type 2: null
      Total: 280
      HP: 45.0
      Attack: 35.0
      Defense: 50.0
      Sp. Atk: 70.0
      Sp. Def: 50.0
      Speed: 30
      Generation: 5
      Legendary: false
    - index: 609
      '#': 549
      Name: Lilligant
      Type 1: Grass
      Type 2: null
      Total: 480
      HP: 70.0
      Attack: 60.0
      Defense: 75.0
      Sp. Atk: 110.0
      Sp. Def: 75.0
      Speed: 90
      Generation: 5
      Legendary: false
    - index: 610
      '#': 550
      Name: Basculin
      Type 1: Water
      Type 2: null
      Total: 460
      HP: 70.0
      Attack: 92.0
      Defense: 65.0
      Sp. Atk: 80.0
      Sp. Def: 55.0
      Speed: 98
      Generation: 5
      Legendary: false
    - index: 611
      '#': 551
      Name: Sandile
      Type 1: Ground
      Type 2: Dark
      Total: 292
      HP: 50.0
      Attack: 72.0
      Defense: 35.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 612
      '#': 552
      Name: Krokorok
      Type 1: Ground
      Type 2: Dark
      Total: 351
      HP: 60.0
      Attack: 82.0
      Defense: 45.0
      Sp. Atk: 45.0
      Sp. Def: 45.0
      Speed: 74
      Generation: 5
      Legendary: false
    - index: 614
      '#': 554
      Name: Darumaka
      Type 1: Fire
      Type 2: null
      Total: 315
      HP: 70.0
      Attack: 90.0
      Defense: 45.0
      Sp. Atk: 15.0
      Sp. Def: 45.0
      Speed: 50
      Generation: 5
      Legendary: false
    - index: 617
      '#': 556
      Name: Maractus
      Type 1: Grass
      Type 2: null
      Total: 461
      HP: 75.0
      Attack: 86.0
      Defense: 67.0
      Sp. Atk: 106.0
      Sp. Def: 67.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 618
      '#': 557
      Name: Dwebble
      Type 1: Bug
      Type 2: Rock
      Total: 325
      HP: 50.0
      Attack: 65.0
      Defense: 85.0
      Sp. Atk: 35.0
      Sp. Def: 35.0
      Speed: 55
      Generation: 5
      Legendary: false
    - index: 619
      '#': 558
      Name: Crustle
      Type 1: Bug
      Type 2: Rock
      Total: 475
      HP: 70.0
      Attack: 95.0
      Defense: 125.0
      Sp. Atk: 65.0
      Sp. Def: 75.0
      Speed: 45
      Generation: 5
      Legendary: false
    - index: 620
      '#': 559
      Name: Scraggy
      Type 1: Dark
      Type 2: Fighting
      Total: 348
      HP: 50.0
      Attack: 75.0
      Defense: 70.0
      Sp. Atk: 35.0
      Sp. Def: 70.0
      Speed: 48
      Generation: 5
      Legendary: false
    - index: 621
      '#': 560
      Name: Scrafty
      Type 1: Dark
      Type 2: Fighting
      Total: 488
      HP: 65.0
      Attack: 90.0
      Defense: 115.0
      Sp. Atk: 45.0
      Sp. Def: 115.0
      Speed: 58
      Generation: 5
      Legendary: false
    - index: 622
      '#': 561
      Name: Sigilyph
      Type 1: Psychic
      Type 2: Flying
      Total: 490
      HP: 72.0
      Attack: 58.0
      Defense: 80.0
      Sp. Atk: 103.0
      Sp. Def: 80.0
      Speed: 97
      Generation: 5
      Legendary: false
    - index: 623
      '#': 562
      Name: Yamask
      Type 1: Ghost
      Type 2: null
      Total: 303
      HP: 38.0
      Attack: 30.0
      Defense: 85.0
      Sp. Atk: 55.0
      Sp. Def: 65.0
      Speed: 30
      Generation: 5
      Legendary: false
    - index: 624
      '#': 563
      Name: Cofagrigus
      Type 1: Ghost
      Type 2: null
      Total: 483
      HP: 58.0
      Attack: 50.0
      Defense: 145.0
      Sp. Atk: 95.0
      Sp. Def: 105.0
      Speed: 30
      Generation: 5
      Legendary: false
    - index: 625
      '#': 564
      Name: Tirtouga
      Type 1: Water
      Type 2: Rock
      Total: 355
      HP: 54.0
      Attack: 78.0
      Defense: 103.0
      Sp. Atk: 53.0
      Sp. Def: 45.0
      Speed: 22
      Generation: 5
      Legendary: false
    - index: 626
      '#': 565
      Name: Carracosta
      Type 1: Water
      Type 2: Rock
      Total: 495
      HP: 74.0
      Attack: 108.0
      Defense: 133.0
      Sp. Atk: 83.0
      Sp. Def: 65.0
      Speed: 32
      Generation: 5
      Legendary: false
    - index: 627
      '#': 566
      Name: Archen
      Type 1: Rock
      Type 2: Flying
      Total: 401
      HP: 55.0
      Attack: 112.0
      Defense: 45.0
      Sp. Atk: 74.0
      Sp. Def: 45.0
      Speed: 70
      Generation: 5
      Legendary: false
    - index: 628
      '#': 567
      Name: Archeops
      Type 1: Rock
      Type 2: Flying
      Total: 567
      HP: 75.0
      Attack: 140.0
      Defense: 65.0
      Sp. Atk: 112.0
      Sp. Def: 65.0
      Speed: 110
      Generation: 5
      Legendary: false
    - index: 629
      '#': 568
      Name: Trubbish
      Type 1: Poison
      Type 2: null
      Total: 329
      HP: 50.0
      Attack: 50.0
      Defense: 62.0
      Sp. Atk: 40.0
      Sp. Def: 62.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 630
      '#': 569
      Name: Garbodor
      Type 1: Poison
      Type 2: null
      Total: 474
      HP: 80.0
      Attack: 95.0
      Defense: 82.0
      Sp. Atk: 60.0
      Sp. Def: 82.0
      Speed: 75
      Generation: 5
      Legendary: false
    - index: 631
      '#': 570
      Name: Zorua
      Type 1: Dark
      Type 2: null
      Total: 330
      HP: 40.0
      Attack: 65.0
      Defense: 40.0
      Sp. Atk: 80.0
      Sp. Def: 40.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 632
      '#': 571
      Name: Zoroark
      Type 1: Dark
      Type 2: null
      Total: 510
      HP: 60.0
      Attack: 105.0
      Defense: 60.0
      Sp. Atk: 120.0
      Sp. Def: 60.0
      Speed: 105
      Generation: 5
      Legendary: false
    - index: 633
      '#': 572
      Name: Minccino
      Type 1: Normal
      Type 2: null
      Total: 300
      HP: 55.0
      Attack: 50.0
      Defense: 40.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 75
      Generation: 5
      Legendary: false
    - index: 634
      '#': 573
      Name: Cinccino
      Type 1: Normal
      Type 2: null
      Total: 470
      HP: 75.0
      Attack: 95.0
      Defense: 60.0
      Sp. Atk: 65.0
      Sp. Def: 60.0
      Speed: 115
      Generation: 5
      Legendary: false
    - index: 635
      '#': 574
      Name: Gothita
      Type 1: Psychic
      Type 2: null
      Total: 290
      HP: 45.0
      Attack: 30.0
      Defense: 50.0
      Sp. Atk: 55.0
      Sp. Def: 65.0
      Speed: 45
      Generation: 5
      Legendary: false
    - index: 636
      '#': 575
      Name: Gothorita
      Type 1: Psychic
      Type 2: null
      Total: 390
      HP: 60.0
      Attack: 45.0
      Defense: 70.0
      Sp. Atk: 75.0
      Sp. Def: 85.0
      Speed: 55
      Generation: 5
      Legendary: false
    - index: 637
      '#': 576
      Name: Gothitelle
      Type 1: Psychic
      Type 2: null
      Total: 490
      HP: 70.0
      Attack: 55.0
      Defense: 95.0
      Sp. Atk: 95.0
      Sp. Def: 110.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 638
      '#': 577
      Name: Solosis
      Type 1: Psychic
      Type 2: null
      Total: 290
      HP: 45.0
      Attack: 30.0
      Defense: 40.0
      Sp. Atk: 105.0
      Sp. Def: 50.0
      Speed: 20
      Generation: 5
      Legendary: false
    - index: 639
      '#': 578
      Name: Duosion
      Type 1: Psychic
      Type 2: null
      Total: 370
      HP: 65.0
      Attack: 40.0
      Defense: 50.0
      Sp. Atk: 125.0
      Sp. Def: 60.0
      Speed: 30
      Generation: 5
      Legendary: false
    - index: 641
      '#': 580
      Name: Ducklett
      Type 1: Water
      Type 2: Flying
      Total: 305
      HP: 62.0
      Attack: 44.0
      Defense: 50.0
      Sp. Atk: 44.0
      Sp. Def: 50.0
      Speed: 55
      Generation: 5
      Legendary: false
    - index: 642
      '#': 581
      Name: Swanna
      Type 1: Water
      Type 2: Flying
      Total: 473
      HP: 75.0
      Attack: 87.0
      Defense: 63.0
      Sp. Atk: 87.0
      Sp. Def: 63.0
      Speed: 98
      Generation: 5
      Legendary: false
    - index: 643
      '#': 582
      Name: Vanillite
      Type 1: Ice
      Type 2: null
      Total: 305
      HP: 36.0
      Attack: 50.0
      Defense: 50.0
      Sp. Atk: 65.0
      Sp. Def: 60.0
      Speed: 44
      Generation: 5
      Legendary: false
    - index: 644
      '#': 583
      Name: Vanillish
      Type 1: Ice
      Type 2: null
      Total: 395
      HP: 51.0
      Attack: 65.0
      Defense: 65.0
      Sp. Atk: 80.0
      Sp. Def: 75.0
      Speed: 59
      Generation: 5
      Legendary: false
    - index: 645
      '#': 584
      Name: Vanilluxe
      Type 1: Ice
      Type 2: null
      Total: 535
      HP: 71.0
      Attack: 95.0
      Defense: 85.0
      Sp. Atk: 110.0
      Sp. Def: 95.0
      Speed: 79
      Generation: 5
      Legendary: false
    - index: 646
      '#': 585
      Name: Deerling
      Type 1: Normal
      Type 2: Grass
      Total: 335
      HP: 60.0
      Attack: 60.0
      Defense: 50.0
      Sp. Atk: 40.0
      Sp. Def: 50.0
      Speed: 75
      Generation: 5
      Legendary: false
    - index: 647
      '#': 586
      Name: Sawsbuck
      Type 1: Normal
      Type 2: Grass
      Total: 475
      HP: 80.0
      Attack: 100.0
      Defense: 70.0
      Sp. Atk: 60.0
      Sp. Def: 70.0
      Speed: 95
      Generation: 5
      Legendary: false
    - index: 648
      '#': 587
      Name: Emolga
      Type 1: Electric
      Type 2: Flying
      Total: 428
      HP: 55.0
      Attack: 75.0
      Defense: 60.0
      Sp. Atk: 75.0
      Sp. Def: 60.0
      Speed: 103
      Generation: 5
      Legendary: false
    - index: 649
      '#': 588
      Name: Karrablast
      Type 1: Bug
      Type 2: null
      Total: 315
      HP: 50.0
      Attack: 75.0
      Defense: 45.0
      Sp. Atk: 40.0
      Sp. Def: 45.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 650
      '#': 589
      Name: Escavalier
      Type 1: Bug
      Type 2: Steel
      Total: 495
      HP: 70.0
      Attack: 135.0
      Defense: 105.0
      Sp. Atk: 60.0
      Sp. Def: 105.0
      Speed: 20
      Generation: 5
      Legendary: false
    - index: 651
      '#': 590
      Name: Foongus
      Type 1: Grass
      Type 2: Poison
      Total: 294
      HP: 69.0
      Attack: 55.0
      Defense: 45.0
      Sp. Atk: 55.0
      Sp. Def: 55.0
      Speed: 15
      Generation: 5
      Legendary: false
    - index: 653
      '#': 592
      Name: Frillish
      Type 1: Water
      Type 2: Ghost
      Total: 335
      HP: 55.0
      Attack: 40.0
      Defense: 50.0
      Sp. Atk: 65.0
      Sp. Def: 85.0
      Speed: 40
      Generation: 5
      Legendary: false
    - index: 656
      '#': 595
      Name: Joltik
      Type 1: Bug
      Type 2: Electric
      Total: 319
      HP: 50.0
      Attack: 47.0
      Defense: 50.0
      Sp. Atk: 57.0
      Sp. Def: 50.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 657
      '#': 596
      Name: Galvantula
      Type 1: Bug
      Type 2: Electric
      Total: 472
      HP: 70.0
      Attack: 77.0
      Defense: 60.0
      Sp. Atk: 97.0
      Sp. Def: 60.0
      Speed: 108
      Generation: 5
      Legendary: false
    - index: 658
      '#': 597
      Name: Ferroseed
      Type 1: Grass
      Type 2: Steel
      Total: 305
      HP: 44.0
      Attack: 50.0
      Defense: 91.0
      Sp. Atk: 24.0
      Sp. Def: 86.0
      Speed: 10
      Generation: 5
      Legendary: false
    - index: 659
      '#': 598
      Name: Ferrothorn
      Type 1: Grass
      Type 2: Steel
      Total: 489
      HP: 74.0
      Attack: 94.0
      Defense: 131.0
      Sp. Atk: 54.0
      Sp. Def: 116.0
      Speed: 20
      Generation: 5
      Legendary: false
    - index: 660
      '#': 599
      Name: Klink
      Type 1: Steel
      Type 2: null
      Total: 300
      HP: 40.0
      Attack: 55.0
      Defense: 70.0
      Sp. Atk: 45.0
      Sp. Def: 60.0
      Speed: 30
      Generation: 5
      Legendary: false
    - index: 661
      '#': 600
      Name: Klang
      Type 1: Steel
      Type 2: null
      Total: 440
      HP: 60.0
      Attack: 80.0
      Defense: 95.0
      Sp. Atk: 70.0
      Sp. Def: 85.0
      Speed: 50
      Generation: 5
      Legendary: false
    - index: 662
      '#': 601
      Name: Klinklang
      Type 1: Steel
      Type 2: null
      Total: 520
      HP: 60.0
      Attack: 100.0
      Defense: 115.0
      Sp. Atk: 70.0
      Sp. Def: 85.0
      Speed: 90
      Generation: 5
      Legendary: false
    - index: 663
      '#': 602
      Name: Tynamo
      Type 1: Electric
      Type 2: null
      Total: 275
      HP: 35.0
      Attack: 55.0
      Defense: 40.0
      Sp. Atk: 45.0
      Sp. Def: 40.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 664
      '#': 603
      Name: Eelektrik
      Type 1: Electric
      Type 2: null
      Total: 405
      HP: 65.0
      Attack: 85.0
      Defense: 70.0
      Sp. Atk: 75.0
      Sp. Def: 70.0
      Speed: 40
      Generation: 5
      Legendary: false
    - index: 666
      '#': 605
      Name: Elgyem
      Type 1: Psychic
      Type 2: null
      Total: 335
      HP: 55.0
      Attack: 55.0
      Defense: 55.0
      Sp. Atk: 85.0
      Sp. Def: 55.0
      Speed: 30
      Generation: 5
      Legendary: false
    - index: 667
      '#': 606
      Name: Beheeyem
      Type 1: Psychic
      Type 2: null
      Total: 485
      HP: 75.0
      Attack: 75.0
      Defense: 75.0
      Sp. Atk: 125.0
      Sp. Def: 95.0
      Speed: 40
      Generation: 5
      Legendary: false
    - index: 668
      '#': 607
      Name: Litwick
      Type 1: Ghost
      Type 2: Fire
      Total: 275
      HP: 50.0
      Attack: 30.0
      Defense: 55.0
      Sp. Atk: 65.0
      Sp. Def: 55.0
      Speed: 20
      Generation: 5
      Legendary: false
    - index: 669
      '#': 608
      Name: Lampent
      Type 1: Ghost
      Type 2: Fire
      Total: 370
      HP: 60.0
      Attack: 40.0
      Defense: 60.0
      Sp. Atk: 95.0
      Sp. Def: 60.0
      Speed: 55
      Generation: 5
      Legendary: false
    - index: 670
      '#': 609
      Name: Chandelure
      Type 1: Ghost
      Type 2: Fire
      Total: 520
      HP: 60.0
      Attack: 55.0
      Defense: 90.0
      Sp. Atk: 145.0
      Sp. Def: 90.0
      Speed: 80
      Generation: 5
      Legendary: false
    - index: 674
      '#': 613
      Name: Cubchoo
      Type 1: Ice
      Type 2: null
      Total: 305
      HP: 55.0
      Attack: 70.0
      Defense: 40.0
      Sp. Atk: 60.0
      Sp. Def: 40.0
      Speed: 40
      Generation: 5
      Legendary: false
    - index: 676
      '#': 615
      Name: Cryogonal
      Type 1: Ice
      Type 2: null
      Total: 485
      HP: 70.0
      Attack: 50.0
      Defense: 30.0
      Sp. Atk: 95.0
      Sp. Def: 135.0
      Speed: 105
      Generation: 5
      Legendary: false
    - index: 677
      '#': 616
      Name: Shelmet
      Type 1: Bug
      Type 2: null
      Total: 305
      HP: 50.0
      Attack: 40.0
      Defense: 85.0
      Sp. Atk: 40.0
      Sp. Def: 65.0
      Speed: 25
      Generation: 5
      Legendary: false
    - index: 678
      '#': 617
      Name: Accelgor
      Type 1: Bug
      Type 2: null
      Total: 495
      HP: 80.0
      Attack: 70.0
      Defense: 40.0
      Sp. Atk: 100.0
      Sp. Def: 60.0
      Speed: 145
      Generation: 5
      Legendary: false
    - index: 680
      '#': 619
      Name: Mienfoo
      Type 1: Fighting
      Type 2: null
      Total: 350
      HP: 45.0
      Attack: 85.0
      Defense: 50.0
      Sp. Atk: 55.0
      Sp. Def: 50.0
      Speed: 65
      Generation: 5
      Legendary: false
    - index: 681
      '#': 620
      Name: Mienshao
      Type 1: Fighting
      Type 2: null
      Total: 510
      HP: 65.0
      Attack: 125.0
      Defense: 60.0
      Sp. Atk: 95.0
      Sp. Def: 60.0
      Speed: 105
      Generation: 5
      Legendary: false
    - index: 683
      '#': 622
      Name: Golett
      Type 1: Ground
      Type 2: Ghost
      Total: 303
      HP: 59.0
      Attack: 74.0
      Defense: 50.0
      Sp. Atk: 35.0
      Sp. Def: 50.0
      Speed: 35
      Generation: 5
      Legendary: false
    - index: 685
      '#': 624
      Name: Pawniard
      Type 1: Dark
      Type 2: Steel
      Total: 340
      HP: 45.0
      Attack: 85.0
      Defense: 70.0
      Sp. Atk: 40.0
      Sp. Def: 40.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 686
      '#': 625
      Name: Bisharp
      Type 1: Dark
      Type 2: Steel
      Total: 490
      HP: 65.0
      Attack: 125.0
      Defense: 100.0
      Sp. Atk: 60.0
      Sp. Def: 70.0
      Speed: 70
      Generation: 5
      Legendary: false
    - index: 688
      '#': 627
      Name: Rufflet
      Type 1: Normal
      Type 2: Flying
      Total: 350
      HP: 70.0
      Attack: 83.0
      Defense: 50.0
      Sp. Atk: 37.0
      Sp. Def: 50.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 690
      '#': 629
      Name: Vullaby
      Type 1: Dark
      Type 2: Flying
      Total: 370
      HP: 70.0
      Attack: 55.0
      Defense: 75.0
      Sp. Atk: 45.0
      Sp. Def: 65.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 693
      '#': 632
      Name: Durant
      Type 1: Bug
      Type 2: Steel
      Total: 484
      HP: 58.0
      Attack: 109.0
      Defense: 112.0
      Sp. Atk: 48.0
      Sp. Def: 48.0
      Speed: 109
      Generation: 5
      Legendary: false
    - index: 697
      '#': 636
      Name: Larvesta
      Type 1: Bug
      Type 2: Fire
      Total: 360
      HP: 55.0
      Attack: 85.0
      Defense: 55.0
      Sp. Atk: 50.0
      Sp. Def: 55.0
      Speed: 60
      Generation: 5
      Legendary: false
    - index: 702
      '#': 641
      Name: TornadusIncarnate Forme
      Type 1: Flying
      Type 2: null
      Total: 580
      HP: 79.0
      Attack: 115.0
      Defense: 70.0
      Sp. Atk: 125.0
      Sp. Def: 80.0
      Speed: 111
      Generation: 5
      Legendary: true
    - index: 703
      '#': 641
      Name: TornadusTherian Forme
      Type 1: Flying
      Type 2: null
      Total: 580
      HP: 79.0
      Attack: 100.0
      Defense: 80.0
      Sp. Atk: 110.0
      Sp. Def: 90.0
      Speed: 121
      Generation: 5
      Legendary: true
    - index: 704
      '#': 642
      Name: ThundurusIncarnate Forme
      Type 1: Electric
      Type 2: Flying
      Total: 580
      HP: 79.0
      Attack: 115.0
      Defense: 70.0
      Sp. Atk: 125.0
      Sp. Def: 80.0
      Speed: 111
      Generation: 5
      Legendary: true
    - index: 705
      '#': 642
      Name: ThundurusTherian Forme
      Type 1: Electric
      Type 2: Flying
      Total: 580
      HP: 79.0
      Attack: 105.0
      Defense: 70.0
      Sp. Atk: 145.0
      Sp. Def: 80.0
      Speed: 101
      Generation: 5
      Legendary: true
    - index: 717
      '#': 649
      Name: Genesect
      Type 1: Bug
      Type 2: Steel
      Total: 600
      HP: 71.0
      Attack: 120.0
      Defense: 95.0
      Sp. Atk: 120.0
      Sp. Def: 95.0
      Speed: 99
      Generation: 5
      Legendary: false
    - index: 718
      '#': 650
      Name: Chespin
      Type 1: Grass
      Type 2: null
      Total: 313
      HP: 56.0
      Attack: 61.0
      Defense: 65.0
      Sp. Atk: 48.0
      Sp. Def: 45.0
      Speed: 38
      Generation: 6
      Legendary: false
    - index: 719
      '#': 651
      Name: Quilladin
      Type 1: Grass
      Type 2: null
      Total: 405
      HP: 61.0
      Attack: 78.0
      Defense: 95.0
      Sp. Atk: 56.0
      Sp. Def: 58.0
      Speed: 57
      Generation: 6
      Legendary: false
    - index: 721
      '#': 653
      Name: Fennekin
      Type 1: Fire
      Type 2: null
      Total: 307
      HP: 40.0
      Attack: 45.0
      Defense: 40.0
      Sp. Atk: 62.0
      Sp. Def: 60.0
      Speed: 60
      Generation: 6
      Legendary: false
    - index: 722
      '#': 654
      Name: Braixen
      Type 1: Fire
      Type 2: null
      Total: 409
      HP: 59.0
      Attack: 59.0
      Defense: 58.0
      Sp. Atk: 90.0
      Sp. Def: 70.0
      Speed: 73
      Generation: 6
      Legendary: false
    - index: 723
      '#': 655
      Name: Delphox
      Type 1: Fire
      Type 2: Psychic
      Total: 534
      HP: 75.0
      Attack: 69.0
      Defense: 72.0
      Sp. Atk: 114.0
      Sp. Def: 100.0
      Speed: 104
      Generation: 6
      Legendary: false
    - index: 724
      '#': 656
      Name: Froakie
      Type 1: Water
      Type 2: null
      Total: 314
      HP: 41.0
      Attack: 56.0
      Defense: 40.0
      Sp. Atk: 62.0
      Sp. Def: 44.0
      Speed: 71
      Generation: 6
      Legendary: false
    - index: 725
      '#': 657
      Name: Frogadier
      Type 1: Water
      Type 2: null
      Total: 405
      HP: 54.0
      Attack: 63.0
      Defense: 52.0
      Sp. Atk: 83.0
      Sp. Def: 56.0
      Speed: 97
      Generation: 6
      Legendary: false
    - index: 726
      '#': 658
      Name: Greninja
      Type 1: Water
      Type 2: Dark
      Total: 530
      HP: 72.0
      Attack: 95.0
      Defense: 67.0
      Sp. Atk: 103.0
      Sp. Def: 71.0
      Speed: 122
      Generation: 6
      Legendary: false
    - index: 727
      '#': 659
      Name: Bunnelby
      Type 1: Normal
      Type 2: null
      Total: 237
      HP: 38.0
      Attack: 36.0
      Defense: 38.0
      Sp. Atk: 32.0
      Sp. Def: 36.0
      Speed: 57
      Generation: 6
      Legendary: false
    - index: 729
      '#': 661
      Name: Fletchling
      Type 1: Normal
      Type 2: Flying
      Total: 278
      HP: 45.0
      Attack: 50.0
      Defense: 43.0
      Sp. Atk: 40.0
      Sp. Def: 38.0
      Speed: 62
      Generation: 6
      Legendary: false
    - index: 730
      '#': 662
      Name: Fletchinder
      Type 1: Fire
      Type 2: Flying
      Total: 382
      HP: 62.0
      Attack: 73.0
      Defense: 55.0
      Sp. Atk: 56.0
      Sp. Def: 52.0
      Speed: 84
      Generation: 6
      Legendary: false
    - index: 731
      '#': 663
      Name: Talonflame
      Type 1: Fire
      Type 2: Flying
      Total: 499
      HP: 78.0
      Attack: 81.0
      Defense: 71.0
      Sp. Atk: 74.0
      Sp. Def: 69.0
      Speed: 126
      Generation: 6
      Legendary: false
    - index: 732
      '#': 664
      Name: Scatterbug
      Type 1: Bug
      Type 2: null
      Total: 200
      HP: 38.0
      Attack: 35.0
      Defense: 40.0
      Sp. Atk: 27.0
      Sp. Def: 25.0
      Speed: 35
      Generation: 6
      Legendary: false
    - index: 733
      '#': 665
      Name: Spewpa
      Type 1: Bug
      Type 2: null
      Total: 213
      HP: 45.0
      Attack: 22.0
      Defense: 60.0
      Sp. Atk: 27.0
      Sp. Def: 30.0
      Speed: 29
      Generation: 6
      Legendary: false
    - index: 734
      '#': 666
      Name: Vivillon
      Type 1: Bug
      Type 2: Flying
      Total: 411
      HP: 80.0
      Attack: 52.0
      Defense: 50.0
      Sp. Atk: 90.0
      Sp. Def: 50.0
      Speed: 89
      Generation: 6
      Legendary: false
    - index: 735
      '#': 667
      Name: Litleo
      Type 1: Fire
      Type 2: Normal
      Total: 369
      HP: 62.0
      Attack: 50.0
      Defense: 58.0
      Sp. Atk: 73.0
      Sp. Def: 54.0
      Speed: 72
      Generation: 6
      Legendary: false
    - index: 737
      '#': 669
      Name: Flabébé
      Type 1: Fairy
      Type 2: null
      Total: 303
      HP: 44.0
      Attack: 38.0
      Defense: 39.0
      Sp. Atk: 61.0
      Sp. Def: 79.0
      Speed: 42
      Generation: 6
      Legendary: false
    - index: 738
      '#': 670
      Name: Floette
      Type 1: Fairy
      Type 2: null
      Total: 371
      HP: 54.0
      Attack: 45.0
      Defense: 47.0
      Sp. Atk: 75.0
      Sp. Def: 98.0
      Speed: 52
      Generation: 6
      Legendary: false
    - index: 739
      '#': 671
      Name: Florges
      Type 1: Fairy
      Type 2: null
      Total: 552
      HP: 78.0
      Attack: 65.0
      Defense: 68.0
      Sp. Atk: 112.0
      Sp. Def: 154.0
      Speed: 75
      Generation: 6
      Legendary: false
    - index: 740
      '#': 672
      Name: Skiddo
      Type 1: Grass
      Type 2: null
      Total: 350
      HP: 66.0
      Attack: 65.0
      Defense: 48.0
      Sp. Atk: 62.0
      Sp. Def: 57.0
      Speed: 52
      Generation: 6
      Legendary: false
    - index: 742
      '#': 674
      Name: Pancham
      Type 1: Fighting
      Type 2: null
      Total: 348
      HP: 67.0
      Attack: 82.0
      Defense: 62.0
      Sp. Atk: 46.0
      Sp. Def: 48.0
      Speed: 43
      Generation: 6
      Legendary: false
    - index: 744
      '#': 676
      Name: Furfrou
      Type 1: Normal
      Type 2: null
      Total: 472
      HP: 75.0
      Attack: 80.0
      Defense: 60.0
      Sp. Atk: 65.0
      Sp. Def: 90.0
      Speed: 102
      Generation: 6
      Legendary: false
    - index: 745
      '#': 677
      Name: Espurr
      Type 1: Psychic
      Type 2: null
      Total: 355
      HP: 62.0
      Attack: 48.0
      Defense: 54.0
      Sp. Atk: 63.0
      Sp. Def: 60.0
      Speed: 68
      Generation: 6
      Legendary: false
    - index: 746
      '#': 678
      Name: MeowsticMale
      Type 1: Psychic
      Type 2: null
      Total: 466
      HP: 74.0
      Attack: 48.0
      Defense: 76.0
      Sp. Atk: 83.0
      Sp. Def: 81.0
      Speed: 104
      Generation: 6
      Legendary: false
    - index: 747
      '#': 678
      Name: MeowsticFemale
      Type 1: Psychic
      Type 2: null
      Total: 466
      HP: 74.0
      Attack: 48.0
      Defense: 76.0
      Sp. Atk: 83.0
      Sp. Def: 81.0
      Speed: 104
      Generation: 6
      Legendary: false
    - index: 748
      '#': 679
      Name: Honedge
      Type 1: Steel
      Type 2: Ghost
      Total: 325
      HP: 45.0
      Attack: 80.0
      Defense: 100.0
      Sp. Atk: 35.0
      Sp. Def: 37.0
      Speed: 28
      Generation: 6
      Legendary: false
    - index: 749
      '#': 680
      Name: Doublade
      Type 1: Steel
      Type 2: Ghost
      Total: 448
      HP: 59.0
      Attack: 110.0
      Defense: 150.0
      Sp. Atk: 45.0
      Sp. Def: 49.0
      Speed: 35
      Generation: 6
      Legendary: false
    - index: 750
      '#': 681
      Name: AegislashBlade Forme
      Type 1: Steel
      Type 2: Ghost
      Total: 520
      HP: 60.0
      Attack: 150.0
      Defense: 50.0
      Sp. Atk: 150.0
      Sp. Def: 50.0
      Speed: 60
      Generation: 6
      Legendary: false
    - index: 751
      '#': 681
      Name: AegislashShield Forme
      Type 1: Steel
      Type 2: Ghost
      Total: 520
      HP: 60.0
      Attack: 50.0
      Defense: 150.0
      Sp. Atk: 50.0
      Sp. Def: 150.0
      Speed: 60
      Generation: 6
      Legendary: false
    - index: 752
      '#': 682
      Name: Spritzee
      Type 1: Fairy
      Type 2: null
      Total: 341
      HP: 78.0
      Attack: 52.0
      Defense: 60.0
      Sp. Atk: 63.0
      Sp. Def: 65.0
      Speed: 23
      Generation: 6
      Legendary: false
    - index: 754
      '#': 684
      Name: Swirlix
      Type 1: Fairy
      Type 2: null
      Total: 341
      HP: 62.0
      Attack: 48.0
      Defense: 66.0
      Sp. Atk: 59.0
      Sp. Def: 57.0
      Speed: 49
      Generation: 6
      Legendary: false
    - index: 756
      '#': 686
      Name: Inkay
      Type 1: Dark
      Type 2: Psychic
      Total: 288
      HP: 53.0
      Attack: 54.0
      Defense: 53.0
      Sp. Atk: 37.0
      Sp. Def: 46.0
      Speed: 45
      Generation: 6
      Legendary: false
    - index: 758
      '#': 688
      Name: Binacle
      Type 1: Rock
      Type 2: Water
      Total: 306
      HP: 42.0
      Attack: 52.0
      Defense: 67.0
      Sp. Atk: 39.0
      Sp. Def: 56.0
      Speed: 50
      Generation: 6
      Legendary: false
    - index: 759
      '#': 689
      Name: Barbaracle
      Type 1: Rock
      Type 2: Water
      Total: 500
      HP: 72.0
      Attack: 105.0
      Defense: 115.0
      Sp. Atk: 54.0
      Sp. Def: 86.0
      Speed: 68
      Generation: 6
      Legendary: false
    - index: 760
      '#': 690
      Name: Skrelp
      Type 1: Poison
      Type 2: Water
      Total: 320
      HP: 50.0
      Attack: 60.0
      Defense: 60.0
      Sp. Atk: 60.0
      Sp. Def: 60.0
      Speed: 30
      Generation: 6
      Legendary: false
    - index: 762
      '#': 692
      Name: Clauncher
      Type 1: Water
      Type 2: null
      Total: 330
      HP: 50.0
      Attack: 53.0
      Defense: 62.0
      Sp. Atk: 58.0
      Sp. Def: 63.0
      Speed: 44
      Generation: 6
      Legendary: false
    - index: 763
      '#': 693
      Name: Clawitzer
      Type 1: Water
      Type 2: null
      Total: 500
      HP: 71.0
      Attack: 73.0
      Defense: 88.0
      Sp. Atk: 120.0
      Sp. Def: 89.0
      Speed: 59
      Generation: 6
      Legendary: false
    - index: 764
      '#': 694
      Name: Helioptile
      Type 1: Electric
      Type 2: Normal
      Total: 289
      HP: 44.0
      Attack: 38.0
      Defense: 33.0
      Sp. Atk: 61.0
      Sp. Def: 43.0
      Speed: 70
      Generation: 6
      Legendary: false
    - index: 765
      '#': 695
      Name: Heliolisk
      Type 1: Electric
      Type 2: Normal
      Total: 481
      HP: 62.0
      Attack: 55.0
      Defense: 52.0
      Sp. Atk: 109.0
      Sp. Def: 94.0
      Speed: 109
      Generation: 6
      Legendary: false
    - index: 768
      '#': 698
      Name: Amaura
      Type 1: Rock
      Type 2: Ice
      Total: 362
      HP: 77.0
      Attack: 59.0
      Defense: 50.0
      Sp. Atk: 67.0
      Sp. Def: 63.0
      Speed: 46
      Generation: 6
      Legendary: false
    - index: 771
      '#': 701
      Name: Hawlucha
      Type 1: Fighting
      Type 2: Flying
      Total: 500
      HP: 78.0
      Attack: 92.0
      Defense: 75.0
      Sp. Atk: 74.0
      Sp. Def: 63.0
      Speed: 118
      Generation: 6
      Legendary: false
    - index: 772
      '#': 702
      Name: Dedenne
      Type 1: Electric
      Type 2: Fairy
      Total: 431
      HP: 67.0
      Attack: 58.0
      Defense: 57.0
      Sp. Atk: 81.0
      Sp. Def: 67.0
      Speed: 101
      Generation: 6
      Legendary: false
    - index: 773
      '#': 703
      Name: Carbink
      Type 1: Rock
      Type 2: Fairy
      Total: 500
      HP: 50.0
      Attack: 50.0
      Defense: 150.0
      Sp. Atk: 50.0
      Sp. Def: 150.0
      Speed: 50
      Generation: 6
      Legendary: false
    - index: 777
      '#': 707
      Name: Klefki
      Type 1: Steel
      Type 2: Fairy
      Total: 470
      HP: 57.0
      Attack: 80.0
      Defense: 91.0
      Sp. Atk: 80.0
      Sp. Def: 87.0
      Speed: 75
      Generation: 6
      Legendary: false
    - index: 778
      '#': 708
      Name: Phantump
      Type 1: Ghost
      Type 2: Grass
      Total: 309
      HP: 43.0
      Attack: 70.0
      Defense: 48.0
      Sp. Atk: 50.0
      Sp. Def: 60.0
      Speed: 38
      Generation: 6
      Legendary: false
    - index: 780
      '#': 710
      Name: PumpkabooAverage Size
      Type 1: Ghost
      Type 2: Grass
      Total: 335
      HP: 49.0
      Attack: 66.0
      Defense: 70.0
      Sp. Atk: 44.0
      Sp. Def: 55.0
      Speed: 51
      Generation: 6
      Legendary: false
    - index: 781
      '#': 710
      Name: PumpkabooSmall Size
      Type 1: Ghost
      Type 2: Grass
      Total: 335
      HP: 44.0
      Attack: 66.0
      Defense: 70.0
      Sp. Atk: 44.0
      Sp. Def: 55.0
      Speed: 56
      Generation: 6
      Legendary: false
    - index: 782
      '#': 710
      Name: PumpkabooLarge Size
      Type 1: Ghost
      Type 2: Grass
      Total: 335
      HP: 54.0
      Attack: 66.0
      Defense: 70.0
      Sp. Atk: 44.0
      Sp. Def: 55.0
      Speed: 46
      Generation: 6
      Legendary: false
    - index: 783
      '#': 710
      Name: PumpkabooSuper Size
      Type 1: Ghost
      Type 2: Grass
      Total: 335
      HP: 59.0
      Attack: 66.0
      Defense: 70.0
      Sp. Atk: 44.0
      Sp. Def: 55.0
      Speed: 41
      Generation: 6
      Legendary: false
    - index: 784
      '#': 711
      Name: GourgeistAverage Size
      Type 1: Ghost
      Type 2: Grass
      Total: 494
      HP: 65.0
      Attack: 90.0
      Defense: 122.0
      Sp. Atk: 58.0
      Sp. Def: 75.0
      Speed: 84
      Generation: 6
      Legendary: false
    - index: 785
      '#': 711
      Name: GourgeistSmall Size
      Type 1: Ghost
      Type 2: Grass
      Total: 494
      HP: 55.0
      Attack: 85.0
      Defense: 122.0
      Sp. Atk: 58.0
      Sp. Def: 75.0
      Speed: 99
      Generation: 6
      Legendary: false
    - index: 786
      '#': 711
      Name: GourgeistLarge Size
      Type 1: Ghost
      Type 2: Grass
      Total: 494
      HP: 75.0
      Attack: 95.0
      Defense: 122.0
      Sp. Atk: 58.0
      Sp. Def: 75.0
      Speed: 69
      Generation: 6
      Legendary: false
    - index: 788
      '#': 712
      Name: Bergmite
      Type 1: Ice
      Type 2: null
      Total: 304
      HP: 55.0
      Attack: 69.0
      Defense: 85.0
      Sp. Atk: 32.0
      Sp. Def: 35.0
      Speed: 28
      Generation: 6
      Legendary: false
    - index: 795
      '#': 719
      Name: Diancie
      Type 1: Rock
      Type 2: Fairy
      Total: 600
      HP: 50.0
      Attack: 100.0
      Defense: 150.0
      Sp. Atk: 100.0
      Sp. Def: 150.0
      Speed: 50
      Generation: 6
      Legendary: true
    - index: 796
      '#': 719
      Name: DiancieMega Diancie
      Type 1: Rock
      Type 2: Fairy
      Total: 700
      HP: 50.0
      Attack: 160.0
      Defense: 110.0
      Sp. Atk: 160.0
      Sp. Def: 110.0
      Speed: 110
      Generation: 6
      Legendary: true
    - index: 797
      '#': 720
      Name: HoopaHoopa Confined
      Type 1: Psychic
      Type 2: Ghost
      Total: 600
      HP: 80.0
      Attack: 110.0
      Defense: 60.0
      Sp. Atk: 150.0
      Sp. Def: 130.0
      Speed: 70
      Generation: 6
      Legendary: true
    - index: 798
      '#': 720
      Name: HoopaHoopa Unbound
      Type 1: Psychic
      Type 2: Dark
      Total: 680
      HP: 80.0
      Attack: 160.0
      Defense: 60.0
      Sp. Atk: 170.0
      Sp. Def: 130.0
      Speed: 80
      Generation: 6
      Legendary: true
    - index: 799
      '#': 721
      Name: Volcanion
      Type 1: Fire
      Type 2: Water
      Total: 600
      HP: 80.0
      Attack: 110.0
      Defense: 120.0
      Sp. Atk: 130.0
      Sp. Def: 90.0
      Speed: 70
      Generation: 6
      Legendary: true
    params_names_for_user:
    - name: df
      type: dataframe
    params_names_from_user:
    - name: new_df
---
# {{ params_vars_title }}
This question uses the pokemon dataset (`df`), of which ten rows are shown below:

<pl-figure file-name="pokemon.png" directory="clientFilesQuestion"></pl-figure>

## Question Text

<div class="card my-2">
<div class="card-header">Subset</div>
<div class="card-body">

With the DataFrame above, how would you subset the database to return only {{ params_vars_ptype_op }}{{ params_vars_ptype }}-type Pokemon that have an HP {{ params_vars_hp_op }} {{ params_vars_hp }} points?

*Note: You should check both columns for the type - in other words, a pokemon is considered of that type if either Type 1 or Type 2 has that type.*

</div>
</div>

### Answer Section

### pl-submission-panel

{{feedback.df}}

<pl-external-grader-results></pl-external-grader-results>

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)