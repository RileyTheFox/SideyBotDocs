---
uid: Guides.Image.Utility.Rotate
title: Rotate
---

# Rotate
## Overview
The Rotate command will rotate the given image by the given amount of degrees.

## Arguments
| Name        | Type        | Options           | Description                                                                 |
| ----------- | ----------- | ----------------- | --------------------------------------------------------------------------- |
| Degrees     | float       | N/A               | How much to rotate the image by.                                            |
| Url         | String      | N/A               | The URL of the image to rotate.                                             |
| Image       | Attachment  | N/A               | An image attachment which will be rotate.                                   |

## Usage

### Example 1
```bash
/rotate degrees: 45 url:"https://example.com/myimage.png"
```
Will rotate the image located at `https://example.com/myimage.png` by 45 degrees.

### Example 2
```bash
/rotate degrees: 45 image:"Discord Image Attachment"
```
Will rotate the image attached with the command in Discord by 45 degrees.

### Example Image

<img src="gradient.png" alt="Gradient" style="width:350px;"/>

#### Example Result 1
```bash
/rotate degrees: 90
```
Using the command with rotation of 90 degrees:

<img src="example1.png" alt="Rotate Example 1" style="width:350px;"/>

#### Example Result 2
```bash
/rotate degrees: 45
```
Using the command with with rotation of 45 degrees to show that it can also rotate outside of multiples of 90:

<img src="example2.png" alt="Rotate Example 2" style="width:350px;"/>