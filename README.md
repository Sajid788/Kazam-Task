# Kazam Task Management Application

This project is a full-stack task management application built with React for the frontend and Node.js (Express) for the backend.

## Project Structure

The project is divided into two main parts:

- **Frontend**: React application with Tailwind CSS for styling
- **Backend**: Express.js API with MongoDB, Redis, and MQTT integration

## Quick Start

### Prerequisites

- Node.js 
- MongoDB
- Redis
- MQTT Broker (e.g., Mosquitto)

### Installation and Setup

1. Clone the repository
   ```bash
   git clone <repository-url>
   cd Kazam-Task
   ```

2. Set up the backend
   ```bash
   cd backend
   npm install
   # Configure your environment variables in .env file
   npm run dev
   ```

3. Set up the frontend
   ```bash
   cd frontend
   npm install
   npm start
   ```

4. Access the application at `http://localhost:3000`

## Features

- Create, read, update, and delete tasks
- Real-time updates via MQTT
- Data caching with Redis
- Responsive UI built with React and Tailwind CSS

## Documentation

For detailed information:
- See [frontend README](./frontend/README.md) for frontend details
- See [backend README](./backend/README.md) for backend details 