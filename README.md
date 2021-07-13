# [Connect](https://connect-call.herokuapp.com/)
![banner](https://github.com/swarnalii/connect-call/blob/main/imgs/banner.png)

This project is made as a submission to  Microsoft Engage 2021 Program. It is a video calling application built using webRTC and socket.io.

### Features:

1. Automatically generates unique room link everytime we click on the [link](https://connect-call.herokuapp.com/), which can be shared with other people.
2. Supports one to many video call. 
3. Participants can switch on/off their audio and video during the call.
4. Has chat box which lets the participants chat during the call.
5. Participants can share their screen.
6. A particular participant's video can be enlarged.
7. Has a simple whiteboard which participants can use while screen sharing to explain something.
8. Can leave the room and rejoin with one click.


### Tech Stack:

- For Frontend: HTML5, CSS3 and JS.
- For backend: Nodejs, express
- webRTC mesh for video call
- socket.io to enable real-time, bidirectional and event-based communication.


### Screenshots:

![home](https://github.com/swarnalii/connect-call/blob/main/imgs/home.png)

![chat-box](https://github.com/swarnalii/connect-call/blob/main/imgs/chat.png)

![screen-share](https://github.com/swarnalii/connect-call/blob/main/imgs/screenshare.png)

![whiteboard](https://github.com/swarnalii/connect-call/blob/main/imgs/whiteboard.png)

![endCall-page](https://github.com/swarnalii/connect-call/blob/main/imgs/endCall.png)

### Running this on local device:

- Fork this repo and clone it in your device
- Change the directory by running `cd connect-call` in the terminal
- Install dependencies using the command `npm install`
- Run the app using `npm start` command
- It will start locally on http://localhost:3000/ .

### [Link to the presentation](https://docs.google.com/presentation/d/1kaEKs6AwtHho0aQQarlb_QneTzoGqpaKH6s645KMzvw/edit?usp=sharing)

### Resources:

- Video calling app inspired from [talk](https://github.com/vasanthv/talk)
- [Whiteboard Tutorial](http://www.williammalone.com/articles/create-html5-canvas-javascript-drawing-app/)


