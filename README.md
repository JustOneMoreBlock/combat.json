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
