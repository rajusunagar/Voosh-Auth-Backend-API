# Node.js Authentication and API
Node.js Authentication and API with Email Verification, Image Upload and Password Reset Using JWT, Passport.js and Sendgrid.

## Testing
Use <a href="https://www.getpostman.com" target="_blank">Postman</a> to test.<br/>

**Try accessing the user index route without token [GET]**<br/>

https://mesannodejsapiwithverification.herokuapp.com/api/user<br/>

![User Index](https://github.com/rajusunagar/Voosh-Auth-Backend-API/blob/main/demo/UserIndex.gif "User Index")

**Register and Login** <br/>
Create a POST request to /api/auth/register <br/>
Create a POST request to /api/auth/login

**Make sure to enter a valid email address so you can receive the verification email.**<br/>

![Register And Login](https://github.com/rajusunagar/Voosh-Auth-Backend-API/blob/main/demo/RegisterandLogin.gif "Register And Login")

![Verification Email](https://github.com/rajusunagar/Voosh-Auth-Backend-API/blob/main/demo/VerificationEmail.png "Verification Email")

**Login and Recover Password** <br/>
Create a POST request to /api/auth/recover to recover your password. An email will be sent to you.

![Password Recovery](https://github.com/rajusunagar/Voosh-Auth-Backend-API/blob/main/demo/PasswordRecovery.gif "Password Recovery")

**Reset Password and Login with new Password** <br/>
Click the link in the email to reset your password. 
Reset the password then attempt to login with your old password. This should fail. Login with your new password

![Password Reset](https://github.com/rajusunagar/Voosh-Auth-Backend-API/blob/main/demo/PasswordReset.gif "Password Reset")
