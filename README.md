# Introduction

## Plugin Description

**TerminatorPlus** is a **Spigot** **Plugin** that allows the creation of server-side player bots. Unlike many NPC plugins that already exist, this project has an emphasis on making the bots as human-like as possible.

## Supported Versions

During the Beta phase, Minecraft Server Version **1.16.5** is the single compatible version. 1.17 support will _likely_ roll out in the first stable release. Major forks of Spigot 1.16.5 are also compatible!

{% hint style="success" %}
You can choose to run the plugin on a 1.16.5 server and use the ViaVersion Plugin to allow 1.17 players to play at the same time!
{% endhint %}

## Getting Started

* [Download the plugin](https://discord.gg/horsenuggets)
* Put it in server plugins folder
* Restart your Minecraft Server
* Try out the `/tplus` command

## Building From Source

{% hint style="warning" %}
We do not recommend this as we've now automated our github development workflow to automatically scan and build on each new commit.
{% endhint %}

* `git clone https://github.com/HorseNuggets/TerminatorPlus`
* [Install and setup maven on your computer](https://maven.apache.org/install.html)
* `cd TerminatorPlus`
* `mvn clean package`
* find artifacts in the target directory
