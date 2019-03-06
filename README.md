# Minecraft Combat Changes

A lot players would like Mojang to change the Combat System back to 1.7 or 1.8, and essentially get rid of 1.9 PvP. However, they won't do this as "Spam Clicking" is not PvP.

I don't have a problem with PvP itself. However, the limitation from keeping 1.8 to Latest Minecraft compatibility is making servers not to grow, and not use all of Minecraft features.

That's because all the servers are stuck on Minecraft Server 1.8.x because of the Combat Changes in 1.9, and it's been the concenous amoung players they need to change something.

https://twitter.com/AntVenom/status/1102708478618025985

https://youtu.be/fET63lohY9Y?t=541

AntVenom recent posted a video about the 1.14 updates, and made a comment about adding a "/gamerule" to Minecraft, and players including myself have stated they need a "/gamerule", "/combat" or something in "server.properties" that will essentially allow Minecraft PvP 1.8 exist in  1.14, and then finally servers can finally upgrade, new servers can be brought online.

https://twitter.com/JustPlayHere/status/1102714657914187776

@mcabnormals make a comment of a video of his:
https://twitter.com/mcabnormals/status/1103024540337106945

Basically says a "/gamerule" wouldn't work because it's not meant to do that as it's meant for map making. Mojang created the game, and they can change the rules how gamerules work. In any event, they can easily add a "/combat" command to do the same thing as they did with "/difficulty".

Based on this YouTubers video, I saw his point a view but the idea could still be implemented. However, in a different way. Through a command, and would make a file called `combat.json`.

```
/combat cooldown shield 1.8
/combat cooldown sword 1.8
/combat cooldown tool 1.8
/combat cooldown fishingrod 1.8
```

At the moment, I based it off Minecraft versioniong to make it easy to understand. However, if Mojang implemented such command and/or file it would likely be a proper cooldown time.

The reason why I added "cooldown" to the json file as there could be awhole more to Minecraft Combat than basic configs. The proposed idea will allow the combat system to be modified server-based.
