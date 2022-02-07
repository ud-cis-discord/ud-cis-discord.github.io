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

Throughout this guide, we will refer to "copying the message link". To get the link for a message, click the three dots next to the message, then click "Copy Message Link" to copy it to your clipboard.
![Copying a message link][28]

## Tagging a question

To tag a question, use the `/tagquestion` command. This command uses the link of the message that you'd like to link to an assignment with that assignment's ID in one of your course's channels as an argument: `/tagquestion <messageLink> <assignmentID>`

If you're only enrolled in one CISC course, you can see the list of assignments you can tag questions to by using the
`/question` command. If you're enrolled in two or more courses, you'll have to specify the course you'd like to see
assignments for: `/question 108`.

## Finding tagged questions

If you want to find questions that other people have tagged to specific assignments, you can use the `/question`
command, followed by the assignment that you want to find questions for: `/question <assignmentID>` in either <span style="color:#7289DA">#sages_place</span> or a DM with Sage. If you're enrolled in more than one CISC course, you'll need to specify the course you're looking up as well: `/question <courseID> <assignmentID>`.

![Sage sent: Questions for 108 hw2: * Is Python just for making games about snakes? (click to view) * How do I invert a binary tree? (click to view)][27]

You can then click the link that says "Click to view" to go to the original message and see discussion about the
question.

   [25]: https://canvas.instructure.com/courses/2510334/files/124743054/preview?verifier=Opd803ZIkC7Lh9TutFzOxkWreXF04xxXva58bEJQ
   [26]: https://canvas.instructure.com/courses/2510334/files/124744481/preview?verifier=X5Ymm47gASbbmQlt2SVb948RwIGF2K2FwHyeNjPR
   [27]: https://canvas.instructure.com/courses/2510334/files/124744733/preview?verifier=8nseThmpUxL9E76Wm9lXzghHuBTDwEuktrvyLhMW
   [28]: https://canvas.instructure.com/courses/2510334/files/168780776/preview?instfs=true