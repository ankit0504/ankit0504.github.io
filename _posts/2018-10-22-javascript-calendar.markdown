---
title: "JavaScript Calendar"
layout: post
date: 2018-10-22 10:10
tag:
- JavaScript
- jQuery
- Bootstrap
- PHP
- AJAX
- Amazon EC2
- MySQL
# image:
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "JavaScript Calendar"
category: project
author: ankitgupta
externalLink: false
---

![Screenshot](../assets/images/calendar.png)

Technology used:

- JavaScript
- jQuery
- Bootstrap
- Amazon EC2
- PHP
- AJAX
- MySQL

---
This is another project that I co-created in my Rapid Prototype Development and Creative Programming course. We created this calendar with an HTML template that we found online, Bootstrap for styling, PHP for web security things, and vanilla JavaScript for the functionality. <br>
This calendar has functionality to add an event with a title, date and time, edit and delete an already-created event, share events with other users, and filter your calendar view by seeing high-priority events only.<br>
All requests are handled by AJAX, so the calendar works on a single page and does not require any refreshes to see updates in the calendar. Passwords that are stored in the database are salted and hashed for a layer of security. This website is protected against SQL Injection, CSRF attacks, and XSS attacks.<br>
[Link to the GitHub page](https://github.com/ankit0504/Rapid-Prototype-Development-and-Creative-Programming/tree/master/JavaScript%20Calendar)<br>
[Link to the login page](http://ec2-18-220-119-176.us-east-2.compute.amazonaws.com/~kfeinberg/module5/calendar.html)
