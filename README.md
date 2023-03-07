# Warbler

## Features
- CRUD features for user posts, likes, delete
- User registration and authentication
- DB with many-to-many relationships
- 90% test coverage

## Environment Setup
```
Add a `.env` file in the top level directory and include the following 

  DATABASE_URL=postgresql:///warbler
  DATABASE_URL_TEST=postgresql:///warbler-test
  SECRET_KEY=so_secret

You'll need Python3 and PostgreSQL

  python3 -m venv venv
  source venv/bin/activate
  pip3 install -r requirements.txt

  createdb warbler
  createdb warbler-test

Then to run ::

  flask run -p (PORT)
```
---

## Tech

Python | Flask | SQL | Postgres | Javascript | HTML | CSS | Bootstrap

## Description

Built in 3.5 days as part of a sprint w/ @nicom while attending Rithm School.

## To Do
- UX / UI improvments
- User messaging interface, possibly with websocket
- Additional tests
