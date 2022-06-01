---
uid: Guides.Unilang.SnapMeasure
title: Snap Measure
---

# Snap Measure
### Aliases
`SNAP_MEASURE`, `SM`

## Overview
The Snap Measure function will snap to the nearest ***next*** measure. You can also specify an amount of measures to jump after snapping. Default is 0 measures.

## Arguments
| Name                   | Type        | Description                                                  |
| ---------------------- | ----------- | ------------------------------------------------------------ |
| JumpCount *(optional)* | integer     | The amount of measures to jump after snapping. Default is 0. |

> [!NOTE]
> If jump count is empty `SM()`, it will snap to the nearest measure and jump 0 measures, unless it is already on a measure, in which it will jump ot the ***next*** measure.

> [!TIP]
> Unlike the @Guides.Unilang.JumpStep function, this function behaves the same under any quantization.

#### Example 1
```css
123SM()543
```
This will snap to the nearest measure after the first yellow note.

<img src="/images/unilang_examples/snap_measure/example1.png" alt="Snap Measure Example 1" style="width:245px;"/>

#### Example 2
```css
123SM(1)543
```
This will snap to the nearest measure and jump one measure.

<img src="/images/unilang_examples/snap_measure/example2.png" alt="Snap Measure Example 2" style="width:145px;"/>