---
title: Documentation
permalink: /docs/

layout: post
sidenav: docs
subnav:
  - text: In-game server
    href: '#in-game-server'
  - text: Website
    href: '#website'
  - text: Guild
    href: '#guild'
---

# Introduction

We're a modern creative environment; we give members every command they need to powerfully build and enjoy our server without meeting any requirements.

## In-game server
Our Minecraft server is what we're built around.
We provide operator permissions for anyone without hassle, an assortment of plugins, and powerful tools for building and administration.

### Connection
It's easy to join the server.
You can connect using the domain `shadow.ga` (SRV, default) or `a.shadow.ga` (A) as a server address using the direct connect box; or by adding us to your in-game list.
Using a port isn't required but if you need one there's `25565`.

 * `/status` - Displays the server's current state and loaded worlds.
 * `/memory` - Projects memory statistics, loaded worlds, and ticks per second (TPS).
 * `/mem` - An alias of the previous command and serves the same function.
 
You can also view and lookup other members, as opposed to the tab list.

<div class="usa-alert usa-alert-info" >
  <div class="usa-alert-body"><p class="usa-alert-text">Many in-game commands with member-specific variables will only apply to those connected during the execution of your command, making specificity imperative.</p>
  </div>
</div>

 * `/list` - Displays a list of members currently on the server.
 * `/list -a` - Displays a list of members, with administrator, on the server.
 * `/whois <name>` - Provides advanced information regarding a member.
 * `/realname <name>` - Finds a member's username from their nickname (if they have one).
 
Nearby members can be located with a couple of proximity-sensing commands.

 * `/radar` - Displays a list of nearby members and their proximity to you.
 * `/nearby` - An Essentials-based variant of the above command, tracks proximity.
 * `/near` - An alias of the previous command and serves the same function.

We provide support for both newer and older clients, from `1.12.2` all the way back to `1.7.2`.
Support for older client versions may change as the game updates.

### Communication
Besidies the chat, other forms of in-game communication can be utilised with a variety of different commands.
We use the <a class="usa-external_link" href="https://wiki.mc-ess.net">Essentials</a> features library along with several other plugins.

 * `/me <text>` - Globally announces the specified text for all to see.
 * `/msg <user> <text>` - Privately sends a message (`<text>`) to another member (`<user>`).
 * `/mail` - Serves as an in-game mailbox. Messages can be sent to other members.
 
#### Mail usage
The `/mail` function can be used to send, receive, and manage messages.
Keep in mind that all messages must comply with our guidelines or they'll be removed.

<div class="usa-alert usa-alert-info" >
  <div class="usa-alert-body"><p class="usa-alert-text">Mailed messages, unlike `/msg`, can be sent to offline members—or members that aren't currently on the server during command execution. `/mail sendall` cannot be used by members.</p>
  </div>
</div>

 * `/mail send <user> <message>` - Mails a message to another member (`<user>`).
 * `/mail read` - Functions as an inbox; displays all (if any) messages sent to you.
 * `/mail clear` - Clears your inbox; deletes all (if any) messages sent to you.

### Economy
With an economy, members are capable of making transactions for shop items and developing their own wealth.
Money is presented in the form of coins and you can manage them.

#### Using the shop
To earn coins, you can [vote](https://www.planetminecraft.com/server/shadowrealms---a-server-where-everyone-gets-op/vote/) for the server and complete in-game chat reactions.
Once you build up enough coins, you can purchase from the shop; items like login messages and weapons.
 
 * `/coins` - Displays your current wealth; coins attributed to your user.
 * `/shop` - Opens up the shop. From here you can purchase items.
 
#### Shop management
Senior Admins and higher can manage the shop with an administrator tool.
Shop management allows for economy modification and the addition of new coins.

<div class="usa-alert usa-alert-warning" >
  <div class="usa-alert-body"><p class="usa-alert-text">Only remove or 'set' coins with the permission of an Executive or higher. Giving out coins can potentially unbalance the server economy, resulting in inflation.</p>
  </div>
</div>

 * `/manageshop coins add <amount> <user | all>` - Gives an amount of coins to someone.
 * `/manageshop coins remove <amount> <user | all>` - Takes away an amount of coins.
 * `/manageshop coins set <amount> <user | all>` - Sets a definite amount of coins.
 
The `all` function will only apply to members that are online; `set` will override pre-existing coins.

## Website
The website provides fundamentals; such as information, referrals, and resources.
It's also great to master these tools, and you can start by learning how we commit different sections.

### Homepage
Our homepage is the first page enveloping `shadow.ga`—you know, with the funny text and big red mountains.
Other pages branching from our homepage (such as error pages) can provide material.
This and akin files are powered by <a class="usa-external_link" href="https://jekyllrb.com/">Jekyll</a> and <a class="usa-external_link" href="http://flarum.org/">Flarum</a>.

We provide guidelines, instructions, and guides on our documentation; so newcomers can learn with ease.
You're even reading a docs page right now and you can jump to pages with the left-hand table.

Everyone should thoroughly read our documentation so they know how to get around.
Information also helps with using the exclusive features of our server, forum, and other resources.

### Social media
Social media is used for communicating announcements and other important information.
We have a <a class="usa-external_link" href="https://twitter.com/shadowgadev">Twitter</a> for sending quick messages and all tweets are relayed to the guild in #announcements.

Our <a href="github.com/shadowga">GitHub</a> organization is great for the open-source development of resources such as this website—and don't forget our <a href="../periodical/">periodical</a>.

### Community
We'll often refer to our forum as the 'community' to keep things simple—a feature great for online collaboration and discourse.
Getting started on the community is nice and simple, we don't ask for much; anyone can sign up through our database or GitHub—but [enable](https://shadow.ga/docs/2/d-security/#activating-two-factor-login) two-factor auth.

<div class="usa-alert usa-alert-warning" >
  <div class="usa-alert-body"><p class="usa-alert-text">Account deletions can only be performed by an Executive or higher due to the action's severity. If you'd like your account deleted, please <a href="https://shadow.ga/docs/1/d-support/#direct-support">contact us</a>.</p>
  </div>
</div>

Discussions are thread-like posts that (when made) will show up on the community's front page.
When a discussion is getting a lot of replies, it'll stay on the front for everyone to see.
You can talk about anything on the community, but we have tags for organisation; be specific, no abuse.

## Guild
The guild is our Discord server where anyone can talk to each other in real time.
This service is great for sharing content, collaboration, and quick support; anyone can [join](/guild/), and it's linked to in the navigation bar.

### Channels
Text channels are the focus of our guild, along with voice channels.
We segregate our channels based on the subject they were constructed for; as a result, please keep things where they belong.

 * <a class="usa-external_link" href="https://discord.gg/kpePHUP">`#announcements`</a> - Executive-only channel for important stuff; updates, tweets, and articles.
 
The following channels can be used by anyone who isn't muted or removed.
 
 * <a class="usa-external_link" href="https://discord.gg/3fFF2V2">`#general-chat`</a> - Catalyst of 'normal' content—everyday and relevant talk.
 * <a class="usa-external_link" href="https://discord.gg/k6RHq5N">`#spam-chat`</a> - For content that's purposeless or has been designated as spam.
 * <a class="usa-external_link" href="https://discord.gg/XQjuvt3">`#dev-chat`</a> - The support hotline and place for development discussion.

Other channels that aren't listed here (such as admin-only channels) function limitedly; for more information, see the various channel topics.

### Position
The guild uses Discord's role system for standalone designation; meaning that some roles provided to members will have no server or forum counterpart.
These are called 'titles' because they carry no permissions (unlike ranks).

---

<div style="text-align: center; margin-top: 15px;"><img src="https://shadow.ga/img/svg/titles.svg"></div>

---

<div class="usa-alert usa-alert-info" >
  <div class="usa-alert-body"><p class="usa-alert-text">Only titles will be listed here, as the guild's ranking system is identical to that of our server; a list of administrator ranks can be found at our <a href="https://shadow.ga/docs/2/a-directorate/#hierarchy">hierarchy</a>.</p>
  </div>
</div>

 * **Developer** - Provided to those who make code contribution to our <a href="https://github.com/shadowga">organisation</a>.
 * **Architect** - Awarded to the prolific builders of our in-game atmosphere.
 
The following positions can only be granted to administrators.

 * **Inactive** - Attached to an inactive admin's account; provided upon request.
 * **Emeritus** - Attached to administrators designated as permanently active.
 
### Automation
We use bots to emulate a personal assistant for every member.
Bots have a wide variety of control and may cover customisation to specification.
They can't be used in-game.

 * `/` - Triggers a pop-up menu listing the built-in commands of our Discord guild.
 * `.help` - Provides a list of the <a class="usa-external_link" href="https://github.com/robingall2910/RobTheBoat">Some Dragon</a> bot's commands via a personal message.
 * `t!help` - Provides a list of the <a class="usa-external_link" href="https://www.tatsumaki.xyz/">Tatsumaki</a> bot's commands via a personal message.

---

Other commands and information; regarding in-game features, resources, and tools are further detailed appropriately.
