---
uid: Guides.Unilang.Quantization
title: "Quantization"
---

# Quantization
### Aliases
`QUANTIZATION`, `STEP`, `QUANT` `Q`

## Overview
The Quantization function will set the quantization, or step of the parser at this point. A value of 16 means 1/16th step.
This function is functionally identical to using `|` for quantization. Ex. `|16|` means the same as `QUANTIZATION(16)`.

For a shorter way to write basic quantizations, see the @Guides.Unilang.ShorthandQuantization function.

## Arguments
| Name                  | Type    | Description                                                      |
| --------------------- | ------- | ---------------------------------------------------------------- |
| Value                 | integer | The value of the quantization as `1/value`.                      |
| SnapMode *(optional)* | string  | Defines the SnapMode for this quantization. Default is FORWARDS. |

Allowed snapmodes are NONE, FORWARDS, BACKWARDS.
See Examples 3a, 3b and 3c for the differences.

#### Example 1
```css
1234QUANT(8)5432
```
Sets the quantization to 1/8th after the blue note.

<img src="/images/unilang_examples/quantization/example1.png" alt="Quantization Example 1" style="width:245px;"/>

#### Example 2
```css
1234|8|5432
```
Yields the same result as Example 1, but using the `|` bar notation.

<img src="/images/unilang_examples/quantization/example1.png" alt="Quantization Example 2" style="width:245px;"/>

## Snap Mode
The second parameter of Quantization function defines what way quantization snapping should be handled.

It has three modes:

| Mode        | Behaviour                                                                     | Bar Notation                |
| ----------- | ----------------------------------------------------------------------------- | --------------------------- |
| `FORWARDS`  | Snaps to the next closest multiple unless it is already on that multiple.     | `|16|` - No Extra character |
| `BACKWARDS` | Snaps to the closest position after the previous note.                        | `|16:|` - Colon             |
| `NONE`      | No snapping, it just sets the quantization and. This can create offset notes. | `|16!|` - Exclamation Mark  |

`QUANT(16, NONE)` is the same as `|16!|`.

#### Example 3a

```css
123|12|123
```
`FORWARDS` snapping.

<img src="/images/unilang_examples/quantization/example3a.png" alt="Quantization Example 3a" style="width:245px;"/>

#### Example 3b

```css
123|12:|123
```
`BACKWARDS` snapping.

<img src="/images/unilang_examples/quantization/example3b.png" alt="Quantization Example 3b" style="width:245px;"/>

#### Example 3c

```css
123|12!|123
```
`NONE` snapping.

<img src="/images/unilang_examples/quantization/example3c.png" alt="Quantization Example 3c" style="width:245px;"/>
