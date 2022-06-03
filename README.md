
# Rap-Name-Api

This is an api made by leon noel with the 100Devs team to get information on rappers using just their name.

**Link to project:** https://rapper-api-100devs-class39.herokuapp.com/api/rapper-name

## How It's Made:

**Tech used:** Express.js

Using express.js we created a route to get request, using the parameter as argument to send corresponding response back to the request point.

## Optimizations

Added CORS to make Api usable from client side and not just server side, without hosting one can use our Api.

## Usage

```

fetch('https://rapper-api-100devs-class39.herokuapp.com/api/rapper-name')//replace rapper-name with rapper's name

  .then(response => response.json())

  .then(data => console.log(data))//Do whatever you want with data;

```
## Want to contribute
clone repository

`$ git clone https://github.com/100devs/rap-names-api`

install dependencies from package.json

`$ npm install https://github.com/100devs/rap-names-api`


`npm install <100devs>/<rap-names-api>`


## Test Result:
![Screenshot_20220603-030319](https://user-images.githubusercontent.com/69097602/171774385-5276465b-3ce8-422d-b431-13ca1fb21d2d.png)

