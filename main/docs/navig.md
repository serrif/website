---
title: Navigation
permalink: /docs/navig

layout: post
sidenav: docs
subnav:
  - text: Switching worlds
    href: '#switching-worlds'
  - text: Location
    href: '#location'
  - text: Dynamic map
    href: '#dynamic-map'
  - text: Resource pack
    href: '#resource-pack'
---

# Navigation
We have different types of worlds so members may choose any environment they like.
While every world shares the same set of guidelines, they can help distinguish the atmosphere of builds.

## Switching worlds
Worlds can be switched by any member.
To do this, we have the command `/world`, which allows you to specify different types of worlds to visit.
Most to-world commands will have an alias, listed below.

### Default world
The default world (flatlands) is where you spawn in upon death or as a new player.
You can build anything anywhere in this world; it only wipes if the map gets too big, is corrupted, or has been ruined.

 * `/spawn` - Teleports a player to the spawn (in the flatlands).
 * `/flatlands` - Teleports a player to the flatlands.

### Primary worlds
Primary worlds (roughlands, netherlands, enderlands) are places you don't naturally spawn in, but can access using commands.
These worlds will only wipe if they're corrupted and members can build here, just like the flatlands.

The roughlands includes natural biomes—such as deserts, prairies, and jungles; the netherlands (or [nether world](https://minecraft.gamepedia.com/The_Nether)) and the enderlands (or [end world](https://minecraft.gamepedia.com/The_End)) are also maintained, including the distinctive features of each realm.

#### Command usage
 * `/world <number>` - Teleports a player to the world they specify.
 * `/roughlands` - Teleports a player to the roughlands.
 * `/nether` - Teleports a player to the netherlands.
 * `/ender` - Teleports a player to the enderlands.
 
The `/world` command's perimeter is required.
 * `<number>` - Specifies a world number. Each number (`0` to `4`) takes you somewhere else.

Here's each number and the world it corresponds to.
 * `0` - To the roughlands. Direct is `/roughlands`.
 * `1` - To the netherlands. Direct is `/nether`.
 * `2` - To the enderlands. Direct is `/ender`.
 * `3` - To the flatlands. Direct is `/flatlands` or `/spawn`.
 * `4` - To the adminworld. Only admins can do this. Direct is `/adminworld` or `/aw`.

### Adminworld
The adminworld is a private world that only Super Admins and above can go in.
On occasion, an admin can invite someone as a "guest", allowing them to join the adminworld for a small amount of time until the server restarts.

 * `/adminworld` - Teleports an administrator to the adminworld.
 * `/aw` - An alias of the previous command and serves the same function.
 
#### Guest management
As mentioned above, guests can be invited to the adminworld by administrators.
They can also be revoked and reset as specified by the `/adminworld` command.

> **Note:** Guests, once added, are capable of modifying the adminworld (placing and breaking blocks) in-game. Because of this, admins should **never add guests on-demand** and carefully watch added members.

 * `/adminworld guest list` - Lists any members added to the guest list.
 * `/adminworld guest purge` - Purges the guest list, removing any added member.

You can directly add and remove members to/from the guest list with the below commands.

 * `/adminworld guest add <user>` - Adds a member to the guest list.
 * `/adminworld guest remove <user>` - Removes a member from the guest list.

## Location
Our server uses the basic Essentials kit of commands.
As a result, you can bookmark a set of coordinates both for the public and as a private home.

### Using warps
A warp is a keyword that allows anyone to teleport to a set of coordinates.
Warps are public and can be viewed by anyone, and they can also be overridden.

 * `/warps` - Provides a list of existing warps.
 * `/warp <warp>` - Allows you to... warp to a warp. (Sounds weird, right?)
 
Warps can only be deleted by an Executive or higher through the control panel.

 * `/delwarp <warp>` - Deletes an existing warp; console-only. Will not remove the build.
 
### Using homes
Members can set their own home, which is just like a private warp.
Homes won't appear in the public list of warps and they're good for referencing locations.

> **Note:** Unlike warps, members can't go to homes set by others. They're specific to whoever has set them previously. If you'd like to have a public keyword, you should be using warps instead.

 * `/homes` - Provides a list of your homes.
 * `/home <home>` - Takes you home to a home. (Slightly less weird.)
 * `/delhome <home` - Deletes an existing home. Will not remove the build.
 
### Teleportation
Anyone can use basic commands if they'd like to teleport to other players, but we require their content.
Privacy is important to us, so we don't allow intrusive commands.

> **Note:** `/tp` and `/tpo` can only be used by administrators, which is why only the `/tpa` set of commands are documented.

All `/tpa` commands require approval from the second member for your relocation.

 * `/tpa <user>` - Teleports you to the location of another member.
 * `/tpask <user>` - An alias of the previous command and serves the same function.
 * `/tpahere <user>` - Teleports another member to your location.
 
The request, sent to another member, can be easily approved or denied with a short response command.

 * `/tpaccept` - Accepts an incoming teleportation request.
 * `/tpyes` - An alias of the previous command and serves the same function.
 * `/tpdeny` - Denies an incoming teleportation request.
 * `/tpno` - An alias of the previous command and serves the same function.
 
If you'd like to prevent any member from teleporting to you, incoming requests can be disabled.

 * `/tptoggle [on | off]` - Toggles the ability for incoming requests, or you can set a value.
 
### Other commands
WorldEdit and other plugins come bundled with navigaton-centic commands.
Teleportation features with narrow functionality are listed here.

 * `/thru` - No arguments, teleports you through the block you are specifically facing.
 * `/tppos <x> <y> <z> [yaw] [pitch]` - Takes you to a specified set of block coordinates.

## Dynamic map
Dynmap, as abbreviated in the name, is a dynamic map generator.
This plugin can generate a bird's-eye view of any world through your web browser.
With the online interface, you can also view statistics and use the in-game chat.

### Web interface
The map can be opened like any other webpage [here](http://b.shadow.ga:26589).
From there, it will take you to the default world (flatlands).
By clicking on the arrow to your right, you can select different worlds, switch to different render modes, and view a list of online members.
Chat messages will be displayed at the bottom-left next to the hyperlink button.

On the top-left, you can click on a layer button to filter out certain objects.
Both options are enabled by default and deselecting either one will automatically update the render.
The `markers` option shows where spawnpoints are located and `players` identifies the location of all online members.

### Online chat
If the plugin is able to link your in-game address with that of your connection to Dynmap, you can send and receive messages.
You'll be able to communicate (read and view in-game messages) as if you were on the server through the comfort of a webpage.

Dynmap-sent messages can be distinguished by the `[WEB]` prefix that precedes anything sent through the interface.
Messages sent by members in-game can also show display a text bubble relative to their position on the map; you must be viewing the respective map to use this feature.

### Other information
At the top-center, it will display the Minecraft world-specific time along with an animated representation.
Under the filters button, it will show the world coordinates in relation to where your cursor is located.
The top-right image will display a compass for directional reference.

## Resource pack
Our server uses a custom resource pack that gives builders the ability to add more detail in their creations.
We recommend that all members have it installed.

### Downloading
If the server does not notify you to install the resource pack automatically, you can download and apply it manually.
The resource pack is an open-source project and we use a repository for easy editing and the ability to quickly make changes; from which you can [obtain](https://github.com/shadowga/resourcepack/archive/master.zip) the latest version.

### Installation
After successfully downloading the resource pack, you can install and activate it normally.
It may take up to a minute for your game to initialize the textures, and then you should be returned to the options menu.
You have now completed all the steps and your resource pack should be working.
