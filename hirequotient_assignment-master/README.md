# MERN Auth & Chat App

### NodeJS - Express - JWT -  Socket.io - MongoDB - React - React Router - Context API - TailwindCSS

This is a perfect example for a MERN stack real-time chat application with authentication & authorization.

Basically, it consists of 2 parts as the follows:
- Real-time chat application using socket.io in node.js(Express)
- JWT Authentication & Authorization stored in HTTP-only cookie






## Usage
- Create a MongoDB database and obtain your `MongoDB URI` - [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register)


### Env Variables

Rename the `server/.env.example` file to `.env` and add the following

```
PORT=5000
MONGO_URI=
JWT_SECRET_KEY=
```

Change the JWT_SECRET to what you want

### Install Dependencies (backend & frontend)
```
cd server
npm install
```
```
cd socket
npm install
```
```
cd client
npm install
```
### Run locally

```
# Run API server
cd server
npm run dev
```
```
# Run socket server
cd socket
npm run dev
```
```
# Run frontend
cd client
npm run dev
```
## Build & Deploy
```
cd client/ && npm install && npm run build && cd .. && cd server/ && npm install && npm run start
```



Happy coding 🔥
