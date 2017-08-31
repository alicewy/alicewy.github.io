---
layout: project
type: project
image: images/TemperatureConverter.png
title: Converting an F to a C
permalink: projects/TemperatureConverter
date: 2017
labels:
  
  - C
  - Java
  
summary: A temperature conversion program with a user interface that converts a temperature from fahrenheit to celsius, given the fahrenheit input.
---

<img class="ui centered middle image" src="../images/TemperatureConverter.png">

<b> So what are the features? </b>

This temperature converter program uses both Java and C to create an interface that requests the user to enter an input in Fahrenheit. A function to round up Fahrenheit and to convert the Fahrenheit to Celsius was written in C, while a function to print the table and a function to check if the input was an Integer to prevent invalid inputs, was written in Java. The Fahrenheit input is then rounded up to the next increment of 5, and a table of data is displayed. This was an assignment for ICS 212, program structure. 

<a href="https://github.com/alicewy/ICS212/tree/master/hw9">This is the link to my project!</a>


<b> The Struggles </b>

The programming parts of the assignment made it seem almost too easy, which made trying to execute and compile everything together even worse. Even though stack overflow had been helpful at times, particularly<a href="https://stackoverflow.com/questions/5963266/call-c-function-from-java"> this one fellow with the 48 likes, </a> I had to spend most of my time reading through a <a href = "https://www3.ntu.edu.sg/home/ehchua/programming/java/JavaNativeInterface.html"> JNI tutorial. </a>  

The command to run the project is: <b> java -Djava.library.path=. hw9 </b>

<b> Learning Outcomes </b>

The purpose of this assignment was to gain experience of learning on our own while being thrown into something that we didn't have much previous experience with. In fact, most of the course of ICS 212 helped to build students' skills with learning how to use different and new tools, such as the make utility and source code control system.
