---
uid: Guides.Unilang.TrackEvent
title: Track Event
---

# Track Event
### Aliases
`TRACKEVENT`, `LOCALEVENT`, `TE`, `LE`

## Overview
The Track Event function will create a track event at this point.

## Arguments
| Name        | Type        | Description                                   |
| ----------- | ----------- | --------------------------------------------- |
| Event name  | string      | The name of the event to place at this point. |

> [!Tip]
> Track Event is the exact same as a "Local Event" in MoonScraper.

#### Example
```css
12TE("hello")34
```
This will create a Track Event with name "hello" at the same location as the note with value 3 (yellow) after.

<img src="/images/unilang_examples/track_event/example1.png" alt="Track Event Example 1" style="width:350px;"/>

> [!Note]
> This example image does not represent what the /pattern command will output. It's just an example showing where the track event will go.