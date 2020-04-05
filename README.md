# video-chat
> Video chat application using [VueJS](https://vuejs.org), [Vuex](https://vuex.vuejs.org), [WebRTC](https://webrtc.org/start/), [SocketIO](https://socket.io), NodeJS and [Redis](https://github.com/NodeRedis/node_redis)

## Thanks 
This code is based on https://github.com/adrigardi90/video-chat, if you want to test with a docker container, please feel free to check this repo
https://levelup.gitconnected.com/build-your-own-video-chat-with-vue-webrtc-socketio-node-redis-eb51b78f9f55

## Quick start
First of all, you need to install and run the redis in your PC. Here there is an [article](https://medium.com/@petehouston/install-and-config-redis-on-mac-os-x-via-homebrew-eb8df9a4f298) for Mac OS X. Once Redis is up and running:

```bash
# Clone the repo
git clone https://github.com/edgardojs/video-chat

# Change into the repo directory
cd video-chat

# install
npm install 

# Start the FE in dev mode
npm run serve

# Start the server
npm run run:server

```
Then visit http://localhost:8080 in your browser, open another incognito Chrome tab for testing.