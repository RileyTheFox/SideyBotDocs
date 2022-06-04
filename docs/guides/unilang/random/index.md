---
uid: Guides.Unilang.Random
title: "Random"
---

# Random
### Aliases
`RANDOM`, `RND`, `S!RAND`

## Overview
The Random function will, as one might expect, place a random note. It will place a random note between the given min and max notes.

Using `RANDOM()` with no arguments is functionally identical to using a `?` character.

## Arguments
| Name                  | Type    | Description                                                                                                            |
| --------------------- | ------- | ---------------------------------------------------------------------------------------------------------------------- |
| MinValue *(optional)* | integer | The minimum value of the random function. Default is 1.                                                                |
| MaxValue *(optional)* | integer | The maximum value of the random function. Default is 5.                                                                |
| Seed *(optional)*     | integer | The seed to set while doing the random. A value of -2147483648 will use a random seed. This is also the default value. |

#### Example 1
```css
RND()RND()RND()RND()RND()
```
5 random notes. As the function is the "Random" function, it will be completely random every time.

<img src="example1.png" alt="Random Example 1" style="width:245px;"/>

#### Example 2
```css
ARP(RND(1,9),8)
```
8 random notes between 1 and 9.

<img src="example2.png" alt="Random Example 2" style="width:441px;"/>

## Using the ? Character
Using `?` does the same as using the Random function with default parameters `RANDOM(1,5)`.

#### Example 3
```css
??????????
```
10 question marks makes 10 random notes between 1 and 5.

<img src="example3.png" alt="Random Example 3" style="width:245px;"/>
