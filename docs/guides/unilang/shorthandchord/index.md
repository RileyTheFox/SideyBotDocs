---
uid: Guides.Unilang.ShorthandChord
title: Shorthand Chord
---

# Shorthand Chord
### Aliases
`SHORTHAND_CHORD`, `SHORTCHORD`, `SC`

## Overview
The Shorthand Chord function takes letters as input and turns them into chords. 

> [!NOTE]
> Not to be confused with the @Guides.Unilang.Letters function.

This function is functionally identical to using `.` followed by a character.

This function is quite handy if you need to write shorter Unilang code.

## Arguments
| Name                 | Type         | Description                     |
| -------------------- | ------------ | ------------------------------- |
| ChordLetters         | string       | The shorthand chord letters.    |

## List of Chords
Here is a list of what letters map to each chord. The rule is that the top note will change first.

| One note     | Two note chords                                                                                          | Three note chords | Four note chords | Five note chords |
| ------------ | -------------------------------------------------------------------------------------------------------- | ----------------- | ---------------- | ---------------- |
| `0` -> `[0]` | `a` -> <img src="chord_a.png" alt="[12]" style="width:196px;"/> | `k` -> <img src="chord_k.png" alt="[123]" style="width:196px;"/> | `u` -> <img src="chord_u.png" alt="[1234]" style="width:196px;"/> | `z` -> <img src="chord_z.png" alt="[12345]" style="width:196px;"/>  |
| `1` -> `[1]` | `b` -> <img src="chord_b.png" alt="[13]" style="width:196px;"/> | `l` -> <img src="chord_l.png" alt="[124]" style="width:196px;"/> | `v` -> <img src="chord_v.png" alt="[1235]" style="width:196px;"/> |                  |
| `2` -> `[2]` | `c` -> <img src="chord_c.png" alt="[14]" style="width:196px;"/> | `m` -> <img src="chord_m.png" alt="[125]" style="width:196px;"/> | `w` -> <img src="chord_w.png" alt="[1245]" style="width:196px;"/> |                  |
| `3` -> `[3]` | `d` -> <img src="chord_d.png" alt="[15]" style="width:196px;"/> | `n` -> <img src="chord_n.png" alt="[134]" style="width:196px;"/> | `x` -> <img src="chord_x.png" alt="[1345]" style="width:196px;"/> |                  |
| `4` -> `[4]` | `e` -> <img src="chord_e.png" alt="[23]" style="width:196px;"/> | `o` -> <img src="chord_o.png" alt="[135]" style="width:196px;"/> | `y` -> <img src="chord_y.png" alt="[2345]" style="width:196px;"/> |                  |
| `5` -> `[5]` | `f` -> <img src="chord_f.png" alt="[24]" style="width:196px;"/> | `p` -> <img src="chord_p.png" alt="[145]" style="width:196px;"/> |                  |                  |
| `6` -> `[6]` | `g` -> <img src="chord_g.png" alt="[25]" style="width:196px;"/> | `q` -> <img src="chord_q.png" alt="[234]" style="width:196px;"/> |                  |                  |
| `7` -> `[7]` | `h` -> <img src="chord_h.png" alt="[34]" style="width:196px;"/> | `r` -> <img src="chord_r.png" alt="[235]" style="width:196px;"/> |                  |                  |
| `8` -> `[8]` | `i` -> <img src="chord_i.png" alt="[35]" style="width:196px;"/> | `s` -> <img src="chord_s.png" alt="[245]" style="width:196px;"/> |                  |                  | 
| `9` -> `[9]` | `j` -> <img src="chord_j.png" alt="[45]" style="width:196px;"/> | `t` -> <img src="chord_t.png" alt="[345]" style="width:196px;"/> |                  |                  |

#### Example 1
```css
SC(abcd)
```
Places the shorthand chords corresponding to the letters `a`, `b`, `c`, `d`, being `[12]`, `[13]`, `[14]`, `[15]`.

<img src="example1.png" alt="Shorthand Chord Example 1" style="width:245px;"/>

## Using Period . Characters
You can write `.` followed by one of the chord letters above to achieve the same as `SHORTHAND_CHORD()` with one letter input.

#### Example 2
```css
.a.e.h.j
```
Places the shorthand chords corresponding to the letters `a`, `e`, `h`, `j`, being `[12]`, `[23]`, `[34]`, `[45]`.

<img src="example2.png" alt="Shorthand Chord Example 2" style="width:245px;"/>

> [!TIP]
> Any chord is shorter to write using `.` notation. However, using it does come at the cost of readability.

> [!TIP]
> If you have more than 4 short hand chords, `SC(input)` notation becomes shorter than using `.` notation. 