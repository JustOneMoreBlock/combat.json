On March, 4th, 2019 AntVenom tweeted a new video he uploaded about the new Minecraft 1.14 Villager Trading, and in the video, he made a comment about the `Minecraft Combat PvP`, and ask Mojang to add-in a `/gamerule` to Minecraft.

Tweet: https://twitter.com/AntVenom/status/1102708478618025985

Combat Comment: https://youtu.be/fET63lohY9Y?t=541

After watching the video, and heard the comment I immediately made a comment to AntVenom about how many players in the Minecraft Community have been asking for changes to the Combat System with the ability to change using a `/gamerule`. I’ve mentioned to others in the past a possible `server.properties` setting.

2017: https://twitter.com/JustPlayHere/status/920034395465175041

2018: https://twitter.com/JustPlayHere/status/986767278904668161

2019: https://twitter.com/JustPlayHere/status/1102714657914187776

Over the years, the idea of it hasn’t changed. However, the method, and the way it should be approached has changed. In the 2019 tweet, a YouTuber by the name of @mcabnormals posted a video of “Why a gamerule won’t fix Combat PvP”.

https://twitter.com/mcabnormals/status/1103024540337106945

In the video, it states that a `/gamerule` is meant for map making. However, Mojang created Minecraft and how things are implemented is there decision. They could accomplish the same thing via a `/gamerule` or I’ve suggested a `combat=1.8` in the `server.properties` file. Although he does make a few points where it could make it limited.

Based on his screenshot of 1.8 vs 1.9 Combat PvP. I wrote a JSON file called `combat.json` as the proposed idea for Minecraft’s approach.

```
/combat cooldown shield 1.8
/combat cooldown sword 1.8
/combat cooldown tool 1.8
/combat cooldown fishingrod 1.8
```

At the moment it’s based off Minecraft Versioning. However, If I know Mojang they will likely make to use actually cooldown numbers. The purpose of showing it this way is to show an example of how it would work.

The reason why I added "cooldown" to the JSON file as there could be a whole more to Minecraft Combat than basic configs. The proposed idea will allow the combat system to be modified as needed.

On Thursday, June 27th, 2019 - Mojang released "A custom Java Edition snapshot to test new combat mechanics" for version `1.14` in order to gain feedback on `Combat Changes` they maybe pending for the next release of Minecraft 1.15 and Minecraft Bedrock Edition.

The end goal is to essentially have the same `Combat` on all platforms of Minecraft and where the issue lies as they need to be `BALANCED` to the be the same game on all platforms.

Source: https://www.reddit.com/r/Minecraft/comments/c5mqwv/a_custom_java_edition_snapshot_to_test_new_combat/

# BALANCED HARDCODED
They're for sure `Balacing` it, however, their approach is to hardcode the `BALANCE` and not give `Server Owners` the ability to do so.

# BALANCED FREEFORM
I prefer my method of creating the `combat.json` file at the start and they would be their default values. This still come later after it's been all polished and using a `-1` would essentially allow servers owners to disable the `1.9 PvP` and give us `1.7 or 1.8 PvP` to make everyone happy.

The end goal either way here regardless of the way they do it. `BALANCED HARDCODED` or `BALANCED FREEFORM` as long as `Players` upgrade their client from `1.7+` to the Latest Version of Minecraft.

If `Players Upgrade` eventually in time `Servers WILL Upgrade`.

Why is this important?
If players are happy on the latest version of Minecraft with the new `Combat Mechanics` then `Server Owners` no longer need a reason to continue support for `Minecraft 1.7 to at least Minecraft 1.12.2`. This would support 1.13+ versions only, and then eventually as newer upgrades progess older versions can be `RETIRED`.

EOL = End of Life

# COMBAT CHANGES UPGRADE MAP
| Client Version | Server Version |  EOL Server Support |
|--|--|--|
| Minecraft 1.15.x | Minecraft 1.15.x | Minecraft 1.8.9-1.13.2 |
| Minecraft 1.16.x | Minecraft 1.16.x | Minecraft 1.14.x |
| Minecraft 1.17.x | Minecraft 1.17.x | Minecraft 1.15.x-1.16.x |

If `Client Version` and `Server Version` then `EOL Server Support`
