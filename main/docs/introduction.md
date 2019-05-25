---
title: Introduction
permalink: /docs/

layout: post
sidenav: docs
subnav:
  - text: "In-game server"
    href: '#in-game-server'
  - text: "₍₁₎ Connection"
    href: '#connection'
  - text: "₍₂₎ Communication"
    href: '#communication'
  - text: "₍₂ₐ₎ Mail usage"
    href: '#mail-usage'
  - text: "₍₃₎ Other commands"
    href: '#economy'
  -
  - text: "Web services"
    href: '#web-services'
  - text: "₍₁₎ Homepage"
    href: '#homepage'
  - text: "₍₂₎ Social media"
    href: '#social-media'
  -
  - text: "Guild"
    href: '#guild'
  - text: "₍₁₎ Channels"
    href: '#channels'
  - text: "₍₂₎ Roles"
    href: '#roles'
  - text: "₍₃₎ Applications"
    href: '#applications'
---

"We give members every command they need to powerfully build and enjoy our server without meeting any requirements."
{: .usa-font-lead }

Permissions are developed in accordance with our commitment towards freedom.
<br>
If something's blocked or off-limits that you think shouldn't be, please let us know.

<hr style="margin-top: 3rem;">

## In-game server
Our <a class="usa-external_link" href="https://minecraft.net">Minecraft</a> server is the keystone to our community. We provide operator permissions for anyone without hassle, an assortment of plugins, and powerful tools for building and management.

### Connection
Joining the server is simple. You can connect using the address `novelmc.net` or `play.novelmc.net` through the direct connect box; or adding us to your server list in-game. Applying a port isn't necessary for connection  but `25565` can be appended to an address.

 * `/status` - Displays the server's current state and loaded worlds.
 * `/memory` or `/mem` - Displays memory statistics, loaded worlds, and ticks per second (TPS).

You can also view and lookup other members, as opposed to the default tab list.

<div class="usa-alert usa-alert-warning" >
  <div class="usa-alert-body">
    <p class="usa-alert-text">Many in-game commands displaying member-specific information will only apply to those connected during when the command was sent, making specificity imperative.</p>
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

We provide support for both newer and older clients, from `1.12.2` all the way back to `1.7.2`. Support for older client versions may change as the game updates.

### Communication
Besidies the chat, other forms of in-game communication can be utilised with a variety of different commands. We use the <a class="usa-external_link" href="http://wiki.mc-ess.net/wiki/Main_Page">Essentials</a> features library along with several other plugins.

 * `/me <text>` - Globally announces the specified text for all to see.
 * `/msg <user> <text>` - Privately sends a message (`<text>`) to another member (`<user>`).
 * `/mail` - Serves as an in-game mailbox. Messages can be sent to other members.

#### Mail usage
The `/mail` function can be used to send, receive, and manage messages.
Keep in mind that all messages must comply with our guidelines or they'll be removed.

<div class="usa-alert usa-alert-info" >
  <div class="usa-alert-body">
    <p class="usa-alert-text">Mailed messages, such as <code class="highlighter-rouge">/msg</code>, can be sent to offline members—or members that aren't currently on the server during command execution. <code class="highlighter-rouge">/mail sendall</code> cannot be used by members.</p>
  </div>
</div>

 * `/mail send <user> <message>` - Mails a message to another member (`<user>`).
 * `/mail read` - Functions as an inbox; displays all (if any) messages sent to you.
 * `/mail clear` - Clears your inbox; deletes all (if any) messages sent to you.

### Other commands
Members can manage settings directly pertinent to their character; such as gamemode and immunity to health-based damage.

<div class="usa-alert usa-alert-info" >
  <div class="usa-alert-body">
    <p class="usa-alert-text">Currently, spectator mode is only available to administrators. This restriction is in place to maintain privacy and prevent unwanted activity.</p>
  </div>
</div>

<ul>
  <li><code class="highlighter-rouge">/gamemode &lt;creative | survival | adventure | spectator&gt;</code> - Sets your gamemode.</li>
  <li><code class="highlighter-rouge">/gmc</code> <code class="highlighter-rouge">/gms</code> <code class="highlighter-rouge">/gma</code> <code class="highlighter-rouge">/gmsp</code> - Alias(es); they set your gamemode, specifically.</li>
</ul>
<ul>
  <li><code class="highlighter-rouge">/heal</code> - If affected by damage, resets your health and hunger.</li>
  <li><code class="highlighter-rouge">/god [on | off]</code> - Without arguments, toggles damage immunity.</li>
</ul>

## Web services
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

## Guild
The guild is our <a class="usa-external_link" href="https://discordapp.com">Discord</a> server where anyone can talk to each other in real time.
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

### Roles
The guild uses Discord's role system for standalone designation; meaning that some roles provided to members will have no server or forum counterpart.
These are called 'titles' because they carry no permissions (unlike ranks).

---

<div style="text-align: center; margin-top: 15px;"><img src="https://shadow.ga/img/svg/titles.svg"></div>

---

<div class="usa-alert usa-alert-info" >
  <div class="usa-alert-body">
    <p class="usa-alert-text">Only titles will be listed here, as the guild's ranking system is identical to that of our server; a list of administrator ranks can be found at our hierarchy.</p>
  </div>
</div>

 * **Developer** - Provided to those who make code contribution to our <a class="usa-external_link" href="https://github.com/shadowga">organisation</a>.
 * **Architect** - Awarded to the prolific builders of our in-game atmosphere.

The following positions can only be granted to administrators.

 * **Inactive** - Attached to an inactive admin's account; provided upon request.
 * **Emeritus** - Attached to administrators designated as permanently active.

### Applications
We use bots to emulate a personal assistant for every member.
Bots have a wide variety of control and may cover customisation to specification.
They can't be used in-game.

 * `/` - Triggers a pop-up menu listing the built-in commands of our Discord guild.
 * `.help` - Provides a list of the <a class="usa-external_link" href="https://github.com/robingall2910/RobTheBoat">Some Dragon</a> bot's commands via a personal message.
 * `t!help` - Provides a list of the <a class="usa-external_link" href="https://www.tatsumaki.xyz/">Tatsumaki</a> bot's commands via a personal message.

---

Other commands and information; regarding in-game features, resources, and tools are further detailed appropriately.
