# Colosseum

Colosseum is a collaborative video watching platform that facilitates synchronized viewing experiences among multiple users. It offers seamless synchronization of video playback, including play, pause, and seek functionalities, ensuring that all viewers are in sync. The platform supports various sources for video content, including screen sharing, online videos accessible via HTTP, and YouTube videos. Users can create separate rooms on demand, each with its own set of features and participants.

## Key Features

- **Synchronized Viewing**: Watch videos together in real-time with synchronized playback controls.
- **Multiple Content Sources**: Supports screen sharing, online videos, and YouTube videos.
- **Room Creation**: Users can create separate rooms as needed for different viewing sessions.
- **Text Chat**: Engage in text-based communication within the viewing room.
- **Video Chat**: Enable video communication alongside video watching for enhanced interaction.

## Quick Start

1. **Installation**: Install npm dependencies by running `npm install`.
2. **Server Start**: Start the server with `PORT=8080 npm run dev`. Customize the port using the `PORT` environment variable.
3. **Client Start**: Launch the React application in a separate shell with `PORT=3000 npm run start`. Point to the server using `REACT_APP_SERVER_HOST` environment variable if customized.
4. **Configuration**: Duplicate `.env.example`, rename it to `.env`, and add necessary configurations as described in the advanced setup.

## Advanced Setup

- **YouTube API Integration**: Obtain a YouTube API key and add it to the `.env` file for video search functionality.
- **Firebase Authentication**: Set up Firebase for user authentication by providing Firebase SDK configuration in the `.env` file.

## Technologies Used

- **React**: Frontend development framework for building user interfaces.
- **TypeScript**: Superset of JavaScript for type-checking and improved code quality.
- **Node.js**: Backend JavaScript runtime environment for server-side logic.
- **Socket.io**: Real-time communication library enabling synchronized actions among clients.
- **Docker**: Containerization platform for packaging applications and their dependencies.
- **PostgreSQL**: Relational database management system for storing application data.

By combining these technologies, Colosseum delivers a seamless and interactive platform for synchronized video watching and communication.
