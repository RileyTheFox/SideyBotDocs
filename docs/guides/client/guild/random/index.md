---
uid: Guides.Client.Guild.Random
title: Random
---

# Random
## Overview
The Random command will get random messages from the given channel. You can also 

## Arguments
| Name        | Type        | Options           | Description                                                                                                   |
| ----------- | ----------- | ----------------- | ------------------------------------------------------------------------------------------------------------- |
| Channel     | String      | N/A               | The name of channel to get random messages from. If left empty it will get messages from the current channel. |
| Count       | String      | N/A               | The amount of messages in a row to get. If empty it will get 1 message. Max is 10.                            |

## Usage

### Example
```
/random channel: #some-channel count: 2
```
This will get 2 random messages (which are in a row), from the channel named #some-channel.