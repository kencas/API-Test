# API-Test
A mini project to Test Product Upload VIA Node JS

## The API Details

The API is developed with NodeJS, and the Data store used is MongoDB; accessing the Db using Mongoose Library. The schema description is shown below

### To get all products run this command

Type - GET
Endpoint - https://fullstack-tester.herokuapp.com/products

Sample resulgt from endpoint
```
[
{
"name": "ff",
"description": "ddd",
"price": 33,
"category": "ccc",
"colour": "ccc",
"status": "Approved",
"_id": "5be307c170430c00236af4dc",
"productImage": "uploads/Wed Nov 07 20189Cab Logo 48px.png",
"created": "2018-11-07T15:41:53.650Z",
"__v": 0
}
]
```
### To get single product run this command, with the _id (which is the Model unique identifier)

Type - GET
Endpoint - https://fullstack-tester.herokuapp.com/products/{id}

Where id is the Unique ID

Eg - GET https://fullstack-tester.herokuapp.com/products/5be307c170430c00236af4dc
Sample result from endpoint
```

{
"name": "ff",
"description": "ddd",
"price": 33,
"category": "ccc",
"colour": "ccc",
"status": "Approved",
"_id": "5be307c170430c00236af4dc",
"productImage": "uploads/Wed Nov 07 20189Cab Logo 48px.png",
"created": "2018-11-07T15:41:53.650Z",
"__v": 0
}

```
### The Javascript and Web interface to test the API is listed below
https://fullstack-web-test.herokuapp.com/
