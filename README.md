# Real-Time Location Tracking

This is a real-time location tracking application using **Node.js**, **Express**, **Socket.io**, and **Leaflet.js**. It allows users to share their live locations on a map.

## Features
- Real-time location sharing using **Socket.io**.
- Interactive map using **Leaflet.js** with OpenStreetMap tiles.
- Auto-removal of disconnected users from the map.

## Technologies Used
- **Node.js** (Server-side JavaScript runtime)
- **Express** (Web framework for Node.js)
- **Socket.io** (Real-time communication)
- **Leaflet.js** (Mapping library)
- **EJS** (Template engine for rendering views)
- **HTML, CSS, JavaScript**

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/repo-name.git
   cd repo-name
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server:
   ```sh
   node server.js
   ```
4. Open your browser and visit:
   ```
   http://localhost:3000
   ```

## How It Works
1. When a user opens the web app, their browser requests location access.
2. The geolocation API continuously tracks their position.
3. The location data is emitted to the server using **Socket.io**.
4. The server broadcasts the location to all connected users.
5. The frontend updates the map in real time.
6. When a user disconnects, their marker is removed from the map.

## Project Structure
```
repo-name/
│── public/         # Static files (CSS, JS, images)
│── views/          # EJS templates
│── server.js       # Node.js server with Socket.io
│── package.json    # Project dependencies
│── README.md       # Documentation
```



---
### Contributors
- Your Name ([GitHub Profile](https://github.com/usamata))

