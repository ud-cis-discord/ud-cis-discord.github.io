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
![Copying a message link][0]

## Tagging a question

To tag a question, use the `/tagquestion` command. This command uses the link of the message that you'd like to link to an assignment with that assignment's ID in one of your course's channels as an argument: `/tagquestion <messageLink> <assignmentID>`: 

![A gif of a student tagging a question by copying the message link and running the tagquestion command][1]

## Finding tagged questions

If you want to find questions that other people have tagged to specific assignments, you can use the `/question`
command, followed by the assignment that you want to find questions for: `/question <assignmentID>`. If you're enrolled in more than one CISC course, you'll need to specify the course you're looking up as well: `/question <courseID> <assignmentID>`.

![A gif of a student looking up a question by using the question command with assignment hw1 and course 123][2]

You can then click the link that says "Click to view" to go to the original message and see discussion about the
question.

[0]: /assets/copyLink.png
[1]: /assets/gifs/tagQuestion.gif
[2]: /assets/gifs/questionLookup.gif
