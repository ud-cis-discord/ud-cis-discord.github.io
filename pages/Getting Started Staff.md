---
waltz:
  title: Getting Started (Staff)
  resource: page
  published: false
---
As staff, you'll need to know how to do some things in addition to what the general UD CIS Discord user has to know. The
following information will go over how to respond to students' private questions, add assignments to your course for use
with our question tagging system, reset a user's level, and lookup specific Discord users.

## Private Questions

Students can ask private and anonymous messages by DMing Sage directly and using the `s;private` and `s;anonymous`
commands. The anonymous questions are sent and should be replied to in your course's general channel, but the following
information about private questions also applies to anonymous questions if you want to reply to an anonymous question
privately.

A private question asked by a student will be sent to your course's staff channel and look like this:

![privateq.png][10]

As the instructions on the message state, you can reply to these questions by using the `s;sudoreply <questionID>
<response>` command. This will send your response to the student that asked the question's DMs.

## Adding Assignments

To add an assignment to your class so that questions can be tagged for a specific assignment, you can use the
`s;addassignment <course ID>|<assignment ID>` command. This adds a new assignment to your course that you or students
can link their questions to with the `s;tagquestion` command. These questions can then be recalled with the `s;question`
command.

## Resetting Levels

If you need to reset or edit a student's message count, you can use the `s;resetlevel` command. This command takes the
user whose level needs to be reset as a required argument. When called with only one argument, the student's message
count will be reset to 0. There is also an optional second argument, an integer. When used with a positive integer, the
user's message count will be set to the given integer. When used with a negative integer, the user's message count will
have the given integer subtracted from their total message count.

For example, if user bobby's message count is 20 and you call `s;resetlevel bobby -5`, bobby's new message count would
be 15. If you instead called `s;resetlevel bobby 27`, bobby's message count would be set to 27. Lastly, if you called
`s;resetlevel bobby`, bobby's message count would be reset to 0.

## User Lookup

To look up a specific user's real life information based on the Discord account they verified with, you can use the
`s;lookup <user>` command. This command takes one argument, the user to look up. If the user has opted in to having
their information shared over Discord, Sage will DM it to you directly. If they haven't opted in, you will get an email
with the requested information sent to the email that you verified with.

   [10]: https://canvas.instructure.com/courses/2510334/files/124105146/preview?verifier=PuNjlfNMIEUp62pbsXi77LMe1m2oQVahbyW48AEt