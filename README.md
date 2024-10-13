# spring-boot-token-api
Spring boot token API using spring boot security with JWT token 

What we will build
The API must expose routes where some are accessible without authentication while others require one. Below are the routes:

[POST] /auth/signup → Register a new user
[POST] /auth/login → Authenticate a user
[GET] /users/me → Retrieve the current authenticated user
[GET] /users → Retrieve the current authenticated user

The routes “/auth/signup” and “/auth/login” can be accessed without authentication while “users/me” and “users” require to be authenticated.
