# WebRTC Video Call Project

This project is a basic setup for a WebRTC application, allowing video calls between devices on the same network or over the internet using webrtc and socket.io .

## Getting Started

Follow these steps to set up and run the project:

### 1. Install Dependencies

Run the following command to install the necessary dependencies:

```bash
npm install
```

### 2. Start the Server
Start the server by running the following command:

```bash
npm start
```

### 3. Access the Application
Once the server is running, open your browser and go to:

```bash
http://localhost:9000
```
### 4. Connect with Another Device
  To connect to another device on the same network, use the following steps:
  Download and install ngrok.
  Run the following command to expose your local server to the internet:
  
```bash
ngrok http http://localhost:9000
```
ngrok will provide a public URL (e.g., https://abcdef.ngrok.io). Share this URL with the other device to connect.




