---
title: Objects/User
---

#### Properties
* (string) Username
* (uint64) Id
* (string?) AvatarUrl
* (Date) CreateDate
* (string) Discriminator
* (boolean) IsBot
* (number?) [Flags](./#user-flags)

## User flags
| Flag							| Value		|
|-------------------------------|-----------|
| None							| 0			|
| DiscordEmployee				| 1			|
| DiscordPartner				| 2			|
| HypeSquadEvents				| 4			|
| BugHunterLevelOne				| 8			|
| HouseBravery					| 64 		|
| HouseBrilliance				| 128 		|
| HouseBalance					| 256 		|
| EarlySupporter				| 512 		|
| TeamUser						| 1024 		|
| System						| 4096 		|
| BugHunterLevelTwo				| 16384 	|
| VerifiedBot					| 65536 	|
| VerifiedBotDeveloper			| 131072 	|
| DiscordCertifiedModerator		| 262144 	|
| HttpInteractionsBot			| 524288 	|

