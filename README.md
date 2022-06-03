# Rap Names API
This RESTful API returns data about your favorite rapper. 

![supaHot](https://media3.giphy.com/media/AJwnLEsQyT9oA/giphy.gif)

Check out the Live site: [Click Here](https://rapper-api-100devs-class39.herokuapp.com/)

## Documentation

![GET](https://img.shields.io/badge/-GET-brightgreen) Get Rapper Info by Name

>/api/ {<i>rapper_name</i>}

<strong>Example:</strong>

Route: `/api/chance%20the%20rapper`
<br>
Returns:
```
{
  "age": 29,
  "birthName":"Chancelor Bennett",
  "birthLocation":"Chicago, Illinois"
}
```
<strong>NOTE:</strong> If {rapper_name} doesn't exist in our database it will return "unknown" values

## Instruction
<i>If you want to run server on your local machine</i>

### Clone repo
>`git clone https://github.com/100devs/rap-names-api.git`

### Install Packages
>`npm install`

### Run server locally
>`node server.js`

## Try it yourself!

### I. Using cURL
<ins><strong>Local: </strong><ins>

>`curl http://localhost:8000/api/{rapper_name}`

<ins><strong>Live Server: </strong></ins>

>`curl https://rapper-api-100devs-class39.herokuapp.com/api/{rapper_name}`

### II. Using POSTMAN
Make sure you are making a [GET Request](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET) to the following url

<ins><strong>Local: </strong><ins>

>`http://localhost:8000/api/{rapper_name}`

<ins><strong>Live Server: </strong></ins>

>`https://rapper-api-100devs-class39.herokuapp.com/api/{rapper_name}`