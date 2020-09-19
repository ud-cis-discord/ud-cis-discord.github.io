---
layout: page
title: About the bot
permalink: /about-bot/
---
<link rel="icon" href="/favicon.ico" type="image/x-icon" />

Why have a bot, you ask? It makes life easier, That's why!
## Our lovely bot
***
Our bot, Sage is  built on top of the Klasa framework and the Discord.js library. Sage is custom-coded and is
actively maintained by Ben Segal and based on Steve Bot. Sage is a a general purpose Discord bot, with some added
functionality to make online learning easier. Sage has a bunch of cool commands you can read about below but that's
not all. Sage also keeps track of how many messages you send. However, commands and messages sent in channels with 
`[no message count]` in the channel topic wont increase your message count. This information is used by your
Professor to give you participation points. If you have an idea to improve Sage, you can send `s;suggest <your idea here>`
in a <span style="color:#738adb;">#sages_place</span> and it will be sent directly to the eyes of Ben. 

## Commands
***
Here is the list of all the commands that can be run. To run a command simply send `s;command` or `Sage, command`.
To get more information about any command simply send `s;help command`.

### General Commands
**help (aliases: commands, howtheheckdoiusethisbot)** Shows info about the bots commands.\
**levelcheck (aliases: check)** Shows how many messages you have sent.\
**whois (aliases: whoami, member)** Gives an overview of a member's info.\
**info** Provides some information about the bot.\
**ping** Runs a connection test to Discord.\
**stats** Provides some details about the bot and stats.\
**userconf** Define per-user settings.\
**assign** Assign or unassign roles to yourself!\
**nominate** Nominate someone to be a Skilled User.

### Information Commands
**discstatus (aliases: discordstatus, isdiscordbroke)** Gets the current status of Discord from [status.discord.com](https://status.discord.com/ "Why not check it now")\
**google** Search Google for a phrase.\
**markdown** Gives information on how to use Markdown in Discord.\
**roleinfo (aliases: membersin)** Gives information about a role, including a list of the members who have it.\
**serverinfo** Gives useful information about the server.\
**snippets (aliases: snippet, snip)** Easily access useful bits of information about the server.\
**verify** Verifies a user.\
**rules** Shows a rule.

### Fun Commands
**remind (aliases: remindme)** Set personal reminders for yourself.\
**myreminders (aliases: reminders)** View or cancel your pending reminders.\
**pomodoro (aliases: pomo, pom)** Be productive with the pomodoro technique!\
**rockpaperscissors (aliases: rps)** Play rock, paper, scissors against the bot.\
**f** Press F to pay respects.\
**doubt (aliases: x)** Press X to doubt.\
**nice** Nice.\
**8ball** Ask the 8ball a question and you shall get an answer.\
**rate** Have the bot rate something of your choosing.\
**roll** Roll dice!\
**poll (aliases: vote)** Have the bot create a poll for you.

### Moderation Commands (only useable by staff unless noted otherwise)
**nick** Changes a member's nickname.\
**role** Adds or removes a role from a member.\
**mute** Adds the server's muted role to the specified member.\
**unmute** Removes the server's muted role from the specified member.\
**kick** Kicks a member from the server.\
**ban (only useable to admin level users)** Bans a member from the server.\
**unban (only useable to admin level users)** Unbans a user.\
**lookup** Looks up a users verification information and message count.\
**resetlevel** Resets a users message count.\
**lock** Locks a channel from public posting.\
**unlock** Unlocks a channel.\
**slow** Sets the message rate limit for a channel.\
**purge** Bulk deletes messages from a channel.\
**pins** Tells how many messages are currently pinned in a channel.\
**case** View a specific case using the case number.\
**reason** Edit the reason field for a case.\
**timer** Add a timer to a moderation case.\
**permissions (aliases: perms)** View the permissions of the specified member.\
**report (aliases: export, getcsv)** Generates a report of user messages

### Admin Commands (only useable by bot owner unless noted otherwise)
**enable** Re-enables or temporarily enables a command/inhibitor/monitor/finalizer. Default state restored on reboot.\
**disable** Re-disables or temporarily disables a command/inhibitor/monitor/finalizer/event. Default state restored on reboot.\
**eval (aliases: ev)** Evaluates arbitrary JavaScript. Extraordinary powerful and dangerous.\
**load** Load a piece from the bot.\
**unload** Unloads the klasa piece.\
**reload** Reloads a klasa piece, or all pieces of a klasa store.\
**transfer** Transfers a core piece to its respective folder.\
**conf (available to all admin level users)** Define per-guild settings.\
**reboot** Reboots the bot
