---
uid: Guides.Image.Memes.JaredSelfie
title: Jared Selfie
---

# Jared Selfie
## Overview
The JaredSelfie command will place the supplied image into the background of CarnyJared's selfie. The Jared overlay will be scaled to fit the background proportionally.

## Arguments
| Name        | Type        | Options           | Description                                                                 |
| ----------- | ----------- | ----------------- | --------------------------------------------------------------------------- |
| Url         | String      | N/A               | The URL of the image to put into the background.                            |
| Image       | Attachment  | N/A               | An image attachment which will be used to place into the background.        |
| Side        | Choice      | Left, Right       | Choose to place the Jared overlay on the left or right side of the image.   |

## Usage

### Example 1
```bash
/jaredselfie url:"https://example.com/myimage.png"
```
Will place the image located at `https://example.com/myimage.png` into the background.

### Example 2
```bash
/jaredselfie image:"Discord Image Attachment"
```
Will place the image attached with the command in Discord into the background.

### Example 3
```bash
/jaredselfie url:"https://example.com/myimage.png" side:"Right"
```
Will place the image located at `https://example.com/myimage.png` into the background and Jared positioned on the right side.

### Example Image

<img src="gradient.png" alt="Gradient" style="width:300px;"/>

#### Example Result 1
```bash
/jaredselfie side: Left
```
Using the command with this image and side set to Left will produce the result below:

<img src="example1.png" alt="Jared Selfie Example 1" style="width:350px;"/>

#### Example Result 2
```bash
/jaredselfie side: Right
```
Using the command with this image and side set to Right will produce the result below:

<img src="example2.png" alt="Jared Selfie Example 2" style="width:350px;"/>