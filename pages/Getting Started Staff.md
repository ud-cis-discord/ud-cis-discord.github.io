---
waltz:
  title: Getting Started (Staff)
  resource: page
  published: false
layout: page
title: Getting Started (Staff)
permalink: staff_pages/getting%20started%20staff
---
As staff, you'll need to know how to do some things in addition to what the general UD CIS Discord user has to know. The
following information will go over how to respond to students' private questions, add assignments to your course for use
with our question tagging system, reset a user's level, and lookup specific Discord users.

## Private Questions

Students can ask private and anonymous messages by using the `/private` and `/anonymous`
commands. The anonymous questions are sent and should be replied to in your course's general channel, but the following
information about private questions also applies to anonymous questions if you want to reply to an anonymous question
privately.

A private question asked by a student will open a private thread under your course's general channel and look like this. 

![A private thread opened by Josh Lyon][0]

As the instructions on the message state, you can reply to these questions by replying in the thread that was created.

## Adding Assignments

To add an assignment to your class so that questions can be tagged for a specific assignment, you can use the
`/addassignment <course ID>|<assignment ID>` command. This adds a new assignment to your course that you or students
can link their questions to with the `/tagquestion` command. These questions can then be recalled with the `/question`
command.

## Resetting Levels

If you need to reset or edit a student's message count, you can use the `/resetlevel` command. This command takes the
user whose level needs to be reset as a required argument. When called with only one argument, the student's message
count will be reset to 0. There is also an optional second argument, an integer. When used with a positive integer, the
user's message count will be set to the given integer. When used with a negative integer, the user's message count will
have the given integer subtracted from their total message count.

For example, if user bobby's message count is 20 and you call `/resetlevel bobby -5`, bobby's new message count would
be 15. If you instead called `/resetlevel bobby 27`, bobby's message count would be set to 27. Lastly, if you called
`/resetlevel bobby`, bobby's message count would be reset to 0.

![A gif of the resetlevel command being called on Josh, subtracting 10 from his message count][1]

## User Lookup

To look up a specific user's real life information based on the Discord account they verified with, you can use the
`/lookup <user>` command. This command takes one argument, the user to look up. If the user has opted in to having
their information shared over Discord, Sage will show it to you directly. If they haven't opted in, you will get an email
with the requested information sent to the email that you verified with.

![A gif of the lookup command being run on Josh Lyon, revealing his email to be joshlyon@udel.edu and his message count to be 147][2]

[0]: /assets/privThread.png
[1]: /assets/gifs/resetLevel.gif
[2]: /assets/gifs/lookup.gif