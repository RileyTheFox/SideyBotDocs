---
uid: Guides.Unilang.Swap
title: Swap
---

# Swap
### Aliases
`SWAP`, `SWP`, `PS`

## Overview
The Swap function will swap values of the two given variables. This function is intended to be used in conjunction with @Guides.Unilang.Load and @Guides.Unilang.Pattern functions.

## Arguments
| Name      | Type        | Description                              |
| --------- | ----------- | ---------------------------------------- |
| Variable1 | string      | The name of the first variable to swap.  |
| Variable2 | string      | The name of the second variable to swap. |

#### Example 1
```css
PAT(a,1234)PAT(b,2345)LOAD(a,b)SWAP(a,b)LOAD(a,b)
```
Will create two patterns with names `a` and `b`. Loads `a, b` then swaps `a, b` then loads `a, b`.

<img src="/images/unilang_examples/swap/example1.png" alt="Load Example 1" style="width:245px;"/>