# Kazam Task Management - Backend API

This is the backend server for the Kazam Task Management application, built with Node.js, Express, MongoDB, Redis, and MQTT.

## Tech Stack

- Node.js & Express
- MongoDB (via Mongoose)
- Redis for caching
- MQTT for real-time communication

## Features

- RESTful API endpoints for task management
- MongoDB database integration
- Redis caching for improved performance
- MQTT integration for real-time updates

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (local or Atlas)
- Redis server
- MQTT broker (e.g., Mosquitto)

### Installation

1. Install dependencies:
   ```bash
   npm install
   ```

2. Create a `.env` file in the root directory with the following content:
   ```
   PORT=3001
   MONGO_URI=mongodb://localhost:27017/kazam-tasks
   REDIS_URL=redis://localhost:6379
   MQTT_BROKER=mqtt://localhost:1883
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. The API will be available at `http://localhost:3001`

## API Endpoints

### Tasks

- `GET /api/tasks/fetchAllTasks` - Get all tasks
- `POST /api/tasks` - Create a new task

## Project Structure

- `server.js` - Entry point
- `config/` - Configuration files for MongoDB, Redis, and MQTT
- `controllers/` - Request handlers
- `models/` - MongoDB schemas
- `routes/` - API route definitions
- `services/` - Business logic

## Deployment

The backend can be deployed to platforms like Vercel, Heroku, or any Node.js hosting service.

For Vercel deployment, a `vercel.json` configuration file is already included.

## Scripts

- `npm start` - Start the production server
- `npm run dev` - Start the development server with nodemon 
