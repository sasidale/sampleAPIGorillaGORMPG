implemented
- routing using Gorilla mux
- GORM
- postgres datbase


Install Gorilla mux
go get -u github.com/gorilla/mux

Install GORM
go get -u github.com/jinzhu/gorm

go get -u github.com/lib/pq/hstore

Install Postgres DB 11

https://www.postgresql.org/download/linux/ubuntu/

Supported Endpoints
POST /users
GET /users
GET /users/{id}
PUT /users/{id}
DELETE /users/{id}
