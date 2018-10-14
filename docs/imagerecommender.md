---
id: imagerecommender
title: Image Tag Recommender
---

My final year project for my university.

## Period
Aug 2014 - May 2015

## Tech Stack
Apache Lucene, Apache Tomcat, Java, JSP, jQuery, CSS

## Introduction
While there are different possible strategies that an image recommendation system can use, most of them are purely based on the given data set alone. Hence, the purpose of this project is to investigate whether it is possible to further enhance the recommendation system by taking into account two factors – the temporal and location of the tagged photo. The aim is to study how these two factors would affect the correlation between tags.

The project will also allow users to explore various methods of understanding the Flickr tagging trends by using the functions available in the system. They allow users to observe how the tagging trends may change in relation to time and location by selecting specific ranges.

## Details
I used Lucene for quick and efficient searching of the dataset. The dataset was from Yahoo! Flickr Creative Commons 100M, which consisted information of 100 million photos and videos. After filtering out data that contained both geolocation and tags, the dataset was reduced to 40 million.

Tomcat was to host a web application to serve as the user interface for my program.

### Number of images containing a tag
![fyp2](/img/fyp2.jpg)
This allows searching the number of images that contains a given tag. It can be further refined by searching by data, geolocation or both.

### Area with the highest tag frequency
![fyp4](/img/fyp4.jpg)
Given a tag query, it will show the areas in a heatmap where the tag was used at, as well as indicating which geographical area has the highest number of hits for that tag.

### Date with the highest tag frequency
![fyp5](/img/fyp5.jpg)
Given a year and a tag query, it will show the number of times the tag has been used per month, indicating which month has the highest number of hits.

### Tag recommendation
![fyp6](/img/fyp6.jpg)
Given a tag, the program will find the top 10 other different tags tagged by other users whose photos/videos contain the query tag as well.

### Recommended tag distribution
![fyp7](/img/fyp7.jpg)
This function is used to look at how the tag with the highest correlation for a given tag would differ for different areas in the world.

### Results
![fyp8](/img/fyp8.JPG)
A sample of the results showing the difference in the recommended tags based on the geolocation of the user.
