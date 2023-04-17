# Createder-Back-End
- fork this repository
- clone and coding
- push and pull request to this repository
## User API and TodoList API with FastAPI(Python)
- `Database` : `Sqlite3` or `PostgreSQL` or `Microsoft SQL Server` with ORM (`SQLAlchemy/Pydantic`) 
- `Programming Language` : `Python 3`
### Part 0 : Data Schema
- user schema
```json
{
"id": ?
"userName":?
"password": ?
"email": ?
"firstName": ?
"lastName": ?
"phoneNumber": ?
"role": ?
}
```
- todolist schema
```json
{
"id": ?
"title":?
"dueDate": ?
"description": ?
"userId": ?
"completed": ?
}
```
### Part 1 : CRUD Endpoint User/TodoList (Create, Read, Update and Delete)
### `Authentication and Authorization with JWT for using TodoList API role admin and user`
- async/await
- pytest
- swagger ui
- add data to database
- show all data
- show data by id
- edit data and update to database
- delete data by id
- sort by last time created
- sort by last time updated
- select completed only
- show 5 data by page number
- show data by page number and limit data
    - show x data by page number ; x = limit data

### Part 2 : Run with Docker
- dockerfile
- docker-compose
## Create Aggregation API with FastAPI(Python)
- `Database` : (`Sqlite3` or `PostgreSQL` or `Microsoft SQL Server`) and `BigQuery` with ORM (`SQLAlchemy/Pydantic`)
- `Programming Language` : `Python 3`

### Part 0 : Data Schema
- main schema
```json
{
}
```
- other schema
```json
{
}
```
### Part 1 : Aggregation Endpoint (Read and Update)
- async/await
- pytest
- swagger ui
### Part 2 : Run with Docker
- dockerfile
- docker-compose
## DS with Python
- NLP with PythaiNLP (custom corpus)
- OCR for Thai Language
- Search Engine with Elasticsearch and Kibana and PythaiNLP (custom corpus)
- Recommendation System with Image and Text

Good Luck!
