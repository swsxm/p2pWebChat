# ChatWebapp

A  Peer2Peer-based chat application built with **React** and **Express**. 

## 🚀 Features

- **User Accounts:** Sign-up and login functionality.
- **Direct Messaging:** Private 1-on-1 chats between users.
- **Global Group Chat:** An "All-Chat" feature for public group discussions.


## 📦 Installation & Setup

You can run the entire application stack using Docker.

1. **Prerequisites**
   Make sure you have [Docker](https://www.docker.com/) installed on your machine.

2. **Configuration**
   Navigate to the project root and create your environment file:
   ```bash
   cp .env_example .env
   ```
3. **Start the application**
   Run the following command to build and start the containers:
   ```
   docker-compose up
   ```
4. **Access**
   Once the container is running, the web app is accessible via the NGINX port (Default: 4000). Open your browser and visit: ``` http://localhost:4000 ```
