# Warbler

Warbler is a Twitter like messaging board, where users can register, login, like, comment and make posts of thier own was well as others on the platform.

[Demo Here](https://warbler.up.railway.app/)

**Test Login:** _guest_
**pw:** _password_

## 🧐 Motivation & Challenges

> This project was built in a 3.5 day sprint with @nicom as a part of Rithm School. Much of the code was given to us, it was up to us to find and fix many errors in the codebase, as well as implement certain unfinished features and build up the testing suite. 

> The major challenge with the project was it was the first time working with a codebase of decent size that we were unfamiliar with. We then had to budget time to implement fixes. 

## 💻 Tech Stack 

**JavaScript | Python | Flask | SQLAlchemy | Jinja** 

## ⭐️ Features (added by us)

- User registration/authentication/profile deletion
- Posting, liking, and deleting messages
- Following/unfollowing users
- Chronological feed of followed-users' messages
- Password hashing with bCrypt
- 92% test coverage

## 📦 Install & Run

1. Create a virtual environment and install requirements:
```
$ python3 -m venv venv
$ source venv/bin/activate
$ pip3 install -r requirements.txt
```
2. Set up the database (PostgreSQL):
```
$ psql
=# CREATE DATABASE warbler;
(ctrl+D)
$ python3 seed.py
```
3. Add a .env file with:
```
SECRET_KEY=(any secret key you want)
DATABASE_URL=postgresql:///warbler
```
4. Run the server:
```
$ flask run -p 5001
```
5. View at `localhost:5001`


### ☑️ To-Do's
- Fix background image formatting
- Fix login "unsuccessful" UI message
- Shift to responsive, SPA front-end framework
- Additional testing
