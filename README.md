# Nerds Hero Builds Project

## What is it?

It's a collection of Dota 2 in-game guides.

Initially it was started as "untraditional" builds, right now all the builds are based on high-rank stats (Divine stats provided by Stratz.com and based on custom reports made with League Report Generator), stream VODs and opinions from hero spammers.

Unlike Standart Hero Builds (from Torte De Lini), every Nerds Hero Guide is built around the idea of player being "advanced" player. A guide isn't plan for your game, but more like a collection of drafts and ideas that points out general patterns in item builds, suggests situational alternatives for various situations and made with "don't need to search for an item in the shop" principle in mind.

The goal is to make a guide for every hero and position it can be played on and add up information about alternatives and timings for every item, as well as have every build be up to date. It's not about making Core Crystal Maiden a thing. The main purpose of the project is to provide players with up-to-date builds trends and show the way to make weird stuff work, if you really want.

Right now there aren't many builds available, but we are working on it.

[List of all available builds](BUILDS.md)

## How can I use this site?

You can read buildfiles (it's just a code, but it's human readable) and get into builds. You can also go directly to [GitHub of the project to look over all the changes that were made](https://github.com/leamare/nerds-builds/commits/master).

## How to use these guides in game?

Choose the build you're most interested in, open its Steam page and just subscribe.

Alternatively, you can just use them in game, most of them are available from guides section.



Files in this repository are backups from my guides folder. These files are used by Dota 2 game client and its guides editor.

Buildfile format is human readable and looks like JSON in some way. You can edit it with any text editor and just suggest your commentaries and ideas as pull requests.

You can install these guides into "%ProgramFiles%/Steam/userdata/(your steam id)/570/remote/guides" folder.

It's recommended to make a symlink for this directory in your repo folder, so all the files will be located here. You can do that with following console commands:

- For windows - `mklink /D builds %SteamGuidesFolder`

- For linux and other unix-like - `ln -s %SteamGuidesFolder% builds`

## How can I suggest changes?

You can just checkout the repository, edit build file and make a pull request. If changes you made are useful, it will be merged into main branch. Another way is creating an issue in repository about change you'd like to make (for example "Treant (Roaming): commentaries" or "Enchantress (roaming): replace dragon lance with dagon"). There will be a discussion on that point and it will result in final decision and build changes.

**All the changes or suggested builds should be first discussed through issues on GitHub or directly on [Spectral Alliance Discord channel](https://discord.gg/7zKeeV8)**. Since all of the builds were initially published in my Steam profile it would be more convinient to publish all of them here (while also giving credit to original author). Same goes to all changes of the builds that were already published.

Publishing all the builds is kind of two-sided coin, but since the project is open to suggestions, it will ensure that it won't die when I'll burn up working on Nerds Hero Builds (I still will need to publish every change by myself, but it's not a big deal). **Please, consider that before submitting any changes.** And discuss them wherever you want if you have any suggestions.

## How are builds published?

This repository is more like "send your suggestions" part. All the builds are published in my steam profile and new ones will be as well. There's no way to "share" editing rights between various users, so we can just deal with it.

All builds that are published are going to be listed in BUILDS.md file.
