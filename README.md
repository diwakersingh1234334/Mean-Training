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
> **Content-TYPE:** application/JsonR

##### Response
```json
"userName":"Smith Jones",
"UserId":"ABC123",
"emailId":"smith.jones@xyz.com",
"contactNo.":1234567890
"address":"Denmark" 
```



