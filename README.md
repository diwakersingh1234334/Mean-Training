# SOS Project
>This Library Serves as the Server side support 
>for the **SOS Application**. It provides all HTTP 
>methods required to be invoked from the *Application's USER INTERFACE*.

##  1. USER
>This includes all the HTTP methods related to **USER** member of SOS Application. 

####  1.GET Method
It will fetch all the registered **users** from the database as a successfull response.  
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
"response":"new user Registered successfully"
```
####  3.PUT Method
It involves **update** mechanism for the registrated user by passing one's *ID*.
> **PUT:** {{url}}/api/user/:id

#### PARAMETER
> **userId:** XYZ098

##### HEADER
> **Content-TYPE:** application/Json

##### Request Body
```json
"userName":"Steve Jones",
"emailId":"steve.jones@xyz.com",
```
##### Response
```json
"response":"user details updated successfully"
```
####  4.DELETE Method
It **deletes a user** associated with the particular ID, passed during the request from User Interface.
> **DELETE:** {{url}}/api/user/:id

#### PARAMETER
> **userId:** XYZ098

##### HEADER
> **Content-TYPE:** application/Json

##### Response
```json
"response":"user deleted successfully"
```
##  2. TRUCK
>This includes all the HTTP methods related to **TRUCK** member of SOS Application. 

####  1.GET Method
It will fetch all the registered **trucks details** from the database as a successfull response.  
> **GET:** {{url}}/api/truck

##### HEADER
> **Content-TYPE:** application/Json

##### Response
```json
"truckName":"ASDF",
"truckId":"ASDF876",
"emailId":"smith.jones@xyz.com",
"contactNo.":1234567890
"address":"Denmark" 
```
####  2.POST Method
It involves the registration mechanism for **a new truck**.
> **POST:** {{url}}/api/truck

##### HEADER
> **Content-TYPE:** application/Json

##### Request Body
```json
"truckName":"xyz",
"truckId":"XYZ098",
"emailId":"smith.jones@xyz.com",
"contactNo.":1234567890
"address":"Denmark"
```
##### Response
```json
"response":"new truck Registered successfully"
```
####  3.PUT Method
It involves **update** mechanism for the registrated truck by passing one's *ID*.
> **PUT:** {{url}}/api/user/:id

#### PARAMETER
> **truckId:** XYZ098

##### HEADER
> **Content-TYPE:** application/Json

##### Request Body
```json
"truckName":"ABCD456",
"emailId":"steve.jones@xyz.com",
```
##### Response
```json
"response":"truck details updated successfully"
```
####  4.DELETE Method
It **deletes a truck** associated with the particular ID, passed during the request from User Interface.
> **DELETE:** {{url}}/api/truck/:id

#### PARAMETER
> **truckId:** XYZ098

##### HEADER
> **Content-TYPE:** application/Json

##### Response
```json
"response":"truck deleted successfully"
```


