# node-js-jwt-auth
Node.js &amp; MongoDB example that supports User Authentication (Registation, Login) &amp; Authorization with JSONWebToken (JWT).

Registration Api address:  POST    http://localhost:8080/api/auth/signup

Data to be uploaded in the form of JSON object. e.g.
{
    "username": "admin",
    "email": "admin@email.com",
    "password": "12345678",
    "roles": ["user","admin"]
}


Login api address : POST    http://localhost:8080/api/auth/signin
e.g.

{
    "username": "modera",
    "password": "12345678"
}
