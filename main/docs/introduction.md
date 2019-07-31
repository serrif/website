---
title: Introduction
permalink: /docs/

layout: info
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
    href: '#other-commands'
  -
  - text: "Website"
    href: '#website'
  - text: "₍₁₎ Homepage"
    href: '#homepage'
  - text: "₍₂₎ Social media"
    href: '#social-media'
  - text: "₍₃₎ Server blog"
    href: '#server-blog'
  -
  - text: "Discord"
    href: '#discord'
  - text: "₍₁₎ Channels"
    href: '#channels'
  - text: "₍₂₎ Roles"
    href: '#roles'
  - text: "₍₃₎ Applications"
    href: '#applications'
---

## In-game server
Our <a class="usa-external_link" href="https://minecraft.net">Minecraft</a> server is the keystone to our community. Everyone gets operator-style permissions without hassle, with an array of plugins, and powerful tools for building and management.

### Connection
Joining the server is simple. You can connect using the address `novelmc.net` or `play.novelmc.net` through the direct connect box; or by adding us to your server list in-game. A port isn't necessary to join,  but `25565` can be added to an address.

 * `/status` - Displays the server's current state and loaded worlds.
 * `/memory` or `/mem` - Displays memory statistics, loaded worlds, and ticks per second (TPS).

You can also view and lookup other members, instead of the default tab list.

<div class="usa-alert usa-alert-warning" >
  <div class="usa-alert-body">
    <p class="usa-alert-text">Many in-game commands that show information specific to members will only apply to players on the server when the command was sent. Make sure to be accurate when using these commands.</p>
  </div>
</div>

 * `/list` - Displays a list of members currently on the server. Also distinguishes online staff members.
 * `/whois <name>` - Provides advanced information regarding a member.
 * `/realname <name>` - Finds a member's username from their nickname (if they have one).

Nearby members can be located with a few proximity commands.

 * `/radar` - Displays a list of nearby members and their proximity to you.
 * `/nearby`  or `/near` - An Essentials-based variant of the above command, tracks proximity.

We currently only support Minecraft for `1.14.3`. As the game updates, our support for older versions may change.

### Communication
Besides the chat, we offer other features to take advantage of messaging, with additional features, though a variety of different commands. We use the <a class="usa-external_link" href="http://wiki.mc-ess.net/wiki/Command_Reference">Essentials</a> features library along with several other plugins for additional functionality.

 * `/me <text>` - Globally announces the specified text. Supports formatting codes.
 * `/msg <user> <text>` - Privately sends a message (`<text>`) to another member (`<user>`).
 * `/mail` - Serves as an in-game mailbox. Messages can be sent to other members.

#### Mail usage
The `/mail` function can be used to send, receive, and manage messages. All messages sent must follow [our guidelines](../docs/policy) or they'll be removed.

<div class="usa-alert usa-alert-info" >
  <div class="usa-alert-body">
    <p class="usa-alert-text">Mailed messages can be sent to offline members—or members that aren't currently on the server when the command is sent. <code class="highlighter-rouge">/mail sendall</code> is for staff member use only.</p>
  </div>
</div>

 * `/mail send <user> <message>` - Mails a message to another member (`<user>`).
 * `/mail read` - Functions as an inbox; displays all (if any) messages sent to you.
 * `/mail clear` - Clears your inbox; deletes all (if any) messages sent to you.

### Other commands
Members can also manage settings of their character; such as gamemode, and health-based damage.

<ul>
  <li><code class="highlighter-rouge">/gamemode &lt;creative | survival | adventure | spectator&gt;</code> - Sets your gamemode.</li>
  <li><code class="highlighter-rouge">/gmc</code> <code class="highlighter-rouge">/gms</code> <code class="highlighter-rouge">/gma</code> <code class="highlighter-rouge">/gmsp</code> - Alias(es); they set your gamemode, specifically.</li>
</ul>
<ul>
  <li><code class="highlighter-rouge">/heal</code> - Resets your health and hunger, if affected.</li>
  <li><code class="highlighter-rouge">/god [on | off]</code> - Without arguments, toggles damage immunity.</li>
</ul>

## Website
Our website provides important information as the center of our community's operation; housing our explore pages, resources, and information. Learning how we structure different sections of our site is helpful for knowing how to get around.

### Homepage
Our homepage is the forefront to `novelmc.net` —with its features builds, and the 🌊. Other pages apart from our homepage (such as our team page) can provide material. These and similar files are powered by <a class="usa-external_link" href="https://pages.github.com/">GitHub Pages</a> and the <a class="usa-external_link" href="https://designsystem.digital.gov/">U.S. Web Design System</a>.

We provide instructions, policy, and guides on our documentation; so everyone can learn how things work. You're even reading a docs page right now, and you can jump to pages with the left-hand navigation table.

<div class="usa-alert usa-alert-info" >
  <div class="usa-alert-body">
    <p class="usa-alert-text">We use information cards in our documentation pages to highlight upcoming important information. Warning cards are also used for temporary information alerts.</p>
  </div>
</div>

Everyone should read our documentation carefully to familiarize themselves with server procedure and policy. Information also helps with using the advanced (and exclusive) features of our server, and other resources.

### Social media
Social media is used for brief updates to our members. We have a <a class="usa-external_link" href="../twitter/">Twitter</a> for updating our members on what's happening.

Our <a class="usa-external_link" href="../github/">GitHub</a> organization is used for development for all of our projects, including this website.

### Server blog
The [server blog](../blog/) is used for more specific updates of everything that's going on behind the scenes. We save new blog posts for information that's really important, though, so you won't be doing too much reading.

## Discord
Our online <a class="usa-external_link" href="https://discordapp.com">Discord</a> server is an easy-to-use branch of our community where anyone can talk in real time. This service is great for sharing content, and for quick support. Anyone can [join](/discord/).

### Channels
We have text and voice channels that everyone in the community to use. We separate a few discussion streams into separate channels to keep conversations more organized.

 * [`#announcements`](https://discord.gg/nuNTR3U) - For important stuff; updates, and server news. Only Executives can send messages here.
 * [`#github`](https://discord.gg/TY5Jw2C) - GitHub organization activity log.
 * [`#public-logs`](https://discord.gg/hmKEtH9) - Where all moderation actions log.

The following channels can be used by anyone who isn't muted or removed.

 * [`#general`](https://discord.gg/vXydQmT) - For any and all discussions without a specific channel.
 * [`#support`](https://discord.gg/hGFsCkx) - For any and all things server development.
 * [`#nonsense`](https://discord.gg/FdBymjx) - Messages that are purposeless or spam.
 * [`#ouija`](https://discord.gg/45D83Ct) - Ask Ouija anything.

### Roles
We use Discord's role system to designate and separate members on the server; meaning that some roles will have no server or forum counterpart.

---

<div style="text-align: center; margin-top: 15px;"><img src="https://novelmc.net/assets/img/svg/titles.svg"></div>

---

<div class="usa-alert usa-alert-info" >
  <div class="usa-alert-body">
    <p class="usa-alert-text">There are only our server's titles. Our ranks are listed on our <a href="../docs/authority">authority documentation</a>.</p>
  </div>
</div>

 * **Architects** - Awarded to exemplary builders on the server.
 * **Bots** - Given to all [robots](../docs/#applications).
 * **Verified** - Given to active, and well-known server members.

The following titles are given to staff members only.

 * **Inactive** - Given to staff members to show inactivity; by request.

### Applications
We use bots to manage our server members, its moderation, and to add additional features.  

 * `/` - Displays a pop-up menu listing the built-in commands on Discord.
 * `!help` - Displays a list of the <a class="usa-external_link" href="https://rythmbot.co/">Rythm</a> bot's commands via its website.
 * `~help` - Displays a list of the <a class="usa-external_link" href="https://auttaja.io/">Auttaja</a> bot's commands.
 * `s?help` - Displays a list of the <a class="usa-external_link" href="https://statbot.net">Statbot</a> bot's commands.

---

Other commands and information; including in-game features, resources, and tools are outline further in documentation pages.
