# Chicago Food Inspection

#### Video Demo: https://youtu.be/t1iS3ifp47g

#### Description: An web application that allows restaurant visitors and owners to view latest inspection results.

## How to run the application in your local machine

## 1 - sign up for a google maps API

## 2 - Copy and paste your google maps api key and add to line 39 between the quotes ' const apiKey = "";'

## 3 - run command in context of the project 'npm run dev' -> this will spin up a local server and you will be able to see the inspection results!

#### App.js - Parent JS file with headers of the website

#### SearchParams.js - API call to Chicago data portal to query the inspections, processing data to get latest report, pass data down and search input fields

#### Inspections.js - detailed page to display the inspection reports. Passes data down to Gauage Chart and Google Maps. Contains display fields for data points surfaced for the application
