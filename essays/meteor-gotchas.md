---
layout: essay
type: essay
title: Meteor GOTCHAS
date: 2017-09-20
labels:
  - Questions
  - Answers
---

This essay is targeted towards addressing the questions on issues students of ICS 314 have faced during their first time using meteor, <a href= "http://goo.gl/CdWGyh">click here</a> for more information.

## Startup times and issues I experienced...

The intial startup time for meteor during an instance when I forked a repository to use to become more comfortable with using meteor, I had envoked a command such as **meteor --no-release-check --settings ../config/settings.development.json** , which took an extremely long time to finish running, approximately 40 minutes on a sleep deprived night. I found myself waking up the next day's morning with my laptop battery nearly drained. 

<img class="ui centered medium image" width = "70%" src="http://cdn1.theinertia.com/wp-content/uploads/2016/03/tired.jpg">

**Now, the issues at hand, with a little background ... **

The programming languages I have learned so far before taking ICS 314 were mostly functional programming languages, as opposed to markup languages. Although I knew html, I did not take a class learning html in-depth. So, using a tool such as meteor was a whole new experience for me, unknowing what to expect.

**The first issue I came across...**

The first issue I came across was during an in-class WOD for ICS 314, and during that in class WOD, I found out that I could call the functions from a different class by specifying the function name inside of curly braces. Here's the example, it was the simple Meteor template that was given:
<head>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.2.2/semantic.min.css">
  <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.2.2/semantic.min.js"></script>
  <title>app</title>
  <link href="main.js">

</head>
<body>
<div class = "ui text container">
  <h1>Welcome to Meteor!</h1>

  {{> hello}}
  {{> info}}
</div>

</body>

<template name="hello">
  <button>Click Me</button>
  <p>You've pressed the button {{counter}} times.</p>
    {{thatsAlot}} <!-- This here was the issue!--->
</template>

<template name="info">
  <h2>Learn Meteor!</h2>
  <ul>
    <li><a href="https://www.meteor.com/try" target="_blank">Do the Tutorial</a></li>
    <li><a href="http://guide.meteor.com" target="_blank">Follow the Guide</a></li>
    <li><a href="https://docs.meteor.com" target="_blank">Read the Docs</a></li>
    <li><a href="https://forums.meteor.com" target="_blank">Discussions</a></li>
  </ul>
</template>






**The second issue **


**Spotting syntax errors**







 
 
