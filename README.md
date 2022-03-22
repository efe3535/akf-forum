# akf-forum
<img src="https://raw.githubusercontent.com/Akif9748/akf-forum/main/public/images/logo.jpg" align="right" width="300px" />

A forum script written in Node.js.

## Installation
- Clone this repo. Or download it.
- Write `npm i` to install **dependencies**.
- Write `npm restart` for **reset database**, and `npm start` for run it. 
- Note, the reset database is important!

## API
Akf-forum has got an API for other clients etc. You can test api with run apitest.py.
And, you can learn informations about API in `APIDOCS.md`.

## Credits
* [Akif9748](https://github.com/Akif9748) - Project owner, main developer
* [Camroku](https://github.com/Camroku) - Made stylesheets

## To Do (Backend, bug fixes) :
- Middleware. For logged in etc.
- Better error codes, example 400 for bad request
- Database change. (To MongoDB) 
- Better DB writing. Example, not `message.author.id`, `messsage.authorID`
- `/errors/error` will change

## Roadmap
- [x] User
  - [x] Login
  - [x] Register
  - [x] Logout
  - [x] Admin
  - [x] Message count
  - [x] Delete User
  - [ ] Singature & About me
  - [ ] Edit user
- [ ] Messages
  - [x] Ratelimit for sending message
  - [x] Send message
  - [x] Delete message
  - [ ] Edit message
  - [x] React message
- [ ] Threads
  - [ ] Edit it!
  - [ ] Delete it!
- [ ] Other
  - [x] API
  - [x] Other client for forum via API 
  - [ ] Footer of the site
  - [ ] Multiple theme support 
  - [ ] Search 
  - [x] New Thread theme, better render for messages

## Image:
![image](https://user-images.githubusercontent.com/70021050/158060900-7384d394-cad7-4f73-94ad-7c8bd108ac44.png)

