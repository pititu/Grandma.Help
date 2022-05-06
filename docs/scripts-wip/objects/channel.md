---
title: Objects/Channel
---

#### Properties
* (string) Name
* (uint64) Id
* (string) Topic
* (number) Position
* (uint64?) CategoryId
* (number) [Type](./#channel-types)
* (uint64?) LastMessageId
* (boolean) IsNsfw

#### Methods
* SendMessage(string message)
* DeleteMessage(uint64 id, string? reason)
* DeleteMessage(message message)
* PinLastMessage() _`returns the message`_
* UnpinLastMessage() _`returns the message`_

## Channel types
| Type            | Value   |
|-----------------|-----    |
| Text            | 0       |
| Private         | 1       |
| Voice           | 2       |
| Group           | 3       |
| Category        | 4       |
| News            | 5       |
| Store           | 6       |
| NewsThread      | 10      |
| PublicThread    | 11      |
| PrivateThread   | 12      |
| Stage           | 13      |


