---
uid: Guides.Unilang.Repeat
title: Repeat
---

# Repeat
### Aliases
`REPEAT`, `R`

## Overview
The Repeat function is very similar to the @Guides.Unilang.Arpeggiator Function in that it loops through notes.

## Arguments
| Name        | Type        | Description                  |
| ----------- | ----------- | ---------------------------- |
| Pattern     | string      | The pattern to repeat.       |
| Count       | integer     | How many times to repeat it. |

#### Example 1
```css
REPEAT(1254, 4)
```
Will repeat each note in the pattern "1254" a total of 4 times.

<img src="/images/unilang_examples/repeat/example1.png" alt="Repeat Example 1" style="width:245px;"/>

> [!WARNING]
> Currently this function is only partially implemented. So it wont be able to repeat everything like expected, full functionality is planned for a later release.