---
waltz:
  title: Commands
  resource: page
  published: false
layout: page
title: Commands
permalink: pages/commands
---
Here is a list of all of the commands available for Sage, with the format `s;command [arguments]`.
<br>
Note, `[argument]` denotes an optional argument while `<argument>` denotes a required argument. Brackets should be omitted when running commands.
### General Commands

**check**

- Description: Displays the users current message count.

- Usage: `s;check `
### Configuration Commands

**togglelevelpings**

- Description: Toggles whether or not you will receive notifications from Sage on a level up.

- Usage: `s;togglelevelpings `


**togglepii**

- Description: Toggles whether your email (pii) will be sent to instructors over Discord.

- Usage: `s;togglepii `
### Fun Commands

**8ball**

- Description: Ask the 8-ball a question and you shall get an answer.

- Usage: `s;8ball `

- More info: This command requires you to put a question mark ('?') at the end of your message.


**blindfoldedroosen**

- Description: Challenge a blindfolded Prof. Roosen to a sword fight!

- Usage: `s;blindfoldedroosen `

- More info: You've been challenged to a sword fight. However, your opponent, Professor Roosen, has decided to wear a blindfold. Feeling lucky?


**coinflip**

- Description: Have Sage flip a coin for you!

- Usage: `s;coinflip `


**diceroll**

- Description: Get `numdice` random integers between `minimum` and `maximum`.

- Usage: `s;diceroll `

- More info: User specified minimum and maximum are inclusive. If no range is specified, defaults to one number ranging from 1 to 6.


**doubt**

- Description: Press X to doubt.

- Usage: `s;doubt `


**f**

- Description: Press F to pay respects.

- Usage: `s;f `


**latex**

- Description: Accepts a LaTeX expression and posts it as a rendered image.

- Usage: `s;latex `


**poll**

- Description: Have Sage create a poll for you.

- Usage: `s;poll `


**rockpaperscissors**

- Description: The ultimate battle of human vs program. Can you best Sage in a round of rock paper scissors?

- Usage: `s;rockpaperscissors `


**submit**

- Description: Submit an image to the current contest. After using this command upload an image in another message

- Usage: `s;submit `


**thisisfine**

- Description: Everything is fine... probably.

- Usage: `s;thisisfine `


**xkcd**

- Description: Find a comic from xkcd.

- Usage: `s;xkcd `
### Info Commands

**commit**

- Description: Get info about the most recent commit that is currently running.

- Usage: `s;commit `

- More info: Merge commits and version bumps are ignored.


**discordstatus**

- Description: Check Discord's current status.

- Usage: `s;discordstatus `


**feedback**

- Description: Provide feedback or bug reports about Sage.

- Usage: `s;feedback `


**help**

- Description: Provides info about all Sage commands

- Usage: `s;help `

- More info: If given no arguments, a list of all commands you have access to will be sent to your DMs


**info**

- Description: Provides information about Sage.

- Usage: `s;info `


**leaderboard**

- Description: Gives the top 10 users in the guild

- Usage: `s;leaderboard `

- More info: Enter a page number to look further down the leaderboard


**ping**

- Description: Runs a connection test to Discord

- Usage: `s;ping `


**serverinfo**

- Description: Provides information about the UDCIS discord server.

- Usage: `s;serverinfo `


**stats**

- Description: Displays info about Sage's current status

- Usage: `s;stats `
### Partial Visibility Question Commands

**anonymous**

- Description: Send an anonymous question in your classes general channel.

- Usage: `s;anonymous `

- More info: Sage will automatically determine your course if you are only enrolled in one!


**archive**

- Description: Archive a private question thread.

- Usage: `s;archive `

- More info: This command only works in private question threads.


**private**

- Description: Send a question to all course staff privately.

- Usage: `s;private `

- More info: Sage will automatically determine your course if you are only enrolled in one!


**reply**

- Description: Reply to a question you previously asked with Sage.

- Usage: `s;reply `
### Question Tagging Commands

**question**

- Description: Filters the questionTags collection for a given class and assignment

- Usage: `s;question `

- More info: Sage will automatically determine your course if you are only enrolled in one!


**tagquestion**

- Description: Tags a message with a given course/assignment ID. Must be run in a class-specific channel.

- Usage: `s;tagquestion `

More info related to the question tagging system can also be found on [this page](https://ud-cis-discord.github.io/pages/Question%20Tagging).
### Reminders Commands

**cancelreminder**

- Description: Cancel any pending reminders you may have.

- Usage: `s;cancelreminder `

- More info: You can only cancel one reminder at a time


**remind**

- Description: Have Sage give you a reminder.

- Usage: `s;remind `

- More info: Reminders can be set to repeat daily or weekly.


**viewreminders**

- Description: See your upcoming reminders.

- Usage: `s;viewreminders `

- More info: Don't worry, private reminders will be hidden if you use this command publicly.
### Staff Commands
All of the staff-only commands can be found on [this page](https://ud-cis-discord.github.io/staff_pages/staff%20commands).