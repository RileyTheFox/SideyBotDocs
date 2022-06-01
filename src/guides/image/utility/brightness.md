---
uid: Guides.Image.Utility.Brightness
title: Brightness
---

# Brightness
## Overview
The Brightness command will set the brightness of the given image.

## Arguments
| Name        | Type        | Options           | Description                                                                 |
| ----------- | ----------- | ----------------- | --------------------------------------------------------------------------- |
| Amount      | float       | N/A               | How much to set the brightness to. Value less than 1 will darken the image. |
| Url         | String      | N/A               | The URL of the image to brighten.                                           |
| Image       | Attachment  | N/A               | An image attachment which will be used to brighten.                         |

## Usage

### Example 1
```bash
/brightness amount: 2 url:"https://example.com/myimage.png"
```
Will set the brightness of the image located at `https://example.com/myimage.png` to 2.

### Example 2
```bash
/brightness amount: 2 image:"Discord Image Attachment"
```
Will set the brightness of the image attached with the command in Discord to 2.

### Example Image

<img src="/images/image_examples/gradient.png" alt="Gradient" style="width:350px;"/>

#### Example Result 1
```bash
/brightness amount: 2
```
Using the command with brightness value 2, will brighten the image:

<img src="/images/image_examples/utility/brightness/example1.png" alt="Brightness Example 1" style="width:350px;"/>

#### Example Result 2
```bash
/brightness amount: 0.5
```
Using the command with brightness value 0.5, will darken the image:

<img src="/images/image_examples/utility/brightness/example2.png" alt="Brightness Example 2" style="width:350px;"/>