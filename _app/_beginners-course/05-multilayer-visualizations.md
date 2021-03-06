---
title: "Online Mapping for Beginners — Multilayer Visualizations"
redirect_from: /courses/01-beginners-course/lesson-5.html
permalink: /courses/beginners-course/multilayer-visualizations/
tweet_text: "Step by step is the way to go. I've finished the fifth lesson of the map academy. Check it out"
---
# Multilayer Visualizations

In this final lesson of Course 1, we will be talking about creating a two-layer map. We'll be using both data sets - the one on US Counties and on Tornados in the US - so make sure you have both in the Data View section of your dashboard.

## Creating a Two-Layer Map

In order to create a multi-layer visualization, start by creating a visualization from one of the layers you'd like to include. We start with the US Counties dataset in this demo, but you could just as easily start with the Tornados dataset. Once you've created your visualization from one dataset, you can add another layer from the column of icons on the right. At the top of the CartoDB sidebar, select the "+" icon. There, you can chose to "Add a new layer," and select the dataset you'd like to add. In our case, it was the tornado layer.

![Adding a layer.](/img/course1/lesson5/addlayer.png)


## Styling with Multiple Layers

Styling your map visualizations when you have multiple layers of data functions the same as if you had only one layer. Each layer can be styled independently of the others. It is important to remember, however, that the order of the layers reflects the order in which they rendered or displayed. So if you have one fully opaque layer over another one, you may be unable to see the data under the opaque layer. Also, if you have infowindows enabled for both layers, only the top layer’s infowindows will show in areas where the bottom layer is covered by the top layer.

You can continue to play around with the visualization settings on both layers, and use the things you've learned in the previous lessons to create a good-looking visualization to share with the world!
