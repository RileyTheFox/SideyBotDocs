---
uid: Guides.Unilang.Seed
title: Seed
---

# Seed
### Aliases
`SEED`, `RANDOMSEED`, `RS`

## Overview
The Seed function sets the seed for the global random number generator. 
This is useful if you want the Random function to have a predictable output.
For more information, see the @Guides.Unilang.Random function.

## Arguments
| Name        | Type        | Description                               |
| ----------- | ----------- | ----------------------------------------- |
| Seed        | integer     | The seed for the random number generator. |

#### Example 1
```css
SEED(0)ARP(?,16)
```
Sets the seed to 0, and places 16 random notes. Because the seed was set to a value, the output will always be consistent in this scenario.
Question marks `?` denote placing a random note. For more information, see the @Guides.Unilang.Random function.

<img src="/images/unilang_examples/seed/example1.png" alt="Seed Example 1" style="width:245px;"/>