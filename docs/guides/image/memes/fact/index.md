---
uid: Guides.Image.Memes.Fact
title: Fact
---

# Fact
## Overview
The Fact command will place the given image or text into a screen with Schmooey saying "and that's a fact" to it.

## Arguments
| Name        | Type        | Options           | Description                                                                 |
| ----------- | ----------- | ----------------- | --------------------------------------------------------------------------- |
| Text        | String      | N/A               | The text to place in Schmooey's screen.                                     |
| Url         | String      | N/A               | The URL of the image to put onto Schmooey's screen.                         |
| Image       | Attachment  | N/A               | An image attachment which will be used to place onto Schmooey's screen.     |

## Usage

### Example 1
```bash
/fact url:"https://example.com/myimage.png"
```
Will place the image located at `https://example.com/myimage.png` in Schmooey's screen.

### Example 2
```bash
/fact image:"Discord Image Attachment"
```
Will place the image attached with the command in Discord in Schmooey's screen.

### Example 3
```bash
/fact text:"Hello everyone, this is some example text!"
```
Will place the text `"Hello everyone, this is some example text!"` in Schmooey's screen.

### Example Image

<img src="gradient.png" alt="Gradient" style="width:300px;"/>

#### Example Result
```bash
/fact
```
Using the command with this image will produce the result below:

<img src="example1.png" alt="Fact Example 1" style="width:350px;"/>

#### Example Result
```bash
/fact text: Hello everyone, this is some example text!
```
Using the command with this text will produce the result below:

<img src="example2.png" alt="Fact Example 2" style="width:350px;"/>
