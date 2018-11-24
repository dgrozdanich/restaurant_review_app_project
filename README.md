### What do I do from here?

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 

In a terminal, check the version of Python you have: `python -V`. py -m http.server is the command to run the server. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

Once the server is running, navigate to localhost:8000

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information. 

## App Functunality: 

Once you open the app in a browser with your server running you can navigate the app like any other application. Here are a few notes on what is included in the app:

1. This app provides a look into local restaurants. The app has been organized to look good on all devices according to bootstrap standards, but only using CSS.

2. Some common accesabilty functions have been added like tab browsing and aria labels

3. A service worker has been added to keep a nice clean offline experience for the app. 





