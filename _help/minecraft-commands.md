---
layout: page
title: "Minecraft commands"
back:
  link: /help
  title: Help
---

This page lists some useful commands for the Minecraft server.

## In this page:

<a href="#homes" class="action">Homes</a>
<a href="#locks" class="action">Locks</a>
<a href="#teleporting" class="action">Teleporting</a>
<a href="#messaging" class="action">Messaging</a>
<a href="#time" class="action">Time</a>

## Homes

You can set up to 5 homes in Survival.

|---
| Command | Description |
|---
| /sethome [home] | Sets the current location as a home|
| /home [name] | Teleports to the specified home|
| /delhome [home] | Deletes the specified home|
|---

## Locks

These commands allow you to lock doors, as well as chests, furnaces, and other containers. when you place down a chest, it is automatically locked.

|---
| Command | Description |
|---
| /lock | Allows you to lock something by clicking on it.|
| /unlock | Removes the lock|
|---

Other types of locks: 

|---
| Command | Description |
|---
| /cdonation | Donation lock: players can insert items but cannot remove them |
| /cpassword [password] | Password lock |
| /cunlock [password] | Allows you to access a password-locked thing.|
| /cpublic | Public lock: all players can use the thing but cannot lock it.|
|---

Lock flags:

|---
| Command | Description |
|---
| /lwc flag redstone on | Disable redstone input (so things like levers cannot open that door) |
| /lwc flag redstone off | Enables redstone input |
| /lwc flag hopper on | Enable hoppers to interact with locked chests |
|---

More details on the lock plugin including adding others as members to a lock [can be found here](https://github.com/pop4959/LWCX/wiki/Commands).

## Teleporting

To teleport to a place: 

|---
| Command | Description |
|---
| /spawn | Teleports you back to spawn |
| /warp [name] | Teleports you to the specified warp. |
|---

To teleport a player or yourself:

|---
| Command | Description |
|---
| /tpa [player] | Sends a request to the player to teleport to them.|
| /tpahere [player] | Sends a request to the player to teleport them to you.|
| /tpaaccept and /tpdeny | Accepts or denies an incoming teleport request.|
| /tpauto | Automatically accept incoming teleport requests.|
|---

## Messaging

|---
| Command | Description |
|---
| /msg [player] [message] | Sends the private message to the specified player.|
| /r [message] | Replies to the last player that messaged you.|
|---

## Time

You can change your local time. 

These changes are visual and only applies to yourself! The server's time still apply: Phantoms will spawn when it's night, and this does not affect sleep or other players.

|---
| Command | Description |
|---
| /ptime [day\|night\|dawn\|17:30\|4pm] | Change your local time.|
| /ptime @[day\|night\|dawn\|17:30\|4pm] | Change your local time and pause time progression.|
| /ptime reset | Reset your local time to the server's time.|
|---
