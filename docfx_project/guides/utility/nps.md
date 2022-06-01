---
uid: Guides.Utility.Nps
title: NPS
---

# NPS
## Overview
The Nps command will find the NPS for a given BPM, Step and Speed.

## Arguments
| Name               | Type        | Options           | Description                                                 |
| ------------------ | ----------- | ----------------- | ----------------------------------------------------------- |
| BPM                | Float       | N/A               | The BPM you want.                                           |
| Step               | Float       | N/A               | The Step you want that NPS at.                              |
| Speed *(optional)* | Float       | N/A               | The Speed you want.                                         | 

## Usage

### Example
```bash
/nps bpm: 150 step: 32 speed: 110
```
This will find the NPS if you have notes at 150 BPM, 1/32nd notes at 110% speed.

```
22
```