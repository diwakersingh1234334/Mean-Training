# SOS Project
>This Library Serves as the Server side support 
>for the **SOS Application**. It provides all HTTP 
>methods required to be invoked from the *Application USER INTERFACE*.

##  1. USER
>This includes all the HTTP methods related to **USER** member of SOS Application. 

####  1.GET Method
It will fetch all the **users** of the application from the database.  
> **GET:** {{url}}/api/user

##### HEADER
> **Content-TYPE:** application/Json

##### Response
```json
"userName":"Smith Jones",
"UserId":"ABC123",
"emailId":"smith.jones@xyz.com",
"contactNo.":1234567890
"address":"Denmark" 
```
####  2.POST Method
It involves the registration mechanism for **a new user**.
> **POST:** {{url}}/api/user

##### HEADER
> **Content-TYPE:** application/Json

##### Request Body
```json
"userName":"Smith Jones",
"UserId":"ABC123",
"emailId":"smith.jones@xyz.com",
"contactNo.":1234567890
"address":"Denmark" 
```
##### Response
```json
"new user Registered successfully"
```
####  2.PUT Method
It involves **update** mechanism for the registrated user.
> **PUT:** {{url}}/api/user/:id

##### HEADER
> **Content-TYPE:** application/Json

##### Request Body
```json
"userName":"Steve Jones",
"emailId":"steve.jones@xyz.com",
```
##### Response
```json
"user details updated successfully"
```




