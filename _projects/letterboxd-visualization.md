---
layout: page
title: Letterboxd Visualization 
description: A d3 visualization of The Top 250 Narrative Features on Letterboxd.
img: assets/img/LV.PNG
importance: 1
category: School Projects
giscus_comments: true
---

This project is a visualization of data regarding the Top 250 Narrative Features on Letterboxd. It features a variety of charts and graphs to allow users to get info on the greatest movies of all time.

It was developed as part of Instituto Superior Técnico's Visualization of Information course in 2021 using the JavaScript d3 package.

The code is available at [https://github.com/Catralitos/Letterboxd-Visualization](https://github.com/Catralitos/Letterboxd-Visualization).

It has sliders to filter movies by their runtime, number of ratings on the website, and average rating on the website.

It has a genre list for players to filter genres, as well as a radar chart to see the most popular genres and also conduct filtering.

At the center, there is a map where users can filter movies by country.

At the bottom there's a scatter plot correlating the movies' rating to their runtime or number of ratings.

There's also a bar chart displaying the directors and actors that most occur on the top 250 (or selected movies).

Finally to the left, there's a circular packing chart, where each decade is a circle, then each year, and finally each movie.

Clicking on actors or directors gets their filmography. Clicking on a particular movie gets its information.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/LV.PNG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The visualization running on the browser.
</div>
