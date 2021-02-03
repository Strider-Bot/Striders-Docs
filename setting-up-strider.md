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

To setup the swearing system for Strider you first have to do `$swear toggle true` **\(by default its turned off\)** and to add a swear word to the database do `$swear add (Word)` and do `$swear delete (Word)` to delete a word from the database, if a swear word is detected in chat it will be deleted and a warning is sent to the user in chat. [AutoMod](commands-1/bot-settings/automod.md#swearing-system)

## Setting Up Server Prefix

To setup per server prefix type `$prefix ?`in chat and it will change your prefix to _?_ you can change your Prefix to anything by using the same command and change _?_ to whatever it has a 5 character limit for the size.

## Setting Up Logging

To setup logging in your server use `$enable-logs <all/verification/server/emoji/role/member/mod> <#channel>` The options in the &lt;option/option&gt; will specify whats logs go where so you could have your Verification Logs seprate from the rest etc, to disabled all Logs you can do `$disable-logs all`

## Setting Up Verification

To setup Strider's Verification System you will first need to make a verification channel, i have made a channel called _**\#verification**_  now lets do `$verification channel #verification` now that the channel is setup lets setup the role the user will get after they have verified, lets make a role called _**Member**_ and then do `$verification role @Member` now that we've setup the system lets do `$verification enable` to enable it. Now when a new user joins they will only be able to see the _**\#verification**_ channel then they will get a DM to verify there account and will be let into the server, the Pending Verification role is automatically setup once verification is enabled and will isolate new users to the _**\#verification \(Your Verification Channel\)**_ channel until verified.

## Setting Up Leveling

Strider come already setup for Server Leveling when inviting to your server, to check your Level/Rank use `$level` and to see the server leaderboard use `$leaderboard levels`  and the XP levels for chatting are random each time so you cant level up loads. For all commands see Levelling Commands.

## Setting Up Music

The Music Commands is all ready and setup once you have invited Strider to your server, to get started use `$join` for it to join your current Voice Channel you are in. Then for it to start playing music use`$play (song)` then it will start playing to your current Voice Channel. For a full list of commands see [Music Commands](commands-1/music.md).

## Making A Giveaway

### Starting A Giveaway

To start a giveaway use the following command, `$start <#channel> (time) (winners) (name)` so for a giveaway in \#giveaways and for 1 day and with 1 winners use`$gstart #giveaways 1d 1 Nitro Giveaway` this will start the giveaway. See [Giveaways.](commands-1/giveaways.md)

### Giveaway Requirements

Coming Soon... 

## Custom Tags/Commands

### Custom Tags

A [custom tag](commands-1/moderation/#custom-tags-commands) can be created using `$createtag (Tag) (Content)` this will create the tag, the `tag` will be what needs to be said in chat to say the response. Example: `$createtag info Server Info...` This will make is so when someone says info it will respond Server Info...

### Custom Commands

Coming Soon...

