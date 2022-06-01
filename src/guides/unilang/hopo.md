---
uid: Guides.Unilang.Hopo
title: HOPO
---

# HOPO
### Aliases
`HOPO`, `H`

## Overview
The HOPO function will turn all the notes within it to HOPOs.

## Arguments
| Name        | Type        | Description                     |
| ----------- | ----------- | ------------------------------- |
| Pattern     | string      | The pattern to make into HOPOs. |

> [!NOTE]
> The HOPO function will override any internal note type mutators.

#### Example 1
```css
HOPO(1234[12][23][34][45])
```
The example shows what happens when using the HOPO function.

<img src="/images/unilang_examples/hopo/example1.png" alt="HOPO Example 1" style="width:245px;"/>

> [!NOTE]
> The first note in any chart will always be a strum unless it is a tap.