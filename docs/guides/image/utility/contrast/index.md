---
uid: Guides.Image.Utility.Contrast
title: Contrast
---

# Contrast
## Overview
The Contrast command will set the contrast of the given image.

## Arguments
| Name        | Type        | Options           | Description                                                                 |
| ----------- | ----------- | ----------------- | --------------------------------------------------------------------------- |
| Amount      | float       | N/A               | How much to set the contrast to.                                            |
| Url         | String      | N/A               | The URL of the image to contrast.                                           |
| Image       | Attachment  | N/A               | An image attachment which will be contrasted.                               |

## Usage

### Example 1
```bash
/contrast amount: 2 url:"https://example.com/myimage.png"
```
Will set the contrast of the image located at `https://example.com/myimage.png` to 2.

### Example 2
```bash
/contrast amount: 2 image:"Discord Image Attachment"
```
Will set the contrast of the image attached with the command in Discord to 2.

### Example Image

<img src="gradient.png" alt="Gradient" style="width:350px;"/>

#### Example Result 1
```bash
/contrast amount: 10
```
Using the command with contrast value 10:

<img src="example1.png" alt="Contrast Example 1" style="width:350px;"/>

#### Example Result 2
```bash
/contrast amount: 0.25
```
Using the command with contrast value 0.25:

<img src="example2.png" alt="Contrast Example 2" style="width:350px;"/>