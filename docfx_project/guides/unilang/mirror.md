---
uid: Guides.Unilang.Mirror
title: Mirror
---

# Mirror
### Aliases
`MIRROR`, `RORRIM`, `M`

## Overview
The Mirror function will mirror the given pattern around the given max note.

## Arguments
| Name                      | Type        | Description                                                           |
| ------------------------- | ----------- | --------------------------------------------------------------------- |
| Pattern                   | string      | Pattern to mirror.                                                    |
| MaxNote *(optional)*      | integer     | The maximum note value at which to mirror around. Default value is 5. |

> [!NOTE]
> If the given pattern contains notes that are above the given MaxNote, it will mirror around the pattern's max note instead.

#### Example 1
```css
MIRROR(12345)
```
Will mirror the 5 notes.

<img src="/images/unilang_examples/mirror/example1.png" alt="Mirror Example 1" style="width:245px;"/>

#### Example 2
```css
MIRROR(12345, 7)
```
Will mirror the 5 notes with max note at value 7.

<img src="/images/unilang_examples/mirror/example2.png" alt="Mirror Example 2" style="width:343px;"/>