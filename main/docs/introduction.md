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
  - text: "Website"
    href: '#website'
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
    <p class="usa-alert-text">Many in-game commands displaying member-specific information will only apply to those connected during when the command was sent. Make sure those commands are accurate and specific.</p>
  </div>
</div>

 * `/list` - Displays a list of members currently on the server.
 * `/list -s` - Displays a list of members, with staff privileges on the server.
 * `/whois <name>` - Provides advanced information regarding a member.
 * `/realname <name>` - Finds a member's username from their nickname (if they have one).

Nearby members can be located with a few of commands to determine member location.

 * `/radar` - Displays a list of nearby members and their proximity to you.
 * `/nearby`  or `/near` - An Essentials-based variant of the above command, tracks proximity.

Join us using the version that is favorite to you; from `1.8` to `1.13`. As the game updates, our support for older versions may change.

### Communication
Besides the chat, other forms of in-game communication can be utilized, with additional features, though a variety of different commands. We use the <a class="usa-external_link" href="http://wiki.mc-ess.net/wiki/Command_Reference">Essentials</a> features library along with several other plugins for additional functionality.

 * `/me <text>` - Globally announces the specified text. Supports formatting codes.
 * `/msg <user> <text>` - Privately sends a message (`<text>`) to another member (`<user>`).
 * `/mail` - Serves as an in-game mailbox. Messages can be sent to other members.

#### Mail usage
The `/mail` function can be used to send, receive, and manage messages. All messages sent must comply with our guidelines or they'll be removed.

<div class="usa-alert usa-alert-info" >
  <div class="usa-alert-body">
    <p class="usa-alert-text">Mailed messages can be sent to offline members—or members that aren't currently on the server when the command is sent. <code class="highlighter-rouge">/mail sendall</code> is reserved for staff member use.</p>
  </div>
</div>

 * `/mail send <user> <message>` - Mails a message to another member (`<user>`).
 * `/mail read` - Functions as an inbox; displays all (if any) messages sent to you.
 * `/mail clear` - Clears your inbox; deletes all (if any) messages sent to you.

### Other commands
Members can manage settings directly pertinent to their character; such as gamemode, and modifications to health-based damage.

<ul>
  <li><code class="highlighter-rouge">/gamemode &lt;creative | survival | adventure | spectator&gt;</code> - Sets your gamemode.</li>
  <li><code class="highlighter-rouge">/gmc</code> <code class="highlighter-rouge">/gms</code> <code class="highlighter-rouge">/gma</code> <code class="highlighter-rouge">/gmsp</code> - Alias(es); they set your gamemode, specifically.</li>
</ul>
<ul>
  <li><code class="highlighter-rouge">/heal</code> - Resets your health and hunger, if affected.</li>
  <li><code class="highlighter-rouge">/god [on | off]</code> - Without arguments, toggles damage immunity.</li>
</ul>

## Website
Our website provides essential information as the center of server operation; housing particulars, resources, and information. Learning how we commit different sections of our site is helpful for effective server navigation.

### Homepage
Our homepage encompasses `novelmc.net` —with its features builds, and the blue waves. Other pages branching from our homepage (such as our features gallery) can provide material. This and akin files are powered by the <a class="usa-external_link" href="https://designsystem.digital.gov/">U.S. Web Design System</a>.

We provide instructions, policy, and guides on our documentation; so everyone can learn with easily. You're even reading a docs page right now and you can jump to pages with the left-hand navigation table.

<div class="usa-alert usa-alert-info" >
  <div class="usa-alert-body">
    <p class="usa-alert-text">We use information cards in our documentation pages to signify upcoming important information. Warning cards are also used for developmental and provisional information.</p>
  </div>
</div>

Everyone should thoroughly read our documentation so they know how to get around and assist other users. Information also helps with using the advanced (and exclusive) features of our server, and other resources.

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
