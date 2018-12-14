---
title: "React Betting Website"
layout: post
date: 2018-11-29 10:10
tag:
- JavaScript
- Node.js
- React
- Bootstrap
- AJAX
- Amazon EC2
# image:
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "React Betting Website"
category: project
author: ankitgupta
externalLink: false
---

![Screenshot](../assets/images/betting.png)

Technology used:

- JavaScript
- React
- Node.js
- Bootstrap
- Amazon EC2
- AJAX

---
This is another project that I co-created in my Rapid Prototype Development and Creative Programming course. It was our final project, so we did not have any guidelines to follow- we were given free reign to make whatever we wanted. The idea for a website to help people keep track of bets was originally mine. I have struggled with remembering to pay or collect from my friends after we made friendly wagers, so I always wished there were an easy way to keep track of all of them.<br>
This project taught me more than any other project I have done so far- it was my first time working with React, and I was fully self-teaching myself.<br>
On this website, users may create a username and register/login with a password. The password is salted and hashed before being stored in the database for security purposes, and the site is protected against SQL Injection attacks. If a user is not logged in, they will be able to see any bets that other users have made public. The purpose of this section of the website is to inspire other users to create more bets. Once a user has logged in, they will be allowed to create bets against any of their friends, mark them as completed, or delete them if desired. Bets may be marked as public or private and can be listed as one of three categories: private, sports, entertainment. Bets marked as private will be visible only to users involved in the bet.<br>
The project is built with a Node.js and MySQL backend with a React frontend with Bootstrap and some custom CSS for styling.<br>
[Link to the GitHub page](https://github.com/ankit0504/Betting-Website)<br>
Specifics of the project including directions to locally run the project can be found in the README.
