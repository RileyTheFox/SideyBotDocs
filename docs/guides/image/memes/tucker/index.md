---
uid: Guides.Image.Memes.Tucker
title: Tucker
---

# Tucker
## Overview
The Tucker command will place the supplied image into the background of Tucker's reaction. The tucker overlay will be scaled to be 1/5th of the background's height, and will be placed 1/40th away from the edge of the image.

## Arguments
| Name        | Type        | Options                                           | Description                                                                 |
| ----------- | ----------- | ------------------------------------------------- | --------------------------------------------------------------------------- |
| Url         | String      | N/A                                               | The URL of the image to put into the background.                            |
| Image       | Attachment  | N/A                                               | An image attachment which will be used to place into the background.        |
| Corner      | Choice      | Top Left, Top Right, Bottom Left, Bottom Right    | Choose to place the Squad overlay on the left or right side of the image.   |

## Usage

### Example 1
```bash
/tucker url:"https://example.com/myimage.png"
```
Will place the image located at `https://example.com/myimage.png` into the background.

### Example 2
```bash
/tucker image:"Discord Image Attachment"
```
Will place the image attached with the command in Discord into the background.

### Example 3
```bash
/tucker url:"https://example.com/myimage.png" corner:"Top Right"
```
Will place the image located at `https://example.com/myimage.png` into the background and Tucker positioned in the top right corner.

### Example Image

<img src="gradient.png" alt="Gradient" style="width:300px;"/>

#### Example Result
```bash
/tucker corner: Top Left
```
Using the command with this image and side set to Top Left will produce the result below:

<img src="example1.png" alt="Tucker Example 1" style="width:350px;"/>