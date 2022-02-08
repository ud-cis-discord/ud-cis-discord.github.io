---
waltz:
  title: Commands
  resource: page
  published: false
layout: page
title: Commands
permalink: pages/commands
---
Here is a list of all of the commands available for Sage, usable with `/<command name here>`.
<br>
Note, any arguments to the commands will be shown with descriptions when you select the command you want to run.
### General Commands

**check**

- Description: Displays the users current message count.

- Parameters:
  - hide (optional): determines if you want stats public or private### Configuration Commands

**togglelevelpings**

- Description: Toggles whether or not you will receive notifications from Sage on a level up.


**togglepii**

- Description: Toggles whether your email (pii) will be sent to instructors over Discord.
### Fun Commands

**8ball**

- Description: Ask the 8-ball a question and you shall get an answer.

- More info: This command requires you to put a question mark ('?') at the end of your message.

- Parameters:
  - question (required): The question you want to ask

**blindfoldedroosen**

- Description: Challenge a blindfolded Prof. Roosen to a sword fight!

- More info: You've been challenged to a sword fight. However, your opponent, Professor Roosen, has decided to wear a blindfold. Feeling lucky?


**coinflip**

- Description: Have Sage flip a coin for you!


**diceroll**

- Description: Get `numdice` random integers between `minimum` and `maximum`.

- More info: User specified minimum and maximum are inclusive. If no range is specified, defaults to one number ranging from 1 to 6.

- Parameters:
  - minimum (optional): Minimum of the roll range (defaults to 1)
  - maximum (optional): Maximum of the roll range (defaults to 6)
  - numdice (optional): Number of dice to roll (1-10) (defaults to 1)

**doubt**

- Description: Press X to doubt.

- Parameters:
  - target (required): The user to doubt

**f**

- Description: Press F to pay respects.

- Parameters:
  - target (optional): The user to pay respects to

**latex**

- Description: Accepts a LaTeX expression and posts it as a rendered image.

- Parameters:
  - input (required): The LaTeX expression to render

**poll**

- Description: Have Sage create a poll for you.

- Parameters:
  - timespan (required): How long your poll should last. Acceptable formats include '5s', '5m', '5h', '5h30m', '7h30m15s'...
  - question (required): What would you like to ask?
  - choices (required): A poll can have 2-10 choices. Separate choices with '|' (no spaces/quotes).
  - optiontype (required): Whether participants can only select one choice or multiple.

**rockpaperscissors**

- Description: The ultimate battle of human vs program. Can you best Sage in a round of rock paper scissors?


**submit**

- Description: Submit an image to the current contest. After using this command upload an image in another message


**thisisfine**

- Description: Everything is fine... probably.


**xkcd**

- Description: Find a comic from xkcd.

- Parameters:
  - comic (required): The comic to send. Can be 'latest', 'random', or a number.### Info Commands

**commit**

- Description: Get info about the most recent commit that is currently running.

- More info: Merge commits and version bumps are ignored.


**discordstatus**

- Description: Check Discord's current status.


**feedback**

- Description: Provide feedback or bug reports about Sage.

- Parameters:
  - feedback (required): feedback to be sent to the admins

**help**

- Description: Provides info about all Sage commands

- More info: If given no arguments, a list of all commands you have access to will be sent to your DMs

- Parameters:
  - cmd (optional): command you would like to know more about

**info**

- Description: Provides information about Sage.


**leaderboard**

- Description: Gives the top 10 users in the guild

- More info: Enter a page number to look further down the leaderboard

- Parameters:
  - pagenumber (optional): leaderboard page to view

**ping**

- Description: Runs a connection test to Discord


**serverinfo**

- Description: Provides information about the UDCIS discord server.


**stats**

- Description: Displays info about Sage's current status
### Partial Visibility Question Commands

**anonymous**

- Description: Send an anonymous question in your classes general channel.

- More info: Sage will automatically determine your course if you are only enrolled in one!

- Parameters:
  - question (required): What would you like to ask?
  - course (optional): What course chat would you like to ask your question in?

**archive**

- Description: Archive a private question thread.

- More info: This command only works in private question threads.


**private**

- Description: Send a question to all course staff privately.

- More info: Sage will automatically determine your course if you are only enrolled in one!

- Parameters:
  - question (required): What you would like to ask
  - course (optional): What course chat would you like to ask your question in?

**reply**

- Description: Reply to a question you previously asked with Sage.

- Parameters:
  - questionid (required): The ID of the question you would like to reply to
  - response (required): What you would like to reply with### Question Tagging Commands

**question**

- Description: Filters the questionTags collection for a given class and assignment

- More info: Sage will automatically determine your course if you are only enrolled in one!

- Parameters:
  - assignment (required): The ID of the assignment to filter questions from
  - course (optional): What course would you like to filter questions from?

**tagquestion**

- Description: Tags a message with a given course/assignment ID. Must be run in a class-specific channel.

- Parameters:
  - message (required): The link of the message you want to tag
  - assignmentid (required): The assignment name tag to add to this message
More info related to the question tagging system can also be found on [this page](https://ud-cis-discord.github.io/pages/Question%20Tagging).
### Reminders Commands

**cancelreminder**

- Description: Cancel any pending reminders you may have.

- More info: You can only cancel one reminder at a time

- Parameters:
  - remindernumber (required): ID of the reminder to cancel

**remind**

- Description: Have Sage give you a reminder.

- More info: Reminders can be set to repeat daily or weekly.

- Parameters:
  - content (required): What you'd like to be reminded of
  - duration (required): When you'd like to be reminded
  - repeat (optional): How often you want the reminder to repeat

**viewreminders**

- Description: See your upcoming reminders.

- More info: Don't worry, private reminders will be hidden if you use this command publicly.
### Staff Commands
All of the staff-only commands can be found on [this page](https://ud-cis-discord.github.io/staff_pages/staff%20commands).