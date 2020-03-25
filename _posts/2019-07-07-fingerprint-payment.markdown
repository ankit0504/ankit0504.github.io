---
title: "Fingerprint Payment"
layout: post
date: 2018-07-07 10:10
tag:
- Kotlin
- Java
- Android
# image:
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "Fingerpritn Payment"
category: project
author: ankitgupta
externalLink: false
---

![Screenshot](../assets/images/fingerprint_reader.jpg)

Technology used:

- Kotlin
- Java
- Android

---
During my summer at Square, I was in a class of about 60 interns. While we socialized reguarly for lunches, game nights, and exploring the bay area, Intern Hack Week was when we all spent copious amounts of time together. Leading up to Intern Hack Week, we self-organized into teams of three to five people and each came up with project ideas related to Square's existing products. My team and I decided we wanted to enable payments with a fingerprint.<br>
We decided that connecting a USB fingerpritn reader to an Android phone would be the most straightforward way of implementing this technology. Seeing as I was on the Connected Devices Experience team at Square, I played a leading role on my hack week team. I had the best understanding of how we were going to transfer and interpret data sent by the fingerprint reader to the phone. We struggled a lot with finding free libraries that would allow us to interface with the fingerprint reader, which became our biggest hurdle, but once that issue got resolved, we were relatively smooth from that point. The fingerprint reader sent data in the form of a bitmap, so we were easily able to compare results.<br>
The code we wrote was in Kotlin and Java, but to link a fingerprint to a specific person, we had to create a separate SQL database that associated a bitmap with a credit card on file. Obviously, the way we stored this data was not secure and not usable for production level code, but we were able to get a proof of concept working!<br>
While working on this project, I thought a lot about whether or not this project was even something consumers would want. Personally, the idea of a company storing my fingerprint data is disconcerting. I am not sure what the legality of private companies storing fingerprint data is (or if such privacy laws even exist) but that is definitely a future step that this project would need if it were ever considered for production.<br>
Unfortunately I do not own the code that was written for this project because it was directly affiliated with Square. <br>
