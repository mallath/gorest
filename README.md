I had created Rest Api using Golang with the help of gorilla mux and gorm
I had used mysql database in this application
Initially iniatilize the project  with "go mod init projectname"
I had runned go mod tidy
later run this go mod build
I had runned ./restapigl.exe
with help of gorm model it dynamically creates " id, created at,updated at, deleted at" these fields
In this application they are 5 http requests will be there
To create user details ,in api test tool select post method and provide url
http://localhost:9000/users 
In order to retrieve only particular user details select get method
http://localhost:9000/users/1
In order to get all user use get method
http://localhost:9000/users
In order to update user details based on their id use put method
http://localhost:9000/users/2
In order to delete user based on their id use delete method
http://localhost:9000/users/3
