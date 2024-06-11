# Agile Project Management Tool

This is a web application built using the MERN stack (MongoDB, Express, React, Node.js). The tool allows both employees and managers to login and manage projects efficiently.

## Features
- **Employee and Manager Login:**
  - Both employees and managers can login to the system.
- **Manager Capabilities:**
  - View all projects.
  - Create new projects.
  - Add employees to projects.
  - Assign tasks to employees.
  - Track the progress of tasks (In Progress, Pending, Done).
- **Employee Capabilities:**
  - View assigned tasks.
  - Update task status (In Progress, Pending, Done).
- **Real-time Updates:**
  - Managers can see the updated status of tasks.

## Installation

Follow these steps to set up the project locally:

### For the client:
- `cd client`
- `npm install`
- `npm start`

### For the server:
- `cd server`
- `npm install`
- `npm start`

## Environment Variables

Create a `.env` file in the server directory and add the following environment variables:

- `PORT=5000`
- `DB=your_database_name`
- `SALT=your_salt_value`
- `JWTPRIVATEKEY=your_jwt_private_key`
- `JWT_SECRET=your_jwt_secret`
- `MONGO_URI=your_mongodb_connection_uri`

1. **Clone the repository**
   ```sh
   git clone https://github.com/Shital9798/Agile-Project-Management-Tool.git
   cd Agile-Project-Management-Tool
