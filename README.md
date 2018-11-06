# Computer-Networks---Lab-10

Project Description:
For our project, we intend to explore the application layer and its uses in the realm of multimedia. For this project we intend to build a multimedia server. To achieve this goal, we decided to implement the client-server model so that multiple clients can store photos and videos in the same place (the server).

To send data back and forth between client and server, we will use a TCP connection in order to ensure reliability. Reliability is important in transmitting a user’s multimedia data because we want to ensure that a user would not lose or their data or have it corrupted when uploading to or downloading from the server.

The server will have the following features:
- Store photos/videos sent to it, with a name specified by the client
- Send a specific photos/videos upon client’s request
- Send a list of the stored photos/videos upon the client’s request

The client will have the following features:
- Send specific photos/videos to be stored along with the media’s name
- Request and download photos/videos from the server
- Request a list of the stored photos/videos upon the client’s request
