---
uid: Guides.Unilang.Load
title: Load
---

# Load
### Aliases
`LOAD`, `L`

## Overview
The Load function will load a variable at the current position and interpret it as a pattern.
Its intended use is together with Pattern functions or code blocks.
See @Guides.Unilang.Pattern and @Guides.Unilang.Code for more information about variables.

## Arguments
| Name         | Type        | Description                       |
| ------------ | ----------- | --------------------------------- |
| VariableName | string      | The name of the variable to load. |

> [!TIP]
> You can load multiple variables in a row by separating them by commas. `L(a,b)` will first load variable a, then variable b.

#### Example 1
```css
PAT(a,1234)LOAD(a)
```
Will load the variable with name `a` as a pattern. See @Guides.Unilang.Pattern for more about how to create patterns.

<img src="/images/unilang_examples/load/example1.png" alt="Load Example 1" style="width:245px;"/>

> [!WARNING]
> If you try to load a pattern that does not exist, you will get an error.

#### Example 2
```css
PAT(a,1234)PAT(b,2345)LOAD(a,b,b,a)
```
Loading multiple patterns in one Load function.

<img src="/images/unilang_examples/load/example2.png" alt="Load Example 2" style="width:245px;"/>

> [!WARNING]
> Loading itself within a `PATTERN` function will likely cause a recursion error.