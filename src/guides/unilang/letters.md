---
uid: Guides.Unilang.Letters
title: Letters
---

# Letters
### Aliases
`LETTERS`, `LETTER`, `LET`, `ABC`, `MTB`

## Overview
The Letters function will turn the characters you input into Message To Blue (MTB) style letters.

## Arguments
| Name        | Type        | Description                                 |
| ----------- | ----------- | ------------------------------------------- |
| InputString | string      | The input string to convert to letters.     |

> [!NOTE]
> The Letters function does support all of ascii and extended ascii but anything beyond will not work.

> [!TIP]
> Quantization does not affect the output of the Letters function.

> [!WARNING]
> Any control characters such as tabs and enter and carriage return will be ignored.

#### Example 1
```css
LET(ABC)
```
Will create MTB style letters of `"ABC"`.

<img src="/images/unilang_examples/letters/example1.png" alt="Letters Example 1" style="width:245px;"/>

## What about commas?

Because of how functions in Unilang work, commas `,` will be treated as a split between different function parameters.
However, you can get around this by using a string instead for your input. Within a string you can place any character.

> [!TIP]
> string escaping rules apply, so if you want to use a character such as a quote `"` in a string, 
> you will have to escape it using a backslash `\`. For `"` do `\"`, for `\` do `\\`

#### Example 2
```css
LET("HI, \"YO\"")
```
Example showing a string for commas and escaping characters as well as spaces.

<img src="/images/unilang_examples/letters/example2.png" alt="Letters Example 2" style="width:145px;"/>