[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/Naereen/ama)
[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)
[![GitHub forks](https://img.shields.io/github/forks/saswatamcode/rest_go?style=social)](https://GitHub.com/saswatamcode/rest_go/network/)
[![GitHub stars](https://img.shields.io/github/stars/saswatamcode/rest_go?style=social)](https://GitHub.com/saswatamcode/rest_go/stargazers/)
[![GitHub issues](https://img.shields.io/github/issues/saswatamcode/rest_go.svg)](https://GitHub.com/saswatamcode/rest_go/issues/)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

# Simple Go REST API
A simple RESTful API to create, read, update and delete books built using Go. Uses Mux router.

## To Run
- Clone into repo
- Run `go get -u github.com/gorilla/mux`
- Run `go run main.go`
- Visit `localhost:8000`

## Endpoints
### Get all books
- `GET /api/books`
### Get a single book
- `GET /api/books/{id}`
### Delete a book
- `DELETE /api/books/{id}`
### Create a book
- `POST /api/books/`
```
{
   "isbn":"12345",
   "title":"SampleBook",
   "author":{"firstname":"John",  "lastname":"Doe"}
}
```
### Update a book
- `PUT /api/books/{id}`
```
{
   "isbn":"12345",
   "title":"SampleBook2",
   "author":{"firstname":"John",  "lastname":"Doe"}
}
```