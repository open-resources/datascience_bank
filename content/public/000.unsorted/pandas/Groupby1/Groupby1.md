---
title: Subset
topic: Data Analysis
author: Gavin Kendal-Freedman
source: original
template_version: 1.4
attribution: standard
partialCredit: true
singleVariant: true
showCorrectAnswer: false
gradingMethod: Manual
outcomes:
- 7.3.2.4
- 7.3.2.5
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
part1:
  type: longtext
  pl-customizations:
    placeholder: Type your answer here...
    file-name: groupby.md
    quill-theme: bubble
    format: markdown
myst:
  substitutions:
    params_vars_title: Subset
    params_vars_groupby: Type 2
    params_vars_column: Sp. Def
---
# {{ params_vars_title }}

## Question Text

This question uses the first 10 rows of a modified version of the pokemon dataset (`df`):

<pl-figure file-name="pokemon.png" directory="clientFilesQuestion"></pl-figure>

<div class="card my-2">
<div class="card-header">Groupby</div>
<div class="card-body">

```python
df[0:10].groupby("{{ params_vars_groupby }}").count()[["{{ params_vars_column }}"]]
```

To get both marks, you must describe what it does AND why it might be useful.
Note, you do not need to give us the output of the command, just what it does and why it's useful.

*Note: If you use sources on the internet, please make sure you add a link (in the box below) to the source you used to avoid plagiarism.*

</div>
</div>

### Answer Section

Try to limit your answer to 5-7 sentences.

## Attribution

Problem is licensed under the [CC-BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/).<br> ![The Creative Commons 4.0 license requiring attribution-BY, non-commercial-NC, and share-alike-SA license.](https://raw.githubusercontent.com/firasm/bits/master/by-nc-sa.png)