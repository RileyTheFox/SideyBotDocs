---
uid: Guides.Image.Memes.Highway
title: Highway
---

# Highway
## Overview
The Highway command will resize the supplied image into the dimensions (512x1024) of a Clone Hero Highway image.

## Arguments
| Name        | Type        | Options           | Description                                                    |
| ----------- | ----------- | ----------------- | -------------------------------------------------------------- |
| Url         | String      | N/A               | The URL of the image to make into a highway.                   |
| Image       | Attachment  | N/A               | An image attachment which will be used to make into a highway. |

## Usage

### Example 1
```bash
/highway url:"https://example.com/myimage.png"
```
Will turn the image located at `https://example.com/myimage.png` into a highway.

### Example 2
```bash
/highway image:"Discord Image Attachment"
```
Will turn the image attached with the command in Discord into a highway.

### Example Image

<img src="gradient.png" alt="Gradient" style="width:300px;"/>

#### Example Result
```bash
/highway
```
Using the command with this image will produce the result below:

<img src="example1.png" alt="Highway Example" style="width:256px;"/>
