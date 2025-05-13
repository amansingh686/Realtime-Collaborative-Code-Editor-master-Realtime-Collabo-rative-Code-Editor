# Sync Code: Realtime Collaborative Code Editor

## Introduction

Are you tired of sending code snippets back and forth, struggling to debug and collaborate with your team? Look no further! **Sync Code** is here to revolutionize the way you code together. This powerful and intuitive collaborative code editor is designed to empower developers, and teams to work seamlessly in real-time, regardless of their location. With **Sync Code**, you can code together, debug together, and ship faster, together.

## Features

- Multiple users can join a room and edit code together
- Changes are reflected in real time
- Copy button to copy the room id to clipboard
- Leave button to leave the room
- Supports syntax highlighting for different programming languages
- Users can choose theme based on their preferences
- Users can leave the room and rejoin later to continue editing
- Joining & leaving of users is also reflected in real time

### Prerequisites

- Node.js (v20.11.1 or later)
- npm (10.2.4 or later)

## Tech Stack

- React.js
- Node.js
- Express.js
- Socket.io
- CodeMirror
- React-Toastify

## Installation and Running

1. Clone this repository:
```bash
git clone https://github.com/amansingh686/Realtime-Collaborative-Code-Editor.git
cd Realtime-Collaborative-Code-Editor
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with the following content:
```
REACT_APP_BACKEND_URL=http://localhost:5000
SERVER_PORT=5000
```

4. Run the project (this will start both frontend and backend):
```bash
npm run dev
```

5. Open your browser and go to `http://localhost:3000`

6. To use the editor:
   - Click on "Create New Room" to create a new room
   - Copy the Room ID
   - Share the Room ID with others to collaborate
   - Others can join by entering the Room ID and their username

## How to Use

1. **Creating a Room:**
   - Click on "Create New Room"
   - Enter your username
   - Copy the Room ID

2. **Joining a Room:**
   - Enter the Room ID
   - Enter your username
   - Click "Join"

3. **Collaborating:**
   - All changes are synced in real-time
   - You can see who's in the room
   - You can leave and rejoin anytime

## Troubleshooting

If you encounter any issues:

1. Make sure all dependencies are installed:
```bash
npm install
```

2. Check if the ports 3000 and 5000 are available

3. If you get any errors about missing modules:
```bash
npm install
```

4. If the server doesn't start:
```bash
npm run server:dev
```

5. If the frontend doesn't start:
```bash
npm start
```

## About Me

I am Aman Singh, a Computer Science Engineering Student from Greater Noida, Uttar Pradesh. I am passionate about coding and currently learning JavaScript, React, and Node.js.

## Connect with me

- [GitHub](https://github.com/amansingh686)
- [LinkedIn](https://www.linkedin.com/in/aman-singh-95a200264)
- [Instagram](https://www.instagram.com/aman_singh686)
- [Facebook](https://www.facebook.com/profile.php?id=61556237048289)

**Email:** kuahsingh0103@gmail.com
