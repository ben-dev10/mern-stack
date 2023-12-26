# mern-stack-tutorial

A fullstack app built with the MERN stack: actually a tutorial from YouTube, Net Ninja: MERN-STACK TUTORIAL.

## Getting Started

This project consists of a frontend built with react and the backend folder consists of a backend server and a database server.

To get started, first install the dependencies separately for both the frontend and backend folders with:

```bash
npm i
```

### Backend

You can setup the database server online for free with Mongodb Atlas or you can host one locally yourself. You can do so in a few steps.

1. Download the mongodb installer for your platform (this only installs the database server). In addition, you can install the cli tool `mongosh` or the GUI `Mongodb Compass`.
2. In the root folder of this project run:

```bash
cd backend && cd backend && mongod --port 3030 # starts the database server
```

3. Then in a new terminal run:

```bash
npm run dev # starts the backend server
```

### Frontend

At the root folder, run the following to start the react server:

```bash
npm run dev
```

> Note: Replace the port number and the mongodb connection string with yours in order to make all this work.
