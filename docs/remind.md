---
title: Remind
---

# Remind

## remind add `[date]` `[message?]`
Creates a new reminder.  

### `[date]`
* If it contains a space, it must be wrapped in quotation marks like so: `"September 10 2020 2:30pm"`

### Examples
* `remind add 10pm` - Creates a reminder that will fire at 10 PM.
* `remind add 10:25pm` - Creates a reminder that will fire at 10:25 PM.

## remind add `[timespan]` `[message?]`
Creates a new reminder.

### Examples
* `remind add 30m` - Creates a reminder that will fire in 30 minutes.
* `remind add 2h30m` - Creates a reminder that will fire in 2 hours and 30 minutes.

## remind remove `[id]`

## remind edit `[id]` `[new_message]`

## remind list
Lists your active reminders.

## remind info `[id]`
Shows information about an active reminder.
