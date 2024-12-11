# MERN Calendar

Calendar web application for adding, editing, deleting or listing other people's events. Developed using the MERN stack.

*API, CRUD, Auth system, JWT, Redux, Calendar.*

## [Try demo](https://mern-redux-calendar.herokuapp.com/)


### Table of contents 📃

- [MERN Calendar](#mern-calendar)
  - [Try demo](#try-demo)
    - [Table of contents 📃](#table-of-contents-)
  - [Starting 🚀](#starting-)
    - [Pre-requirements 📋](#pre-requirements-)
    - [Installation 🔧](#installation-)
  - [Deployment 📦](#deployment-)
  - [Built with 🛠️](#built-with-️)

## Starting 🚀
  
### Pre-requirements 📋

* [Git](https://git-scm.com/)
* [npm](https://www.npmjs.com/)
* [Mongo database](https://www.mongodb.com/)

### Installation 🔧

Local installation:

```bash
# Clone this repository
$ git clone https://github.com/srajiv9496/Calendly-Backend.git

# Change directory to the project path
$ cd Calendly-Backend
```

---

**Server setup:**
```bash
# Change directory to the server path
$ cd Calendly-Backend

# Install dependencies
$ npm install

# Copy .env file
$ cp .env.example .env
```

server **.env** file setup:

```shell
PORT=5000
MONGODB_CNN=mongodb+srv://user:password@clusterrestaurant.rgq1n.mongodb.net/calendar
JWT_SECRET_KEY=RANDOMKEY
```

---

**Client setup:**
```bash
# Go back to the project path
$ cd ..

# Change directory to the client path
$ cd Calendly-Frontend

# Install dependencies
$ npm install

# Copy .env file
$ cp .env.example .env
```

client **.env** file setup:

```shell
REACT_APP_API_URL="http://localhost:5000/api"
```

## Deployment 📦

```bash
# Open terminal in project path and run
$ cd Calendly-Backend
$ npm start


# Open another terminal in project path and run
$ cd Calendly-Frontend
$ npm start
```
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Built with 🛠️

* [React](https://es.reactjs.org/) - Frontend framework
* [React Redux](https://react-redux.js.org/) - State management
* [Node.js](https://nodejs.org/) - Javascript runtime environment
* [Express.js](https://expressjs.com/) - Backend framework
* [MongoDB](https://www.mongodb.com/) - NoSQL database

---
# Calendly-Backend
