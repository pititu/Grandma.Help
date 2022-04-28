---
title: Prune
---

# Prune
Module related to message deletion.

_`Required permissions: manager messages (bot, user), read message history (bot)`_

## prune `[amount=100]`
Deletes the last specified messages in this channel.

## prune `[user]` `[amount=100]`
Deletes the last specified messages in this channel sent by the user.

## prune `[channel]` `[amount=100]`
Deletes the last specified messages in the channel.

## prune `[timespan]`
Deletes the messages that have been sent during the timespan.

### Examples
* `prune 10h` - Deletes messages sent during the last 10 hours
* `prune 15m` - Deletes messages sent during the last 10 minutes
* `prune 30m15s` - Deletes messages sent during the last 30 minutes and 15 seconds
* `prune 5h30m15s` - Deletes messages sent during the last 5 hours, 30 minutes, and 15 seconds
