# Oauth2demo
## 1. POST http://localhost:9001/oauth/token
  ``` Body
      username : user/admin
      password : secret
      grant_type : password 
     
      
     
    Authorization
       Basi Auth
       Username : client
       password : password
   The Refresh Token grant type is used by clients to exchange a refresh token for an access token when the access token has expired.
   ````
   
## 2. GET http://localhost:9001/private 
  ``` pass token as Bearer  + token ```
## 3. GET http://localhost:9001/admin
   ``` pass token as Bearer  + token ```
## 4. GET http://localhost:9001/public
   
