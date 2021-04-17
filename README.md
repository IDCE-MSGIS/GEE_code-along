# Introduction to Google Earth Engine (GEE)
This repo briefly lays out the "code along" exercise using [Google Earth Engine](https://earthengine.google.com/) - so click the link to open it up in your browser! This activity will introduce you to the basics of JavaScript (JS) and build on what you already know about Python. The code along starts with `JS_basics.js` to practice some basic coding in JS and is followed by `DSM_analysis` which will be your first analysis in GEE!

If you want to dive deeper, you can find ([more info here abotut Google Earth Engine](https://www.google.com/earth/outreach/learn/introduction-to-google-earth-engine/)). These are released before our code along to give students a good background in what they will be working with. I also have them sign up for the GEE service well in advance, since the approval process was taking around 1 week at the time of writing.

## Getting Started with JS
Remember that no geospatial analysis takes place in `JS_basics.js`. Instead, all outputs are rendered in the GEE console tab.

> ![](images/JS_basics_output.png.png).

## Our First Analysis in GEE
Import the ALOS World 3D - 30m (AW3D30) global digital surface model, which has a horizontal resolution of approximately 30 meters. There are actually a few versions of this available in GEE, but the code I have used references bands specific to version 2.2, released in April 2019, which [can be found here](https://developers.google.com/earth-engine/datasets/catalog/JAXA_ALOS_AW3D30_V2_2). The code takes you through the steps of:
- importing the data;
- exploring the data in the console window to ensure they have the right data set;
- visualizing the data using a ([cartographically incorrect!](https://www.e-education.psu.edu/maps/l5_p5.html)) qualitative color scheme (it's the easiest to code!); and
- creating a mask that only shows areas of elevation over 500 meters (seen below in red).

> ![](images/DSM_analysis_output.png)

While my code is presented here as files, you can also access a [snapshot of my code on the GEE site here](https://code.earthengine.google.com/8675ccd49ee67b0048f13477c32930cd).

