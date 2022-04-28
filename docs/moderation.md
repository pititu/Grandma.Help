---
title: Server moderation
---

# Moderation
Module related to server moderation.

## recreateChannel `[channel?]` (recreate)

_`Required permissions: manage channels (bot, user)`_

Deletes the channel and creates a new one with the same name, category, position, and permissions.

## ban `[user]` `[reason?]` (hackban)

_`Required permissions: ban members (bot, user)`_

Bans the user, even if they are not in the guild.

## nick lock `[user]` `[nickname]`

_`Required permissions: manage nicknames (bot), administrator (user)`_

Locks a user's nickname.

### `[user]`
* Cannot be in higher or same hierarchy than the bot.

### `[nickname]`
* Length cannot exceed 32 characters (will be trimmed). 

## nick unlock `[user]`

_`Required permissions: manage nicknames (bot), administrator (user)`_

Unlocks a user's nickname, can still be used if they aren't in the guild anymore.

## nick list (show)

_`Required permissions: manage nicknames (bot), administrator (user)`_

Lists currently locked nicknames.


