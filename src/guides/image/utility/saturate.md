---
uid: Guides.Image.Utility.Saturate
title: Saturate
---

# Saturate
## Overview
The Saturate command will set the saturation of the given image.

## Arguments
| Name        | Type        | Options           | Description                                                                 |
| ----------- | ----------- | ----------------- | --------------------------------------------------------------------------- |
| Amount      | float       | N/A               | How much to set the saturation to.                                          |
| Url         | String      | N/A               | The URL of the image to saturate.                                         |
| Image       | Attachment  | N/A               | An image attachment which will be saturated.                                |

## Usage

### Example 1
```bash
/saturate amount: 2 url:"https://example.com/myimage.png"
```
Will set the saturation of the image located at `https://example.com/myimage.png` to 2.

### Example 2
```bash
/saturate amount: 2 image:"Discord Image Attachment"
```
Will set the saturation of the image attached with the command in Discord to 2.

### Example Image

<img src="/images/image_examples/gradient.png" alt="Gradient" style="width:350px;"/>

#### Example Result 1
```bash
/saturate amount: 10
```
Using the command with saturation value 10:

<img src="/images/image_examples/utility/saturate/example1.png" alt="Saturate Example 1" style="width:350px;"/>

#### Example Result 2
```bash
/saturate amount: 0.25
```
Using the command with saturation value 0.25:

<img src="/images/image_examples/utility/saturate/example2.png" alt="Saturate Example 2" style="width:350px;"/>