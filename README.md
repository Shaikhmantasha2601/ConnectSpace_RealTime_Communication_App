# ConnectSpace
Advanced Task 4 real-time communication app.

Features: multi-user WebRTC video, screen sharing, Socket.IO signaling, encrypted chat/files with browser AES-GCM, live whiteboard, JWT authentication, bcrypt passwords, participants/presence and responsive advanced UI/UX.

## Windows
```cmd
npm install
npm run install:all
copy server\.env.example server\.env
npm run dev
```
Open http://localhost:5173. Register two users and join the same room from two browser windows. Allow camera/microphone.

Production: HTTPS + TURN server + database + object storage + SFU (LiveKit/mediasoup) + rate limiting.
