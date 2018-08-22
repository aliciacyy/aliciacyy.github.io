---
id: mikuscores
title: Miku Scores
---
An app for keeping track of high scores.

## Period
February 2018

## Tech Stack
Ionic Framework, Google Firebase, Angular, CSS

## Motivation
It started when I was having a "friendly" competition with my friend over a 3DS game called "Project Mirai DX". It is a rhythm music game and you receive a score based on how well you did.

Since it is a single player game, we used to take photos of the results screen and send it to each to beat each other's scores. As the number of songs grew, I found it tedious to keep track of who won which song and so on. Hence, the idea for this app was born.

## Details
I used Google Firebase, which provided authentication, database and storage.

Ionic was for building the application, which allowed me to write the application simply in Angular and CSS before creating an Android APK file for my phone.

![miku_login](/img/miku_login.png)
Since my friend and I are going to be using the same app, I thought having authentication will help to reduce some manual work, such as having to indicate who was the one uploading the score. This also somewhat ensures data integrity as I will not be able to delete my friend's uploads and vice versa.

![miku_list](/img/miku_list.jpg)
Having the number at the top makes it easy to see who is currently leading. The person with the highest score is written under the song name, and the number on the right represents the total number of scores submissions. Clicking on the Floating Action Button (FAB) will open a form for creating a new entry.

![miku_gif](/img/miku_gif.gif)
The entries for each song are automatically sorted in descending order of the scores. Added the delete feature to delete any entries created by mistake.
