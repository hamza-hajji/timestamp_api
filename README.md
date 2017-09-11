# freeCodeCamp Backend Challenges - Timestamp Microservice

[Main URL](https://ts-microservice-api.herokuapp.com)

Example usage:

With date as a string:

`/June%2012%201995`

JSON Response:

```javascript
{
    "unix": 802915200000,
    "natural": "June 12, 1995"
}
```

With a date as a unix timestamp(seconds):

`/1504287732166`

JSON Response:

```javascript
{
  "unix": "1504287732166",
  "natural": "September 1, 2017"
}
```
