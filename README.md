# Barebones Multi Core RTMP Relay Server

To handle live streams from the drone and have OpenCV reading it.

## Installation

Clone/download this repo into a directory.
Run `npm install` to setup all the dependencies.

## Usage

1. Start the server.
```
npm run start
```

2. Connect the drone to the RTMP server. Any path may be chosen, but consistency is a must. E.g. stream to `rtmp://192.168.1.212/live/stream`

3. Read the same stream with any software that supports RTMP (OpenCV support requires FFMPEG). VLC stream with `rtmp://127.0.0.1/live/stream`

4. Profit????
