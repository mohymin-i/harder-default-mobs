# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

This project is intended to make the vanilla minecraft mobs much more difficult to fight against, while maintaining the vanilla feel of the game. The core way in which this will be done is by arming the mobs with armors, weapons, potion effects, and mounts in order to make them significantly more challenging. 

In addition, spawn rates and spawn patterns will be altered so that these mobs spawn in much more challenging ways. It is intended that there be a day counter, which gradually makes the mobs stronger and stronger up until a certain point. 

Mob drops will be altered so that mobs drop better loot - creepers will drop more gunpowder and tnt, zombies and skeletons will drop ingots from the armors they are wearing, other mobs will drop better loot as well. Crucially, since these mobs are better armed and armored, they will NEVER drop their arms or armor, since this would lead to inventory cluttering and easy access to overpowered gear. 

The ultimate goal of this mod is to bring an element of challenge to the game. Once players have geared up and gotten maxxed out enchantments, it is relatively trivial for the player to deal with enemies the overworld. This mod seeks to change that. 
## Setup

Once a Minecraft modding framework is chosen (e.g., Fabric, Forge, NeoForge), populate `project-spec.txt` with goals and add the relevant scaffolding. Typical mod project commands will then be:

- **Build**: `./gradlew build`
- **Run game with mod**: `./gradlew runClient`
- **Run tests**: `./gradlew test`
- **Run a single test**: `./gradlew test --tests "com.example.TestClass.testMethod"`
