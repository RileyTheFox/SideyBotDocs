---
uid: Guides.Unilang.Section
title: Section
---

# Section
### Aliases
`SECTION`, `SEC`

## Overview
The Section function will create a section at this point.

## Arguments
| Name          | Type        | Description                                     |
| ------------- | ----------- | ----------------------------------------------- |
| Section name  | string      | The name of the section to place at this point. |

#### Example
```css
12SEC("hello")34
```
This will create a section with name "hello" at the same location as the note with value 3 (yellow) after.

<img src="example1.png" alt="Section Example 1" style="width:350px;"/>

> [!Note]
> This example image does not represent what the /pattern command will output. It's just an example showing where the section will go.