## ABOUT THE PROJECT
<h1> QR-code Scanner and Generator</h1>
<div align="center"  width="55" height="55">
  <img src="Frontend/Images/qrlogo.png" alt="html" width="200" height="100"/>
  <br>
  <br>
  <p>Welcome to QR Code-Chimp.</p>
  <br>
  <p>This website provides a user-friendly interface to generate custom QR codes and scan existing codes using their device camera. It provides a quick and convenient way to share information or access content. </p>
</div>








## TECH STACKS USED

<p align = "center">
<img src="https://github.com/PrinceCorwin/Useful-tech-icons/blob/main/images/HTML.png" alt="html" width="55" height="55"/>
<img src="https://user-images.githubusercontent.com/25181517/183898674-75a4a1b1-f960-4ea9-abcb-637170a00a75.png" alt="CSS" width="50" height="55"/>
<img src="https://user-images.githubusercontent.com/25181517/117447155-6a868a00-af3d-11eb-9cfe-245df15c9f3f.png" alt="js" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/PrinceCorwin/Useful-tech-icons/main/images/nodejs.png" alt="nodejs" width="50" height="50"/>
<img src="https://res.cloudinary.com/kc-cloud/images/f_auto,q_auto/v1651772163/expressjslogo/expressjslogo.webp?_i=AA" alt="express" width="50" height="50"/>
 <img src="https://raw.githubusercontent.com/PrinceCorwin/Useful-tech-icons/main/images/mongodb-leaf.png" alt="mongo" width="50" height="50"/> 
<img src="https://user-images.githubusercontent.com/25181517/121401671-49102800-c959-11eb-9f6f-74d49a5e1774.png" alt="npm" width="50" height="50"/>
  
</p>
<hr>

## Features 
-  Authentication
-  API Validation
-  Responsive
-  Cross Platform
-  Different Interface for both Users and Admin
-  Registeration/Signin/Logout
-  URL Qr-Code Generator 
-  Text Qr-Code Generator 
-  Qr-code scanner via camera or local img
-  Admin can view all registered users and can delete their account
-  Admin can view all logs


## Run Locally
### Clone this Project

```
https://github.com/atir09/Qr-code-scanner_generator
```

### Install npm Packages

```javascript
npm i --global
```

### Go to Backend Folder
```javascript
cd Backend
```

### Run Server
```javascript
npx nodemon index.js
```
### Runs the project in the development mode

[http://localhost:8000](http://localhost:8000)


### Environment Variables Required
`mongourl`

`secretKey + refreshSecretKey + salt`

`port`

`Redis Cloud: Password + Host + Port`

`token_key`

`ref_token_key `


## NPM Packages
<p align = "center">
<img src="https://repository-images.githubusercontent.com/139898859/9617c480-81c2-11ea-94fc-322231ead1f0" alt="bcrypt.png" width="70" height="50"/>
<img src="https://github.com/faraz412/cozy-passenger-4798/blob/main/Frontend/Files/cors.png?raw=true" alt="cors" width="70" height="50"/>
<img src="https://github.com/faraz412/cozy-passenger-4798/blob/main/Frontend/Files/download.png?raw=true" alt="dotenv" width="60" height="50"/>
<img src="https://github.com/faraz412/cozy-passenger-4798/blob/main/Frontend/Files/JWT.png?raw=true" alt="jwt" width="70" height="50"/>
<img src="https://4008838.fs1.hubspotusercontent-na1.net/hubfs/4008838/mogoose-logo.png" alt="mongoose.png" width="70" height="70"/>     
<img src="https://user-images.githubusercontent.com/13700/35731649-652807e8-080e-11e8-88fd-1b2f6d553b2d.png" alt="nodemon.png" width="50" height="50"/>
</p>

-  "bcrypt": "^5.1.0",
-  "body-parser": "^1.20.2",
-  "cors": "^2.8.5",
-  "dotenv": "^16.0.3",
-  "express": "^4.18.2",
-  "express-winston": "^4.2.0",
-  "jsonwebtoken": "^9.0.0",
-  "mongoose": "^7.0.3",
-  "nodemon": "^2.0.22",
-  "winston": "^3.8.2",
-  "winston-mongodb": "^5.1.1",
-  "qrcode": "^1.5.1"




   
## API Endpoints
   #### Welcome
```javascript
GET  /
```

 #### User 
```javascript
    USER LOGIN :    user/login
    USER SIGNUP:    user/signup
    LOGOUT:         user/logout
```
  #### Admin 
 ```javascript
    admin//userlist
    admin//deleteUser/:id
    admin/logs
 ```
    
   
<div align = "center">  
  
  
| `Project Highlights` |
| :------------------: | 


<!-- ///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->

    
  <h1>1.  Home Page  </h1><br><br>
  
![Home 1](https://github.com/atir09/Qr-code-scanner_generator/blob/main/Frontend/Images/home-1.png)

  ![home 2](https://github.com/atir09/Qr-code-scanner_generator/blob/main/Frontend/Images/home-2.png)

  

  <h1>2. Login  </h1>
  <br><br>
  
  ![login](https://github.com/atir09/Qr-code-scanner_generator/blob/main/Frontend/Images/login.png)
  
  <h1>3. Signup  </h1>
  <br><br>
  
  ![signup](https://github.com/atir09/Qr-code-scanner_generator/blob/main/Frontend/Images/signup.png)
  
  <h1>4. Url ==> QR Code Generator  </h1>
  <br><br>
  
  ![image](https://github.com/atir09/Qr-code-scanner_generator/blob/main/Frontend/Images/Url.png)

 <h1>4. Text ==> QR Code Generator  </h1>
  <br><br>
  
  ![image](https://github.com/atir09/Qr-code-scanner_generator/blob/main/Frontend/Images/text.png)

  <h1>5. QR Code Scanner  </h1>
  <br><br>
  
  ![image](https://github.com/atir09/Qr-code-scanner_generator/blob/main/Frontend/Images/scanner.png)
  
  <h1>6. Admin  </h1>
  <br><br>
  
  ![Admin](https://github.com/adityagithubraj/-direful-order-8525/blob/main/Frontend/Images/admin-dashboard.png)
  
  ![Admin1](https://github.com/adityagithubraj/-direful-order-8525/blob/main/Frontend/Images/admin-users.png)
  
  ![Admin2](https://github.com/adityagithubraj/-direful-order-8525/blob/main/Frontend/Images/admin-logs.png)
  
  





| `Demo` |
| :----: | 
   

[FRONTEND](https://go-fit.netlify.app/](https://qr-code-scanner-generator.netlify.app/)

[BACKEND](https://rich-plum-barracuda-fez.cyclic.app/)

 
| `Author` |
| :-------: | 

 [ATIR KHAN](https://github.com/atir09) 
 

