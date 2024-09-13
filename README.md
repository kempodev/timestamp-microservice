# Timestamp Microservice

This is my solution code for the Timestamp Microservice project:

https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/timestamp-microservice

## Getting started

### Install the required packages

```
npm install
```

### Start the server

```
npm start
```

## Usage

Make a GET request to `/api/:date` with either a unix datestamp (eg.
`/api/1451001600000`) or a date string (eg. `/api/2015-12-25`).

#### Return value (JSON)

```
{
    "unix":1451001600000,
    "utc":"Fri, 25 Dec 2015 00:00:00 GMT"
}
```
