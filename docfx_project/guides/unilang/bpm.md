---
uid: Guides.Unilang.Bpm
title: BPM
---

# BPM
### Aliases
`BPM`, `B`

## Overview
The BPM function will set the BPM of the chart at this point to the specified value.

## Arguments
| Name        | Type        | Description                               |
| ----------- | ----------- | ----------------------------------------- |
| Value       | float       | The bpm to set the chart to at this point.|

> [!NOTE]
> The BPM is float, meaning that, opposed to .chart files, a value of 140 will set the bpm to 140 instead of 140000.

> [!TIP]
> If there is no BPM function at the beginning of the code, then a BPM of 120 will be set from the beginning.
> This BPM will remain until a BPM function is specified.

#### Example
```css
12341234BPM(240)23452345
```
Will set the BPM to 240 after the first 8 notes.

<img src="/images/unilang_examples/bpm/example1.png" alt="Bpm Example 1" style="width:245px;"/>