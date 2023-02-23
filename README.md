# Warbler

Twitter like clone

## Features
- CRUD features for user posts, likes, delete
- User registration and authencation
- DB with many-to-many relationships
- 92% test coverage

## Set Up
1. Create a virtual environment and install requirements:
```
$ python3 -m venv venv
$ source venv/bin/activate
$ pip3 install -r requirements.txt
```
2. Set up the database (PostgreSQL):
```
$ psql
=# CREATE DATABASE
(ctrl+D)
$ python3 seed.py
```
3. Run the server:
```
$ flask run -p 5001
```
4. View at `localhost:5001`

## To Do
- UX / UI improvments 
- User messaging interface, possibly with websocket
- Additional tests
