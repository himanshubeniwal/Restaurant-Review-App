# Restaurant Reviews Apps - Stage 1

## Project Overview: 

* For the **_Restaurant Reviews_** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.<br />
* Features in three areas: **responsive design**, **accessibility** and **offline use**.<br />

## What do I do from here?

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.  <br />
In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.

## Navigating through repository: 
* **/css/styles.css**: Have all the css and formatting used to make this project awesome for all the pages.
* **/data/restaurants.json**: Contains the JSON format of the details from all restaurants.
* **/img/** : Have all images of restaurants.
* **/js/dbhelper.js** : Have all the Javascript code for fetching the stuff from restaurant database.
* **/js/main.js** : Contains all the Javascript and functionality for main index page.
* **/js/restaurant_info.js** : Have all Javascript code for restaurant details page.
* **/index.html** : Contains the code for our main index web page. 
* **/restaurant.html** : Code for restaurant details web page.
* **/ServiceWorker.js** : Code for making the offline use more easy. 

### Leaflet.js and Mapbox:

This repository uses **[leafletjs]**(https://leafletjs.com/) with **[Mapbox]**(https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information. 

### Note about ES6

Most of the code in this project has been written to the **ES6 JavaScript** specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, try to maintain use of **ES6** in any additional JavaScript you write. 

## REFERENCES 
1. Adding a Service Worker and Offline into your Web App (https://developers.google.com/web/fundamentals/codelabs/offline/)
2. Lab: Responsive Images (https://developers.google.com/web/ilt/pwa/lab-responsive-images)
