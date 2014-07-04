# User

### GET /user/1
Returns the details of a user
 	
##### Request Headers:
Accept –
- application/json
- text/plain

##### Query Parameters:
 	
additional query paramaters

##### Response JSON Object:
 	
- user_name (string) – The users name
- id (number) – The users id
- isAdmin (boolean) – Indicates if the user is an admin or not

##### Status Codes:	
- 200 OK – Request completed successfully
- 401 Unauthorized – You don't have privalage to acces this service

##### Request:
    GET /user/1 HTTP/1.1
    Accept: application/json
    
##### Response:
    HTTP/1.1 200 OK
    Cache-Control: must-revalidate
    Content-Type: application/json
    Date: Sat, 10 Aug 2013 07:02:41 GMT

    {
        "user_name": "John",
        "id": 1,
        "isAdmin": true
    }
