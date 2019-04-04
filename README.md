![CF](http://i.imgur.com/7v5ASc8.png)
=================================================

## Lab 13
### Chris Merritt

* [PR][1]

### Functions

 `_authBearer()`
* Calls the authenticateBearer user method, then calls _authenticate on the result to check if the user has a valid auth token.

 `authenticateBearer()`
* Verify that the token is correct, then return the user's information from the db where it matches. 

### Additional functionality:
* Auth token expires after 15 minutes
OR
* Currently set to create a single use token.


Usage Notes or examples
### Setup
#### `.env` requirements
* `npm i`
* `PORT` = 3000
#### Running the app
* `npm start`

