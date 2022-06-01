---
uid: Guides.Unilang.Chord
title: Chord
---

# Chord
### Aliases
`CHORD`, `CH`, `🎶`

## Overview
The Chord function will create a chord. Functionally, this works the exact same as encompassing something with square brackets `[]`.

For a shorter way to write 5 fret chords, see the @Guides.Unilang.ShorthandChord function.

## Arguments
| Name        | Type        | Description                         |
| ----------- | ----------- | ----------------------------------- |
| Pattern     | string      | The pattern to create a chord from. |

#### Example 1
```css
CHORD(345)321
```
Will create a chord with the notes 3, 4, 5, followed by singular notes of 3, 2, 1

<img src="/images/unilang_examples/chord/example1.png" alt="Chord Example 1" style="width:245px;"/>

## Square Brackets

The Chord function is the internal Unilang function for notes wrapped in square brackets `[]`.

#### Example 2
```css
[1234]135[2345]432[12]
```
An example showing usage of square brackets for chords instead of CHORD.

<img src="/images/unilang_examples/chord/example2.png" alt="Chord Example 2" style="width:245px;"/>

## Functions Within Chords

As the Chord function is a function, other functions can be put inside of chords.

#### Example 3
```css
[SW(1,5)]54321
```
Example showing function behaviour within chords. Namely the @Guides.Unilang.Sweep function from 1 to 5 within a chord.

<img src="/images/unilang_examples/chord/example3.png" alt="Chord Example 3" style="width:245px;"/>

## Note Values Above 5

As with notes, chords also allow note values above 5.

#### Example 4
```css
[1234567][345]
```
Example showing chords allowing values above 5.

<img src="/images/unilang_examples/chord/example4.png" alt="Chord Example 4" style="width:343px;"/>

> [!TIP]
> In SideyBot, note values are capped at 50. To write a note with higher values than 9, use `a-z` or `'10'` numbers in single quotes `'`.
> See more at @Guides.Unilang.Note

## Note Properties

Chords can have note properties, just like normal notes. See @Guides.Unilang.SetNoteProperties for more information.

#### Example 5
```css
[12345]{16}
```
Setting note properties after a chord will set the properties of the entire chord.

<img src="/images/unilang_examples/chord/example5.png" alt="Chord Example 5" style="width:245px;"/>

#### Example 6
```css
[123{16}45]
```
Setting note properties within a chord will set the properties of the accompanying fret.

<img src="/images/unilang_examples/chord/example6.png" alt="Chord Example 6" style="width:245px;"/>

> [!NOTE]
> If a fret inside already has note properties, the external note properties will not override that fret.

#### Example 7
```css
[123{16}45]{8}
```
Setting different note properties internally and externally.

<img src="/images/unilang_examples/chord/example7.png" alt="Chord Example 7" style="width:245px;"/>

## Open Notes

Chords can have open notes as a fret, just like in Clone Hero.

#### Example 8
```css
[024]12345
```
An example showing a chord with, Open, Red, Blue frets.

<img src="/images/unilang_examples/chord/example8.png" alt="Chord Example 8" style="width:245px;"/>

## HOPO and Tap Chords

HOPO and Tap rules apply to chords just like they do in Clone Hero.

#### Example 9
```css
[12][23][34][45]TAP([12][23][34][45])HOPO([12][23][34][45])
```
An example showing different types of chords.

<img src="/images/unilang_examples/chord/example9.png" alt="Chord Example 9" style="width:245px;"/>