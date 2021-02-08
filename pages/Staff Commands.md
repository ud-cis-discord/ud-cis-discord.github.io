---
waltz:
  title: Staff Commands
  resource: page
  published: false
layout: page
title: Staff Commands
permalink: staff_pages/staff%20commands
---
## Running Commands

As staff, you have access to some commands not listed in the general [commands page][29]. You run them the same as the
other commands, using `s;[command] [arguments]`in any channel that Sage is in, although we recommend running staff
commands in staff-only channels.

## The Commands

**roleinfo:**
The roleinfo command takes one argument: the name of any role available on the server. It will output the current
number of users with that role, as well as a list of those users. If the list is too long to be sent in an embed
message, it will be uploaded to pastebin and a link to the upload will be sent instead.

**lookup:**
The lookup command takes one argument: the name of any member of the server. It will output the given user's
verification status and current message count.

**resetlevel:**
The resetlevel command takes one argument: the name of any member of the server. It will adjust the message count and
level of the given user.

**mute:**
The mute command takes one argument: the name of any member of the server. It will give the user the 'muted' role and
take away their permission to send messages in the server, until the role is removed.

**warn:**
The warn command takes no arguments and is used by replying to a message. It sends a DM to a user with a warning about
breaking the rules and deletes the offending message.

## Question Tagging Commands

**addassignment:**
The addassignment command takes two arguments: a class ID and an assignment ID. The class ID will be 000, and the
assignment ID will be created once you use it with the command. It will add the assignment ID you chose to the settings
document so that students can create question tags with that assignmentID.

**sudoreply:**
The sudoreply command takes two arguments: a question ID and an answer. The question ID will be the same ID as the
question you are replying to, and your answer will be sent to the asker to the user's DMs via Sage.

   [29]: https://ud-cis-discord.github.io/pages/commands (Commands)