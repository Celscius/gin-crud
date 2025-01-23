# gin-crud

this project is an exemplary rest api server built with Go 

See API Spec (modified from RealWorld API Spec to simplify)

### API Server technology stack is
- server code: golang
- REST Server: gin
- Database: Sqlite
- ORM: gorm

### Getting Started
copy this project to your directory then you can start this app by using command below 
> ####  go run main.go

### Endpoint
| Action  | Verb | Path | Description | 
| ------------- | ------------- | -------- | ---------- |
| Create  | POST | /user | create and entity present in the json payload |
| List  | GET | /user | Get all entities from the resource |
| Read  | GET | /user/:id | Get a single entity |
| Update  | UPDATE  | /user/:id | Update an entity with the JSON payload |
| Delete  | DELETE | /user/:id | Delete an entity |


