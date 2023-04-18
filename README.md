# Travel App by modext

## Project Description
<p>This is the capstone project for Udacity, where I am required to build a Travel App that obtains a desired trip location & date from the user. That information will then display the weather and an image of the location using information obtained from external APIs. The APIs that I used are <a href="http://www.geonames.org/export/web-services.html">Geonames API</a>, <a href="https://www.weatherbit.io/api">Weatherbit API</a> and <a href="https://pixabay.com/api/docs/">Pixabay API</a>.</p>

**Features included in the App:**
<ul>
  <li>Ability to add multiple trips</li>
  <li>Ability to delete a trip</li>
  <li>Each trip has a "To do" note taker</li>
  <li>User can generate a pdf file for each trip</li>
  <li>Retrieves weather data depending on the trip's length</li>
  <li>A relevant image will appear depending on the trip's location</li>
</ul>

## Dependencies and Packages
<ul>
  <li>HTML</li>
  <li>Sass</li>
  <li>Javascript</li>
  <li>Babel</li>
  <li>Webpack</li>
  <li>NodeJS (npm & Express)</li>
  <li>Jest (development)</li>
  <li><a href="http://www.geonames.org/export/web-services.html">Geonames API</a></li>
  <li><a href="https://www.weatherbit.io/api">Weatherbit API</a></li>
  <li><a href="https://pixabay.com/api/docs/">Pixabay API</a></li>
  <li><a href="https://www.npmjs.com/package/dotenv">dotenv Package</a></li>
  <li><a href="https://www.npmjs.com/package/uuid">UUID Package</a></li>
  <li><a href="https://www.npmjs.com/package/jspdf">jsPDF Package</a></li>
  <li><a href="https://html2canvas.hertzen.com/">html2canvas Package</a></li>
  <li><a href="https://www.npmjs.com/package/workbox-webpack-plugin">Workbox Webpack Plugin Package (Service Workers)</a></li>
</ul>

## Usage
This project does not have the API Keys for <a href="https://www.weatherbit.io/api">Weatherbit API</a> and <a href="https://pixabay.com/api/docs/">Pixabay API</a>. So if you want to run this project in your desktop, you will need to register for the API Keys and have them saved in the .env file as:

````
WEATHER_API_KEY=****************
PIXABAY_API_KEY=*****************
````

To run the project, you'll need to have NodeJS in your desktop. In the project's directory, in the terminal, you'll need to run: 

````
npm install
````

and afterwards,

````
npm run build-prod
````
This is so that your project's folder will have a dist folder containing all the files bundled by webpack. The server also points to this folder, so running those commands is necessary.

To run the web application you can run the following command line in your terminal.
````
npm start
````
Then in your browser, go to **localhost:8080** where your web app is at.

## Screenshots of the Travel App

<img src="https://user-images.githubusercontent.com/33578391/232921301-e74864ae-68ed-400f-92f0-24983df38b14.png" alt="travel app">
<p align="center"><em>"The travel app when you first enter upon the site"</em></p>

<br/>

<img src="https://user-images.githubusercontent.com/33578391/232921320-4c93576e-0297-40dd-8dd7-7917fdb914b1.png" alt="modal form for add trip">
<p align="center"><em>"The modal form, where users enter their trip destination"</em></p>

<br/>

<img src="https://user-images.githubusercontent.com/33578391/232921316-a2dd820e-1c82-41f7-a985-1ba4d65d51d9.png" alt="trip card with the current weather">
<p align="center"><em>"The card that displays the trip: Current Weather"</em></p>
<br/>

<img src="https://user-images.githubusercontent.com/33578391/232921311-b536a29c-9c83-4dd7-bc9c-2e79d26f1c57.png" alt="trip card with the forecast weather">
<p align="center"><em>"The card that displays the trip: Forecast Weather"</em></p>

<br/>

<img src="https://user-images.githubusercontent.com/33578391/232921309-305c1e13-2cef-4564-a592-2a1d4ff05dbc.png" alt="to do list">
<p align="center"><em>"The to-do-list"</em></p>

<br/>

<p align="center"><img src="https://user-images.githubusercontent.com/33578391/232921307-ee43a0ca-8ff5-4a2f-8bf6-1ca9cb8a01de.png" alt="mobile view for travel app"></p>
<p align="center"><em>"Responsive Design: Mobile View"</em></p>

<br/>

<p align="center"><img src="https://user-images.githubusercontent.com/33578391/232921304-c27453a9-2191-455e-a7c2-11717c369f61.png" alt="mobile view for travel app with modal"></p>
<p align="center"><em>"Responsive Design: Mobile View with Modal Form"</em></p>

built by Modext