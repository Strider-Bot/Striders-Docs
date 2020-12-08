---
description: Setting up Strider on your server!
---

# Setup

{% hint style="info" %}
**Before setup**, you should read this so you get the best out of the Strider setup process and of using the bot to its full potential. 

1. Make sure to setup the **Muted** Role and make it below the Strider role.
2. Place Strider's role properly. Put it above roles you want to be monitored \(preferably, at the top to avoid any problems\)
{% endhint %}

## Welcoming Message

When inviting Strider to your server the owner of the server will recieve a Message in PM which will include details about Strider in that certain server and also have some general commands in it..

## Sort Strider's role

Adding Strider will also add a new role specifically made for him. If you do not find such a role, it's advised that you kick and re-add the bot **without removing all permissions from it**. This role is exclusive and essential for Strider's functioning.  
**Place Strider's Role Above The Roles You Want It To Monitor.**

## **Setting Up Swearing AutoMod**

To setup the swearing system for Strider you first have to do `$swear toggle true` **\(by default its turned off\)** and to add a swear word to the database do `$swear add (Word)` and do `$swear delete (Word)` to delete a word from the database, if a swear word is detected in chat it will be deleted and a warning is sent to the user in chat. [AutoMod](commands-1/automod.md#swearing-system)

## Setting Up Server Prefix

To setup per server prefix type `$setprefix ?`in chat and it will change your prefix to ? you can change your Prefix to anything by using the same command and change ? to whatever it has a 5 character limit for the size.

## Setting Up Logging

To setup logging in your server use `$logs enable <#channel>`this will enable logging in the channel you put there, this will log all events to this channel this is a Audit Log with more details. To disable logging use `$logs disable` to disable it. [Logging System](commands-1/automod.md#logging-system)

## Setting Up Leveling

Strider come already setup for Server Levelling when inviting to your server, to check your Level/Rank use `$rank` and to see the server leaderboard use `$leaderboard`  and the XP levels for chatting are random each time so you cant level up loads. For all commands see Levelling Commands.

## Setting Up Music

The Music Commands is all ready and setup once you have invited Strider to your server, to get started use `$join` for it to join your current Voice Channel you are in. Then for it to start playing music use`$play (song)` then it will start playing to your current Voice Channel. For a full list of commands see [Music Commands](commands-1/music.md).

## Making A Giveaway

### Starting A Giveaway

To start a giveaway use the following command, `$start <#channel> (time) (winners) (name)` so for a giveaway in \#giveaways and for 1 day and with 1 winners use`$gstart #giveaways 1d 1 Nitro Giveaway` this will start the giveaway. See [Giveaways.](commands-1/giveaways.md)

### Giveaway Requirements

Coming Soon... 

## Custom Tags/Commands

### Custom Tags

A [custom tag](commands-1/moderation.md#custom-tags-commands) can be created using `$createtag (Tag) (Content)` this will create the tag, the `tag` will be what needs to be said in chat to say the response. Example: `$createtag info Server Info...` This will make is so when someone says info it will respond Server Info...

### Custom Commands

Coming Soon...

