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
![1](https://github.com/kingreuel33/api/assets/147026527/b5bc7925-2771-4375-8e7a-f277c0e85981)
3. The go to body and create a Request Payload to be inserted to the database in JSON format.
```
{
  "lname":"hortizuela",
   "fname":"manny"
}
```
4. Then press **SEND**.
![3](https://github.com/kingreuel33/api/assets/147026527/7340183a-16d1-4efe-8b44-13c06380785e)
5. Check the Response Payload and this should be the response.
```
{
  "status":"success","data":null
}
```

> To use the other endpoints, is the same as the procedure in using the endpoint postName.

## License
- *Apache License 2.0*
- *Sirib Capstone*

## Contributors
- **King David Reuel V. Almadrigo-** Created the repository and inserted essential information for the API.
- **Erven A. Poblete-** Partner in executing the push and pull command to the repository for the given task.

## Contact Information
If you have any inquiries, just look for this person or contact the provided mobile phone number.
King David Reuel V. Almadrigo - 09953608245 (Globe)

