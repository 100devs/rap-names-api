# Rap Names API

An API that allows users to obtain the information of any stored rapper by name.

**Link to project:** https://rapper-api-100devs-class39.herokuapp.com/

![homepage showing API usage instructions](https://user-images.githubusercontent.com/9403665/171768370-3d0e3298-85b2-48dd-9dce-23844c316c19.png)

[![postman showing response of request to API for `rapper-name` of `21 savage`](https://user-images.githubusercontent.com/9403665/171768777-331588dc-f11f-4353-8267-4963557b525c.png)](https://rapper-api-100devs-class39.herokuapp.com/api/chance%20the%20rapper)

## Installation

- Clone the repository
- Run `npm install`

## Usage

- Run `node server.js`
- Go to http://localhost:8000/ in a web browser
- Make a GET request to http://localhost:8000/api/rapper-name, replacing `rapper-name` with the case-insensitive name of a rapper to obtain information of
  - Will return unknown information in the event that the provided `rapper-name` has no stored information

## How It's Made:

**Tech used:** HTML, JavaScript, Node.js, Express, Heroku, git

Combing Express and Node.js allowed for easy creation of the server, serving both the index HTML file with API instructions, and the actual API. Allowing any name to be requested of the API endpoint, searching the database for a rapper by case-insensitive name, and responding with that rappers information if found, otherwise responding with `unknown`.

## Optimizations

In the future this can be written to support more rappers, additionally providing more information about each rapper, and finally this data could be migrated into a MongoDB database to allow for realtime modification of the data.
