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
other commands, using `/<command name here>`in any channel that Sage is in, although we recommend running staff
commands in staff-only channels.

### Staff Commands

**addassignment**

- Description: Adds an assignment to a given course ID's assignment list

- Parameters:
  - course (required): The course ID to add an assignment to
  - newassignments (required): A | separated list of new assignments

**google**

- Description: Have Sage google something for someone

- Parameters:
  - query (required): What you'd like Sage to Google for someone!

**lookup**

- Description: Looks up information about a given user

- Parameters:
  - user (required): The member to look up

**mute**

- Description: Gives the muted role to the given user.

- Parameters:
  - user (required): The user to mute

**resetlevel**

- Description: Resets a given user's message count.

- More info: Using with no value will reset to 0. A positive integer will
	set their message count and a negative will subtract that from their total

- Parameters:
  - user (required): The user whose message count will be edited
  - value (optional): value to use (positive to set, negative to subtract, none to set to 0)

**roleinfo**

- Description: Gives information about a role, including a list of the members who have it.

- Parameters:
  - role (required): Role to get the info of

**sudoreply**

- Description: Reply to a question asked through Sage.

- More info: Responses are put into a private thread between you and the asker.

- Parameters:
  - questionid (required): ID of question you are replying to
  - response (required): Response to the question

**warn**

- Description: Warns a user for breaking the rules and deletes the offending message.

- More info: This command must be used when replying to a message.

- Parameters:
  - msglink (required): Link to the offending message
  - reason (optional): Reason for warning the user

**whois**

- Description: Gives an overview of a member's info.

- Parameters:
  - user (required): The user to lookup
[29]: https://ud-cis-discord.github.io/pages/commands (Commands)