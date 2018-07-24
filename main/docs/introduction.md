---
title: Introduction
permalink: /docs/

layout: post
sidenav: docs
subnav:
  - text: "In-game server"
    href: '#in-game-server'
  - text: "* Connection"
    href: '#connection'
  - text: "* Communication"
    href: '#communication'
  - text: "** Mail usage"
    href: '#mail-usage'
  - text: "* Economy"
    href: '#economy'
  - text: "** Using the shop"
    href: '#using-the-shop'
---

We're a modern creative environment; we give members every command they need to powerfully build and enjoy our server without meeting any requirements.
{: .usa-font-lead }

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
 
You can also view and lookup other members, as opposed to the default tab list.

<div class="usa-alert usa-alert-warning" >
  <div class="usa-alert-body">
    <p class="usa-alert-text">Many in-game commands with member-specific variables will only apply to those connected during the execution of your command, making specificity imperative.</p>
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
We use the [Essentials](https://wiki.mc-ess.net) features library along with several other plugins.

 * `/me <text>` - Globally announces the specified text for all to see.
 * `/msg <user> <text>` - Privately sends a message (`<text>`) to another member (`<user>`).
 * `/mail` - Serves as an in-game mailbox. Messages can be sent to other members.
 
#### Mail usage
The `/mail` function can be used to send, receive, and manage messages.
Keep in mind that all messages must comply with our guidelines or they'll be removed.

> **Note:** Mailed messages, unlike `/msg`, can be sent to offline members—or members that aren't currently on the server during command execution. `/mail sendall` cannot be used by members.

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

> **Note:** Only remove or 'set' coins with the permission of an Executive or higher. Giving out coins can potentially unbalance the server economy, resulting in inflation.

 * `/manageshop coins add <amount> <user | all>` - Gives an amount of coins to someone.
 * `/manageshop coins remove <amount> <user | all>` - Takes away an amount of coins.
 * `/manageshop coins set <amount> <user | all>` - Sets a definite amount of coins.
 
The `all` function will only apply to members that are online; `set` will override pre-existing coins.

### Other commands
Members can manage settings directly pertinent to their character; such as gamemode and immunity to health-based damage.

> **Note:** Currently, spectator mode is only available to administrators. This restriction is in place to maintain privacy and prevent unwanted activity.

<ul>
  <li><code class="highlighter-rouge">/gamemode &lt;creative | survival | adventure | spectator&gt;</code> - Sets your gamemode.</li>
  <li><code class="highlighter-rouge">/gmc</code> <code class="highlighter-rouge">/gms</code> <code class="highlighter-rouge">/gma</code> <code class="highlighter-rouge">/gmsp</code> - Alias(es); they set your gamemode, specifically.</li>
</ul>
<ul>
  <li><code class="highlighter-rouge">/heal</code> - If affected by damage, resets your health and hunger.</li>
  <li><code class="highlighter-rouge">/god [on | off]</code> - Without arguments, toggles damage immunity.</li>
</ul>

## Website
The website provides fundamentals; such as information, referrals, and resources.
It's also great to master these tools, and you can start by learning how we commit different sections.

### Homepage
Our homepage is the first page enveloping `shadow.ga`—you know, with the funny text and big red mountains.
Other pages branching from our homepage (such as error pages) can provide material.
This and akin files are powered by [Jekyll](https://jekyllrb.com/) and [Flarum](http://flarum.org/).

We provide guidelines, instructions, and guides on our documentation; so newcomers can learn with ease.
You're even reading a docs page right now and you can jump to pages with the left-hand table.

> **Notes** and **tips** like this one signify knowledge that isn't necessarily definite but important. **Upcoming** blocks detail assets we're still trying to implement—also subject to revision.

Everyone should thoroughly read our documentation so they know how to get around.
Information also helps with using the exclusive features of our server, forum, and other resources.

### Social media
Social media is used for communicating announcements and other important information.
We have a [Twitter](/twitter/) for sending quick messages and all tweets are relayed to the guild in #announcements.

Our [GitHub](/github/) organization is great for the open-source development of resources such as this website—and don't forget our Medium [blog](/blog/).

### Community
We'll often refer to our forum as the 'community' to keep things simple—a feature great for online collaboration and discourse.
Getting started on the community is nice and simple, we don't ask for much; anyone can sign up through our database or GitHub—but please [enable](https://shadow.ga/docs/2/d-security/#activating-two-factor-login) two-factor auth.

> **Note:** Account deletions can only be performed by an Executive or higher due to the action's severity. If you'd like your account deleted, please [contact us](https://shadow.ga/docs/1/d-support/#direct-support).

Discussions are thread-like posts that (when made) will show up on the community's front page.
When a discussion is getting a lot of replies, it'll stay on the front for everyone to see.
You can talk about anything on the community, but we have tags for organisation; be specific but don't abuse them.

## Guild
The guild is our Discord server where anyone can talk to each other in real time.
This service is great for sharing content, collaboration, and quick support; anyone can [join](/guild/), and it's linked to in the navigation bar.

### Channels
Text channels are the focus of our guild, along with voice channels.
We segregate our channels based on the subject they were constructed for; as a result, please keep things where they belong.

 * [`#announcements`](https://discord.gg/kpePHUP) - Executive-only channel for important stuff; updates, tweets, and articles.
 
The following channels can be used by anyone who isn't muted or removed.
 
 * [`#general-chat`](https://discord.gg/3fFF2V2) - Catalyst of 'normal' content—everyday and relevant talk.
 * [`#spam-chat`](https://discord.gg/k6RHq5N) - For content that's purposeless or has been designated as spam.
 * [`#dev-chat`](https://discord.gg/XQjuvt3) - The support hotline and place for development discussion.

Other channels that aren't listed here (such as admin-only channels) function limitedly; for more information, see the various channel topics.

### Position
The guild uses Discord's role system for standalone designation; meaning that some roles provided to members will have no server or forum counterpart.
These are called 'titles' because they carry no permissions (unlike ranks).

---

<div style="text-align: center; margin-top: 15px;"><img src="https://shadow.ga/img/svg/titles.svg"></div>

---

> **Note:** Only titles will be listed here, as the guild's ranking system is identical to that of our server; a list of administrator ranks can be found at our [hierarchy](https://shadow.ga/docs/2/a-directorate/#hierarchy).

 * **Developer** - Provided to those who make code contribution to our [organisation](https://github.com/shadowga).
 * **Architect** - Awarded to the prolific builders of our in-game atmosphere.
 
The following positions can only be granted to administrators.

 * **Inactive** - Attached to an inactive admin's account; provided upon request.
 * **Emeritus** - Attached to administrators designated as permanently active.
 
### Automation
We use bots to emulate a personal assistant for every member.
Bots have a wide variety of control and may cover customisation to specification.
They can't be used in-game.

 * `/` - Triggers a pop-up menu listing the built-in commands of our Discord guild.
 * `.help` - Provides a list of the [Some Dragon](https://github.com/robingall2910/RobTheBoat) bot's commands via a personal message.
 * `t!help` - Provides a list of the [Tatsumaki](https://www.tatsumaki.xyz/) bot's commands via a personal message.

---

Other commands and information; regarding in-game features, resources, and tools are further detailed appropriately.
You can either click the 'next' button or manually navigate to continue.
