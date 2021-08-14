# MRwR Stream - Client folder

This project comes from Modern React with Redux by Stephen Grider.

In order to run the complete project, you will need to have `MRwR-streams-api` and `MRwR-streams-rtmpserver` running together with this client.

This project uses create-react-app and you can either use NPM or YARN to run the project.

- (NPM): `npm run start`
- (YARN): `yarn start`

The whole purpose of this project is to explore the React and Redux working together to use CRUD (Create streams, Read streams, Update the streams and Delete those streams) and have a quick JSON Server as a database to keep track of your stream info and using RTMP server to connect to OBS to allow streaming on the appropriate streams id.

- When using OBS (please install first in your computer) and want to show your stream in the appropriate stream link then simply go to 

  Settings > Streams > change service to Custom... , Server: rtmp://localhost/live and the StreamKey: <id> and Save.
  
- For your Sources in OBS, you can add your Display Capture and Audio Input Capture in order to show video and audio from your display.
  
After all that is done, simply click on Start Streaming and go to http://localhost:3000/streams/:id and press play on the video player and it should show your stream live.
  
Remember, the API and RTMP server need to be running in conjunction with the Client server. You can get those under MRwR-streams-api and MRwR-rtmpserver

