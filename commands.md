# Lyno Server Manager Bot

A powerful, feature-rich Discord bot for server management, moderation, utility, music, tickets, anti-nuke, and more. This README covers all commands, their usage, and what each does.

---

## Table of Contents
- [Getting Started](#getting-started)
- [Commands](#commands)
  - [Moderation](#moderation)
  - [Utility](#utility)
  - [Music](#music)
  - [Tickets](#tickets)
  - [Anti-Nuke](#anti-nuke)
  - [Admin & Settings](#admin--settings)
  - [Info](#info)
  - [Greet](#greet)
  - [Jail System](#jail-system)
  - [Role Management](#role-management)
- [Notes](#notes)

---

## Getting Started
1. Purchase **lyno** from [here](<https://discord.gg/lyno>)
2. Invite **lyno** from [here](<https://discord.com/oauth2/authorize?client_id=1383277403748565032&permissions=8&scope=bot+applications.commands>)
3. Check out these commands and there will be more for future updates.

---

## Commands

### Moderation
| Command | Usage | Description |
|---------|-------|-------------|
| `ban` | `,ban @user [days] [reason]` | Ban a user, optionally deleting message history. |
| `kick` | `,kick @user [reason]` | Kick a user from the server. |
| `unban` | `,unban user#discrim or userID [reason]` | Unban a user by name or ID. |
| `mute` | `,mute @user [duration] [reason]` | Temporarily mute a user (adds Muted role). |
| `unmute` | `,unmute @user` | Remove Muted role from a user. |
| `timeout` | `,timeout @user <duration> [reason]` | Timeout a user for a set duration. |
| `warn` | `,warn @user [reason]` | Warn a user. |
| `warns` | `,warns @user` | List warnings for a user. |
| `clearwarn` | `,clearwarn @user` | Clear all warnings for a user. |
| `clear`/`purge`/`p` | `,clear <amount>` | Delete a number of messages. |
| `lock` | `,lock [#channel]` | Lock a text channel. |
| `unlock` | `,unlock [#channel]` | Unlock a text channel. |
| `censorword` | `,censorword <word>` | Add a word to the censor list. |
| `uncensorword` | `,uncensorword <word>` | Remove a word from the censor list. |
| `listcensor` | `,listcensor` | List all censored words. |
| `antilink` | `,antilink [mode]` | Enable/disable anti-link protection. |

### Utility
| Command | Usage | Description |
|---------|-------|-------------|
| `snipe` | `,snipe [index]` | Retrieve recently deleted messages. |
| `giveaway` | `,giveaway <prize> <time> [winners] [@host]` | Start a giveaway. |
| `giveaway reroll` | `,giveaway reroll [message_id]` | Reroll giveaway winners. |
| `ping` | `,ping` | Show bot latency. |
| `avatar` | `,avatar [@user]` | Show a user's avatar. |
| `roles` | `,roles [@user]` | List all roles of a user. |
| `joined` | `,joined [@user]` | Show when a user joined. |
| `created` | `,created [@user]` | Show when a user's account was created. |
| `botinfo` | `,botinfo` | Show bot statistics. |
| `invite` | `,invite` | Get the bot's invite link. |
| `membercount` | `,membercount` | Show server member stats. |
| `uptime` | `,uptime` | Show how long the bot has been online. |
| `autoreply` | `,autoreply trigger | reply` | Set or remove an auto-reply. |
| `ticket_panel` | `,ticket_panel` | Show the ticket panel for users. |
| `ticket_setup` | `,ticket_setup` | Configure ticket system. |
| `statusrole` | `,statusrole <keyword> @role` | Assign a role based on user status. |
| `removestatusrole` | `,removestatusrole <keyword>` | Remove a status role. |
| `reactionrole` | `,reactionrole <emoji> @role <message>` | Set up a reaction role. |
| `boostsetup` | `,boostsetup #channel @role <title> <desc> [color]` | Set up a boost reward panel. |
| `autorole` | `,autorole @role` | Set a role to auto-assign to new members. |
| `statusrole_scan` | `,statusrole_scan` | Scan for users matching status roles. |
| `nuke` | `,nuke` | Bulk delete all messages in a channel. |

### Music
| Command | Usage | Description |
|---------|-------|-------------|
| `play` | `,play <query>` | Play music in a voice channel. |
| `stop` | `,stop` | Stop music and clear the queue. |
| `continue_`/`resume` | `,continue_` | Resume paused music. |
| `loop` | `,loop` | Toggle looping the current song. |
| `queue` | `,queue` | Show the current music queue. |
| `volume` | `,volume [value]` | Set or show the music volume. |
| `skip` | `,skip` | Skip the current song. |

### Tickets
| Command | Usage | Description |
|---------|-------|-------------|
| `ticket_panel` | `,ticket_panel` | Show the ticket panel for users. |
| `ticket_setup` | `,ticket_setup` | Configure ticket system. |

### Anti-Nuke
| Command | Usage | Description |
|---------|-------|-------------|
| `antinuke` | `,antinuke` | Anti-nuke command group. |
| `antinuke setup` | `,antinuke setup #channel [action]` | Set up anti-nuke protection. |
| `antinuke admin` | `,antinuke admin @user` | Add a user as anti-nuke admin. |
| `antinuke admins` | `,antinuke admins` | List anti-nuke admins. |
| `antinuke info` | `,antinuke info` | Show anti-nuke config. |
| `antinuke disable` | `,antinuke disable` | Disable anti-nuke. |
| `antinuke channel` | `,antinuke channel` | Configure protected channels. |
| `antinuke bot` | `,antinuke bot` | Configure protected bots. |
| `antinuke role` | `,antinuke role` | Configure protected roles. |
| `antinuke ban` | `,antinuke ban` | Configure ban protection. |
| `antinuke kick` | `,antinuke kick` | Configure kick protection. |

### Admin & Settings
| Command | Usage | Description |
|---------|-------|-------------|
| `set_custom_prefix` | `,set_custom_prefix <prefix>` | Set a custom command prefix. |
| `say` | `,say <text>` | Make the bot say something (admin only). |
| `setupj2c` | `,setupj2c` | Set up Join to Create voice channels. |
| `whitelist` | `,whitelist <guild_id>` | Whitelist a server. |
| `unwhitelist` | `,unwhitelist <guild_id>` | Remove a server from whitelist. |
| `blacklist` | `,blacklist` | Blacklist command group. |
| `blacklist add` | `,blacklist add <user_id>` | Blacklist a user. |
| `blacklist remove` | `,blacklist remove <user_id>` | Remove a user from blacklist. |
| `blacklist list` | `,blacklist list` | List all blacklisted users. |

### Info
| Command | Usage | Description |
|---------|-------|-------------|
| `userinfo` | `,userinfo [@user]` | Show info about a user. |
| `serverinfo` | `,serverinfo` | Show info about the server. |
| `roleinfo` | `,roleinfo @role` | Show info about a role. |
| `channelinfo` | `,channelinfo [#channel]` | Show info about a channel. |

### Greet
| Command | Usage | Description |
|---------|-------|-------------|
| `greet` | `,greet` | Greet command group. |
| `greet setup` | `,greet setup <args>` | Set up greeting messages. |
| `greet enable` | `,greet enable` | Enable greeting messages. |
| `greet disable` | `,greet disable` | Disable greeting messages. |
| `greet info` | `,greet info` | Show greet config. |

### Jail System
| Command | Usage | Description |
|---------|-------|-------------|
| `jail` | `,jail` | Jail command group. |
| `jail info` | `,jail info` | Show jail config. |
| `jail release` | `,jail release @user` | Release a user from jail. |
| `jail_member` | `,jail @user [reason]` | Jail a user. |

### Role Management
| Command | Usage | Description |
|---------|-------|-------------|
| `role` | `,role` | Role management group. |
| `role create` | `,role create <name> [color] [icon] [hoist] [mentionable]` | Create a new role. |
| `role icon` | `,role icon :emoji: @role` | Set a role's icon. |
| `role delete` | `,role delete @role` | Delete a role. |
| `role add` | `,role add @user @role` | Add a role to a user. |
| `role user` | `,role user @user @role` | Alias for add. |

---

## Notes
- All commands use the default prefix `,` unless changed.
- Some commands require specific permissions (e.g., `ban_members`, `manage_guild`, `administrator`).
- For full details and advanced usage, see in-bot help: `,help [command]` or `/help`.
- For support, join the Discord server: [discord.gg/lyno](https://discord.gg/lyno)

---

**© copyright Lyno 2025, all rights reserved**
[Terms](<https://github.com/xcig/lyno/blob/main/tos.md>)
