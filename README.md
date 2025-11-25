# Traffic Light Queue Simulation
A DSA-based Smart Traffic Simulation using C++, HTML/CSS/JS, and Node.js<br>
This project was developed as part of the **Mastering Data Structures and Algorithms** Summer Training at **Lovely Professional University**.

## About the Project
The Traffic Light Queue Management System is a real-time traffic simulation designed to tackle modern urban challenges like congestion, long waiting times, and delay in emergency response.
It uses Data Structures and Algorithms to simulate multi-lane traffic, prioritize emergency vehicles, and dynamically manage queue clearance.<br>

## Project Overview
The Traffic Light Queue Management System is a real-time simulation built using C++ and data structures to model multi-lane traffic flow and prioritize emergency vehicles.
It demonstrates how DSA concepts like linked lists and priority queues can be applied to optimize traffic signal behavior in a realistic, interactive environment.
The frontend interface and Node.js middleware were developed with the help of ChatGPT, enabling smooth user interaction and seamless communication with the C++ backend.

## System Architecture
The system has three major components
### 1. Frontend (HTML, CSS, JS)
- Accepts number of lanes, vehicle inputs, signal durations
- Displays simulation results

### 2. Backend (C++) - Contains core simulation logic
- Linked list, Priority queue, Dynamic queue handling
- Manages: Vehicle entry, Emergency handling, Lane-wise signal logic

### 3. Middleware (Node.js)
- Sends user input to C++ executable
- Receives and displays output
- Handles compilation and I/O

## How to Run the Project
- Open Terminal and navigate to project folder - cd TrafficQueueSimulation
- Initialize Node project - npm init -y
- Install Express - npm install express
- Compile the C++ backend - g++ Simulation.cpp -o Simulation.exe
- Start the Node.js server - node traffic_sim.js
- Open browser and visit - localhost:3000

## Snapshots
### Simulation Web Interface
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/c6ff240a-476e-40eb-8211-b3b3d1a48b1f" />

### User Input - Vehicle Addition
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/13bb8a19-6adf-4eb2-930f-59c6ac2d4160" />

### Simulation Result
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/eb90769c-d2d2-4c4e-9b8f-e81b89f6a313" />

## Acknowledgement
I extend my sincere gratitude to **Lovely Professional University** and the **Centre for Professional Enhancement (CPE)** for providing the summer training opportunity.<br>
A special thanks to **Dr. Mukesh Sharma Sir** for his valuable guidance, continuous support, and technical mentoring throughout the development of this project.
