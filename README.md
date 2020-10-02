# Following tutorial: https://auth0.com/blog/build-an-api-in-rust-with-jwt-authentication-using-actix-web/ 

GET /users — returns all users  
GET /users/{id} — returns the user with a given id  
POST /users — takes in a JSON payload and creates a new user based on it  
DELETE /users/{id} — deletes the user with a given id  

Requests:

curl -v -H "Content-Type: application/json"  -X POST -d '{"first_name": "foo1", "last_name": "bar1", "email": "foo1@bar.com"}' 127.0.0.1:8080/users  

curl -v 127.0.0.1:8080/users  

curl -X DELETE 127.0.0.1:8080/users/1  
