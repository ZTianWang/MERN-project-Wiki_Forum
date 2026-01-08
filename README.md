<p align="center">
  <a href="https://yangshunjie.com/ant-design-blazor/">
    <img src="./frontend/public/favicon.ico">
  </a>
</p>

<h1 align="center">Enlightened Elephants Wiki Forum</h1>

<div align="center">A forum board built with React, Express, Node and MongoDB</div>

## What I do:
* Set up the router
* Set up context and local storage.
* Implement the backend part of Post function.
* Implement the Navigate Bar (both frontend and backend).
* Add token to HTTP request.
* Implement auto-login.

![](./Home.png)

![](./Kobe_Bryant.png)

## 🎨Description 

This is an open forum for Wikipedia, which is a MERN-stack Web application that enables users to authenticate to post comments and discussions about Wikipedia contents, and to reply to these posts. We hope that the Wikipedia forum will help people gain more useful information and make users have a good experience.

## ✨Roadmap

### 🌈Registry and login

The users need to register and login their own accounts. This is the basic function for some other functions.


### 📦The precise search of Wikipedia articles
Search wikipedia articles to view the content and discussion from other users, or join the discussion yourself!

### 💕Corresponding view of a wikipedia article and post
A view with a wikipedia article and related discussion co-displaying to offer a good experience of exploring the konwledge behind the wikipedia article with other users.

### 🎨Post and reply
Post your opinions about related wikipedia articles and comment to others.

### 🛡Like posts
Support the opinions you like or you think important.

## ⚙️Technologies

As we use MERN stack to build the application, we build a frontend application with React and an express application with Express. Store data in a MongDB. Modify and add customized functions to the applications with Nodejs. Except React and Express, we have been using other node moduals to enable more functions in both frontend and backend.

### Frontend

* React Router. Navigate to different areas of the application via the URL path without actually making additional server requests.
* React hooks. Execute code at various points within a component's lifecycle.
* MUI, Ant Design. Two UI libraries based on React.
* Jsencrypt. A good solution to RSA Javascript encryption.

### Backend
* Express Router. Navigate to rescources in the server.
* Jsonwebtoken. Generate and verify the decrypted token containing the user information.
* Mongoose.  A MongoDB object modeling tool designed to work in an asynchronous environment. 

### Database
* Mongodb. A document-oriented database which stores data in JSON-like documents with dynamic schema.

## 📦Getting Started

### Environment Supported

* Install latest [MongoDB](https://www.mongodb.com/3).
* Install latest [Express](https://expressjs.com/).
* Install latest [React](https://reactjs.org/).
* Install latest  [Node.js](https://nodejs.org/en/).

### Installation

1. Clone this repo.

       git clone https://github.com/UOA-CS732-SE750-Students-2022/project-group-enlightened-elephants.git



2. Go to the root directory. And then go to the folders and install all dependencies.

* Install dependencies for frontend.

      cd frontend
      npm install

* Install dependencies for backend.

      cd ../backend
      npm install

### Executing

Go to the root directory.

1. Execute the backend.

       cd backend
       npm start
       
2. Change another terminal and go to the root directory to excute the frontend.

       cd frontend
       npm start

3. Enter `http://localhost:3000` in your browser.

Or Execute in production environment

1. Build the frontend.

       cd frontend
       npm run build
       
2. Excute the backend.

       cd backend
       npm run production

3. Enter `http://localhost:8080` in your browser.

## 🖥Broswer supported

| [<img src="https://cdn.jsdelivr.net/gh/alrra/browser-logos/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br> Edge / IE | [<img src="https://cdn.jsdelivr.net/gh/alrra/browser-logos/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://cdn.jsdelivr.net/gh/alrra/browser-logos/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://cdn.jsdelivr.net/gh/alrra/browser-logos/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari | [<img src="https://cdn.jsdelivr.net/gh/alrra/browser-logos/src/opera/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Opera | [<img src="https://cdn.jsdelivr.net/gh/alrra/browser-logos/src/electron/electron_48x48.png" alt="Electron" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Electron |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                                                                                          Edge 16 / IE 11†                                                                                           |                                                                                                 522                                                                                                  |                                                                                                57                                                                                                |                                                                                                11                                                                                                |                                                                                              44                                                                                              |                                                                                               Chromium 57                                                                                                |

## 🤝Contributors

This project exists thanks to all the people who contribute.

<a href="https://github.com/UOA-CS732-SE750-Students-2022/project-group-enlightened-elephants/graphs/contributors">
  Group Enlightened Elephants
</a>
