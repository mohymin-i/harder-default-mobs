# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

This is a Minecraft mod project ("harder-mobs-mod"). The project is in early initialization — no build system or source code exists yet.

## Setup

Once a Minecraft modding framework is chosen (e.g., Fabric, Forge, NeoForge), populate `project-spec.txt` with goals and add the relevant scaffolding. Typical mod project commands will then be:

- **Build**: `./gradlew build`
- **Run game with mod**: `./gradlew runClient`
- **Run tests**: `./gradlew test`
- **Run a single test**: `./gradlew test --tests "com.example.TestClass.testMethod"`
