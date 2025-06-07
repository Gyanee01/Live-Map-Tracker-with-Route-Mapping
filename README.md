# Real-Time Tracker


## Description
This is a real-time device tracking system built with Node.js, Express, Socket.io, and Leaflet.js. It allows multiple users (or devices) to share their location live, and plots these locations on a map in the browser. The app updates user positions in real time using WebSockets.
I have searched for this project on internet and have many inspirations for this project due to which i learned and gained experience in industry-level like project.I did not made this entire project on my own.

## Features
- Live location sharing using Socket.io
- Leaflet.js map integration
- Real-time updates for all connected users
- Display and track multiple users on the same map

## Technologies Used
- Node.js
- Express.js
- Socket.io
- EJS (template engine)
- Leaflet.js (map rendering)
- HTML/CSS/JavaScript

## Getting Started

### Prerequisites

- Node.js installed on your machine.
- npm (Node package manager).

To run the application with automatic reloading, use `nodemon`:

1. Make sure you have `nodemon` installed globally:
   ```bash
   npm install -g nodemon

   Start the application:
   npx nodemon app.js



## Installation

1. Clone the repository:
git clone https://github.com/Gyanee01/Fleet-Management-System-MERN-Stack-.git
cd Realtime_Tracker-main

2. Install dependencies:
npm install

3. Run the server:
node app.js

4. Open your browser and go to:
http://localhost:3000


## Usage

- Open the app in two browser tabs or different devices.
- Each one will appear on the map with a different marker.
- As you move (if using real GPS or simulated via script), the marker updates live.
- Routes can be implemented using additional logic (e.g., integrating with OpenRouteService or Google Maps API).



---

Built with ❤️ using Node.js and Leaflet


