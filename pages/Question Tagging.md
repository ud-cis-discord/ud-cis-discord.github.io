---
waltz:
  title: Question Tagging
  resource: page
  published: false
layout: page
title: Question Tagging
---
Sage's question tagging system is a great way to see what kinds of questions other people are asking about an
assignment. You can also help others out by tagging your own questions to assignments as you ask them. There are a
couple of commands that you're able to use to facilitate each of these things.

## Tagging a question

To tag a question, use the `s;tagquestion` command. You can also use `s;tagq` or `s;tag` as shorthand. This command is
used by replying to a message that you'd like to link to an assignment with that assignment's ID in one of your course's
channels as an argument: `s;tagq <assignmentID>`

![Josh Lyon sent: Is Python just for making games about snakes? Josh Lyon sent (replying to the previous message): s;tagq hw2 Sage sent: Added that message to the database ][25]

If you're only enrolled in one CISC course, you can see the list of assignments you can tag questions to by using the
`s;q` command. If you're enrolled in two or more courses, you'll have to specify the course you'd like to see
assignments for: `s;q 108`.

## Finding tagged questions

If you want to find questions that other people have tagged to specific assignments, you can use the `s;question`
command, or `s;q` as shorthand, followed by the assignment that you want to find questions for: `s;q <assignmentID>`. If
you're enrolled in more than one CISC course, you'll need to specify the course you're looking up as well: `s;q
<courseID> <assignmentID>`.

![Josh Lyon sent: s;q 108 hw2 Sage sent: I've sent the list to your DMs.][26] ==>
![Sage sent: Questions for 108 hw2: * Is Python just for making games about snakes? (click to view) * How do I invert a binary tree? (click to view)][27]

You can then click the link that says "Click to view" to go to the original message and see discussion about the
question.

   [25]: https://canvas.instructure.com/courses/2510334/files/124743054/preview?verifier=Opd803ZIkC7Lh9TutFzOxkWreXF04xxXva58bEJQ
   [26]: https://canvas.instructure.com/courses/2510334/files/124744481/preview?verifier=X5Ymm47gASbbmQlt2SVb948RwIGF2K2FwHyeNjPR
   [27]: https://canvas.instructure.com/courses/2510334/files/124744733/preview?verifier=8nseThmpUxL9E76Wm9lXzghHuBTDwEuktrvyLhMW