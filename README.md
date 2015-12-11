# Final Project

## Introduction

This is a final project for the [Interacting with Data](https://github.com/Brown-BIOL2430-S04-Fall2015/syllabus) seminar in fall 2015. In this project I want to design a visualization comparing 40 animations produced by Pixar and Dreamwork from several different perspectives such as year, rating, domestic and global box office. Moreover, I am hoping to make this visualization vivid by including logos/characters in animations. 

Click [here](https://rawgit.com/XiaojunMENG/finalproject/master/animations.html) to view this project.

## The data

Description of data

- Data source
The data come from [Ultimate Movie Ranking](http://www.ultimatemovierankings.com/pixar-movies-vs-dreamworks-movies/).
- Data structure - 
The dataset contains 40 Movies, with their year, company, adjusted domestic and global box office, box office rank by year, rating, and oscar nomination/win. The data is organized in a table with each movie occupying a row. 

## Background
Inspired by these example
![alt tag](http://www.slate.com/content/dam/slate/articles/arts/culturebox/2013/06/130628_criticsPixarRatings.jpg.CROP.original-original.jpg)

![alt tag](http://imgfave-herokuapp-com.global.ssl.fastly.net/image_cache/138589212297393.jpg)

In all these examples, rating of animations are plotted against year of production. In addition, points are connected by either straight lines/smoothed curves to show tendency. What attracted me most is that the logo/main character of the animation are incorporated into the animation. (Although this makes visualization less scientific, it is more fun to look at!)

Shortcoming of these visualization is that firstly, they only plotted rating against years. Secondly, they are static and I believe that the pictures of logo/main characters and pasted by hand onto the visualization, so making other similar plots would be troublesome(Imagine I want to make other plots of adjusted global and domestic box office vs year for 40 movies, I will have to manually paste 2*40 images!)

## This project
 
### Mapping of data to aesthetics
- The company information will be matched to color: red for Pixar and black for Dreamwork
- Year, domestic box, global box and rating can be selected as x/y axis. 
- The movie information is mapped to logos of movies.

### Filtering

The data is not filtered

### Motion
The logo of the movie shows when mouseover and disappears when mouse out.

### Perspective

To what extent is perspective (eg mappings) controlled by users vs hard coded in advance? How does this project aid in exploration vs exposition?

Users will be able to control the variables displayed in x and y axis. They can also choose a data point and see the logo of the corresponding movie.

We can see a linear relationship between domestic, global box and rating, with some interesting outliers: e.g. Sherek 2 and 3 are not highly rated yet has high adjusted domestic box office.

## Assessment

Some short-comings that I did not solve:
- The logos are quite blurry.
- It takes time for the image of the logo to load and while loading, the circles flash and takes on red/black color(which I do not quite understand why)
- The visual design of the scatter plot can be improved, currently it looks like a simple student project

I think this kind of visualization can be used for dataset where the rowname of the row is of interest. Also, for animation visualization, disney can be included:)
