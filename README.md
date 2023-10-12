# API-First

An API that is created to build a program using API-First Approach.

## API Description

This API is used to manipulate data in the database by inserting and extracting using endpoints. 

## API Endpoints

> 127.0.0.1/api/public/postName 
 - To insert data(s) in JSON format to the database.

> 127.0.0.1/api/public/updateName
 - To update data(s) available in the database.

> 127.0.0.1/api/public/deleteName
 - To delete a specific data from the database.

> 127.0.0.1/api/public/printName
 - To display the data(s) from the database.

## Request Payload
**Endpoint:** > 127.0.0.1/api/public/postName 
```
{
  "lname":"hortizuela",
   "fname":"manny"
}
```
**Endpoint:** > 127.0.0.1/api/public/updateName
```
{
  "id":1,
  "lname":"wick",
  "fname":"john"
}
```
**Endpoint:** > 127.0.0.1/api/public/deleteName
```
{
  "id":1
}
```

## Response Payload
**This should be the response for every activation of endpoints.** 
```
{
  "status":"success","data":null
}
```

## Usage
*Instruction on how to use the API Endpoints*
(Must have a created database in order to use the endpoints)
**Postman application was used in order to activate POST Payload endpoint.**

To use the endpoint postName:
1. Open Postman application and create a workspace.
2. After creating a workspace, change the GET method to POST method and insert the endpoint provided for the insert.
![alt text](1.jpg)

