# Chat WebSocket
<div align="center">
  <br />
  <img src="https://miro.medium.com/max/2792/1*tWm33yhceKIL22QqOORu2w.png" alt="Logo Socket.io" width="500px" height="250px">
</div>
<h4 align="center">
  Messaging application using Socket.io. Front-end and back-end.
</h4>

## Index Screen
![Index Screen](https://i.imgur.com/yeMzI15.png)

## Chat Screen
![Chat Screen](https://i.imgur.com/nQG4s9i.png)

## 🧪 Tecnologies

This project was developed using cutting edge back-end technologies.

- [Socket.io](https://socket.io/)
- [Express](https://expressjs.com/)
- [TypeScript](https://www.typescriptlang.org/)

## 🚀 Getting started

- You need to install [Node.js](https://nodejs.org/en/download/), [Yarn](https://yarnpkg.com/) and [Docker](https://www.docker.com/products/docker-desktop) to run this project.

**Clone the project and access the folder**

```bash
$ git clone https://github.com/guiathayde/chat-websocket.git && cd chat-websocket
```

**Follow the steps below**

```bash
# Create the container of database with Docker
$ docker run --name chat_websocket -p 27017:27017 -d -t mongo

# Install the dependencies
$ yarn

# Run the project
$ yarn dev
```

- Access the link http://localhost:3000/

<p align="center">Made with 💜 by Guilherme Athayde</p>
