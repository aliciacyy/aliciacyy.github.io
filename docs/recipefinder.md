---
id: recipefinder
title: Recipe Finder
---

A program for finding all Rune Factory 4 recipes easily.

## Period
September 2015

## Tech Stack
Java Swing

## Motivation
Quick background information of Rune Factory 4: It is a 3DS game that involves farming and some RPG elements like dungeons. One of the main sources of income is selling your crops. The monetary value will increase if the crops are cooked into dishes instead.

To try to maximize my profits, I had to frequently check which will be the best selling recipe for a given ingredient. Everything is listed on the wiki page, but I had to use the browser's search to find the ingredient. I thought it was quite tedious, especially if there are many recipes, since I would have to keep track of the best selling ingredient myself while searching through the wiki page.

## Details
Having learnt some Java Swing for a module in university, I decided to use it to create this simple application that can help to filter all the recipes quickly.

![recipe1](/img/recipe1.JPG)
After getting the list of recipes from the wiki page and storing them in the Java application, the default page will show all the recipes ranked from the highest value.

![recipe2](/img/recipe2.JPG)
You can search for ingredients from the list on the left or use the search box. It also supports searching by recipe name. With this feature, I am able to find the highest value recipe to make for a given ingredient.

On hindsight, I should have sorted the recipe in value order automatically rather than putting the sort button at the top. This was one of the improvements that I had incorporated into the [mobile app](runefactory.md) version later.
