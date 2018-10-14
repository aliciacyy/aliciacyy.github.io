---
id: mhstories
title: MH Stories Helper App
---
An app for making monster eggs identification faster.

## Period
October 2018

## Tech Stack
Ionic Framework, Angular, CSS, BeautifulSoup, Python

## Motivation
I started playing [Monster Hunter Stories](https://itunes.apple.com/sg/app/monster-hunter-stories/id1339054344), which involved collecting monster eggs but the game does not explictly tell you which egg pattern corresponds to which monster.

Although there are websites with this information, I decided to just put together a simple app quickly which will let me search for the egg information offline, as well as keeping track of the ones that I already have.

## Details
I used BeautifulSoup and Python to write a simple script that crawls the website, extracts the information, do some post processing tasks such as grouping the monsters by location and then outputs them in a nicely formatted JSON file to be read by my app during the first initialization.

Ionic was for building the application, which allowed me to write the application simply in Angular and CSS before creating an Android APK file for my phone.

![mhs3](/img/mhs3.jpg)
The main page was the eggs page with a list of locations. Numbers on the right represents the number of eggs that I have and the total number of eggs for that area.

![mhs2](/img/mhs2.gif)
Expanding each list shows the eggs which can be found. Eggs can be checked to keep track. If all eggs for the area are checked, the counter turns green.

![mhs4](/img/mhs4.jpg)
I also frequently visit a post in GameFAQs to decide which monsters to use, so I decided to just put his post in the previously default home page.


## Credits
- **Eggs information:** https://gameskinny.com/xm3vu/monster-hunter-stories-guide-all-egg-patterns-and-locations
- **Recommended Monsties:** https://gamefaqs.gamespot.com/boards/146555-monster-hunter-stories/75802537