# Dummy Card API

Simple server exposing *dummy* data for display on cards.

## API Usage

Simply run

    npm install
    npm start

and access ``http://127.0.0.1:3000/cards`` to get an array of data.

If you want to retrieve just a subset, specify the lower and upper limit as query parameters, for example:

    http://127.0.0.1:3000/cards?_start=8&_end=12

## Developing Your Application

This evaluation kit has a static WebServer installed with the application dependencies. To use it, simply create a `public` folder, and place your index.html within the folder. In doing so, you can access your content @ ``http://127.0.0.1:3000``