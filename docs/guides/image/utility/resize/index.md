---
uid: Guides.Image.Utility.Resize
title: Resize
---

# Resize
## Overview
The Resize command will resize the given image to the given width and height.

## Arguments
| Name        | Type        | Options           | Description                                                                 |
| ----------- | ----------- | ----------------- | --------------------------------------------------------------------------- |
| Width       | Integer     | N/A               | The new width of the image.                                                 |
| Height      | Integer     | N/A               | The new height of the image.                                                |
| Url         | String      | N/A               | The URL of the image to resize.                                             |
| Image       | Attachment  | N/A               | An image attachment which will be resized.                                  |

## Usage

### Example 1
```bash
/resize width: 1920 height 1080 url:"https://example.com/myimage.png"
```
Will resize the image located at `https://example.com/myimage.png` to 1920x1080.

### Example 2
```bash
/resize width: 1920 height 1080 image:"Discord Image Attachment"
```
Will resize the image attached with the command in Discord to 1920x1080.

### Example Image

<img src="gradient.png" alt="Gradient" style="width:300px;"/>

#### Example Result
```bash
/resize width: 100 height: 100
```
Resizes the image to 100x100

<img src="example1.png" alt="Resize Example 1" style="width:100px;"/>