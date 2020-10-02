# Following tutorial: https://auth0.com/blog/build-an-api-in-rust-with-jwt-authentication-using-actix-web/ 

GET /users — returns all users
GET /users/{id} — returns the user with a given id
POST /users — takes in a JSON payload and creates a new user based on it
DELETE /users/{id} — deletes the user with a given id

Requests:
curl 127.0.0.1:8080/users
curl -X POST 127.0.0.1:8080/users