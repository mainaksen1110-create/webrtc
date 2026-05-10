# Real-Time WebRTC Video Calling App

A peer-to-peer real-time video calling application built using WebRTC.

## Features
- Real-time video/audio communication
- Peer-to-peer connection using WebRTC
- Socket.IO signaling server
- TURN/STUN support for NAT traversal
- Dynamic room creation and joining
- Low-latency communication

## Tech Stack
- Node.js
- Express.js
- Socket.IO
- WebRTC
- Twilio TURN Server

## How It Works
1. Users join a room
2. Socket.IO exchanges SDP offers/answers and ICE candidates
3. WebRTC establishes direct peer-to-peer communication
4. TURN server ensures connectivity across restricted networks

## Future Improvements
- Screen sharing
- Chat messaging
- Recording support
- Authentication
- Group video calls
