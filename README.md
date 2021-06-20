# Valentine - 0.1
My personal 1.8.9 mc client

## Why?
Idk I was bored and this is very lightweight modification, since this is not Forge (garbage optimized) or some big client like Lunar or Badlion.
This is mainly aimed towards PVP and QOL. Target is 144fps vsync with fancy graphics.

## Warning!
- This is not Forge, this is Vanilla Minecraft with edited source
- Still in early development, use at your own risk (no bannable mods but still)
- No customization (this is my own personal client and all the source code is edited for me and not for you)

## Recommended Flags
> this is made to run on 1gb, no more, no less

`-client -d64 -Xms1G -Xmx1G -Xmn128m -XX:+UseG1GC -XX:+AlwaysPreTouch -XX:+UnlockExperimentalVMOptions -XX:MaxGCPauseMillis=100 -XX:+DisableExplicitGC -XX:TargetSurvivorRatio=90 -XX:G1NewSizePercent=50 -XX:G1MaxNewSizePercent=80 -XX:InitiatingHeapOccupancyPercent=10 -XX:G1MixedGCLiveThresholdPercent=50 -XX:+AggressiveOpts`

## How to use?
1. Go to [Releases](https://github.com/DxxxxY/Valentine/releases) tab and download the `.jar` and the `.json`.
2. Create a folder called `Valentine` in `.minecraft/versions` and move those two files inside.
3. Open launcher and create a new installation, select `Valentine` from the version list.
4. Put the above mentionned flags inside the `JVM Arguments` and you're good to go!

## Features
- Clear and unlimited scroll chat
- Dragon wings cosmetic (2x scale)
- Do not render glass
- Toggle Sprint
- Optifine
- Redesigned mc interface
- No harmful overlays (vignette, pumpkin, nausea, etc.)
- FPS and clock
- Particle multiplier (10x)
- Partial fps boost (fucked up the mc source so might have visual bugs)
- Fullbright
- More GUI options (server list, connect straight to Hypixel from menu, reconnect, etc.)
- Beautiful background (you can change it)
- No healthbar flicker
- No sidebar red numbers
