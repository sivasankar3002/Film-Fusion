Video Streaming Application
This project demonstrates how to build a video streaming backend using Node.js and Express.js, and a video streaming client using React and the Video.js library. The backend allows users to upload video files, converts them to HLS format using FFmpeg, and streams them to the client. The client plays the streamed video using Video.js.
## Description

FILM FUSION is a video streaming application that allows users to upload video files, convert them to HLS format using FFmpeg, and stream them to the client. The client side is built using React and the Video.js library.

## Features
- Upload video files
- Convert videos to HLS format using FFmpeg
- Stream videos to the client
- Adaptive bitrate streaming
- Video playback using Video.js

## Prerequisites
- Node.js (>=14.x)
- npm (>=6.x)
- FFmpeg (installed and added to PATH)
- Git (for cloning the repository)

Project Structure 

  FILM FUSION/
├── frontend/
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── assets/
│   │   ├── App.css
│   │   ├── App.jsx
│   │   ├── index.css
│   │   ├── main.jsx
│   │   └── VideoPlayer.jsx
│   ├── .eslintrc.cjs
│   ├── .gitignore
│   ├── bun.lockb
│   ├── package.json
│   ├── package-lock.json
│   ├── README.md
│   ├── vite.config.js
│   └── index.js
└── PROBLEMS/





Clone the repository
Install dependencies:
npm install


Run the backend server:
npm start

Usage
Upload a video file via the upload route /upload.
The backend will convert the video to HLS format and return a URL for the HLS playlist.
Use the provided URL in the React client to stream and play the video.
Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature-name).
Commit your changes (git commit -m 'Add your feature').
Push to the branch (git push origin feature/your-feature-name).
Create a Pull Request.
