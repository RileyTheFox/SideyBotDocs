---
uid: Guides.Utility.Bpm
title: BPM
---

# BPM
## Overview
The BPM command will find the BPM required for a certain NPS at a given step/quantization.

## Arguments
| Name        | Type        | Options           | Description                                                 |
| ----------- | ----------- | ----------------- | ----------------------------------------------------------- |
| NPS         | Float       | N/A               | The NPS you want.                                           |
| Step        | Float       | N/A               | The Step you want that Nps at.                              |

## Usage

### Example
```bash
/bpm nps: 20 step: 32
```
This will find the BPM required for 20 NPS at 1/32nd step:

```
150
```