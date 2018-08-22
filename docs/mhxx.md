---
id: mhxx
title: MHXX App
---
A quick reference app for Monster Hunter XX.

## Period
November 2017

## Tech Stack
Ionic Framework, Angular, CSS

## Motivation
There had been no news of localization for a Japanese game called Monster Hunter XX for over 2 years, so I decided to just get the Japanese game despite not knowing Japanese. At least there was this website called Kiranico which had the game information in English. But I thought having an app would be faster and handy.

Nevertheless, I was still inspired to make an app because of other apps for the previous installations of the series like [this](https://play.google.com/store/apps/details?id=com.ghstudios.android.mhgendatabase) and [this](https://play.google.com/store/apps/details?id=com.daviancorp.android.mh4udatabase).

Although the project is incomplete, it will no longer be updated since Capcom has suddenly decided to release the English version of the game in 2018.

## Details
My friend helped to get the data from Kiranico and then stored it in JSON files, which would then be read by the app and display the information.

The app has 2 pages - one for the list of quests and one for the list of food skills.

![mhxx1](/img/mhxx1.jpg)
Quests belong in different levels of difficulty, so the first list is to pick the rank.

![mhxx2](/img/mhxx2.jpg)
The next list shows the list of all the quests which are in that rank. Quests with a key sign represent key quests. This makes it easier for us to find the key quests as the game does not tell you which are the ones and the list also provides the English translations to understand the quest name in the game.

![mhxx3](/img/mhxx3.jpg)
Clicking into the quest name will show more details of the quest. Both Japanese and English text are included to help us understand the details of the quest.

![mhxx4](/img/mhxx4.jpg)
I decided to work on the food skills page next because it was quite annoying not knowing what are the food skills that I will be getting.

Having a search bar would be efficient, but I don't know how to type the Japanese characters, so my next solution was to group the names of the food skills according to the similar characteristics that they share. For example, I grouped all the food skills whose names contains "人" under the category "人".

![mhxx5](/img/mhxx5.jpg)
Even though there is no efficient ordering after that due to the lack of understanding of Japanese, I thought at least it will reduce the number of items that I would have to check.
