# Fullstack Task Manager (MERN)

## Overview
This web application, a Cloud-Based Task Manager, employs the MERN stack (MongoDB, Express.js, React, and Node.js) to enhance team task management. It offers a streamlined, intuitive interface for task allocation, monitoring, and collaborative efforts. Features are tailored for both administrators and users, aimed at boosting productivity and organizational effectiveness.

### Why/Problem?
Effective task management is essential in dynamic work settings for team success. Traditional task management techniques like spreadsheets or manual tracking can lead to inefficiencies and errors. This application serves as a solution by offering a unified platform that facilitates smoother collaboration and workflow enhancements.

### Background:
The shift towards remote work and geographically dispersed teams has increased the demand for effective communication and task coordination tools. The Cloud-Based Task Manager utilizes contemporary web technologies to provide a responsive and easy-to-use task management system. It employs the MERN stack for scalability and integrates technologies like Redux Toolkit, Headless UI, and Tailwind CSS to boost performance and user experience.

### Admin Features:
1. **User Management:**
   - Establish and manage admin accounts.
   - Add and oversee team members.

2. **Task Assignment:**
   - Allocate tasks to individuals or groups.
   - Modify task details and update statuses.

3. **Task Properties:**
   - Categorize tasks by status (todo, in progress, completed).
   - Set priority levels (high, medium, normal, low).
   - Organize sub-tasks.

4. **Asset Management:**
   - Manage uploads of task-related assets, such as images.

5. **User Account Control:**
   - Enable or disable user accounts.
   - Permanently remove or temporarily disable tasks.

### User Features:
1. **Task Interaction:**
   - Modify the status of tasks (in progress or completed).
   - Access detailed task information.

2. **Communication:**
   - Engage in discussions or chat within task activities.

### General Features:
1. **Authentication and Authorization:**
   - Secure user login.
   - Implement role-based access controls.

2. **Profile Management:**
   - Update personal user profiles.

3. **Password Management:**
   - Securely change passwords.

4. **Dashboard:**
   - Display summaries of user activities.
   - Sort tasks by status (todo, in progress, completed).

### Technologies Used:
- **Frontend:**
  - React (Vite)
  - State management with Redux Toolkit
  - Headless UI
  - Tailwind CSS

- **Backend:**
  - Express.js on Node.js
  
- **Database:**
  - MongoDB for scalable data storage.

This innovative platform leverages the MERN stack and cutting-edge frontend technologies to deliver a cohesive and efficient task management experience for both administrators and regular users, promoting better collaboration and productivity.

## SETUP INSTRUCTIONS

### Server Setup

#### Environment Variables
Begin by creating a `.env` file in the server directory with these entries:
- MONGODB_URI = `your MongoDB URL`
- JWT_SECRET = `any secure key`
- PORT = `8800` or other
- NODE_ENV = `development`

#### Set Up MongoDB:
1. Navigate to the MongoDB Atlas website to create an account and configure your cluster.
2. After deployment, create a database user, set up IP whitelisting, and establish a connection to the cluster.
3. Update your application’s `.env` file with the MongoDB connection URL.

### Steps to Run Server:
1. Open the project in your preferred editor.
2. Change to the server directory `cd server`.
3. Install dependencies with `npm i` or `npm install`.
4. Start the server using `npm start`. Check for confirmation messages indicating successful server launch and database connection.

### Client-Side Setup

#### Environment Variables
Create a `.env` file in the client folder including:
- VITE_APP_BASE_URL = `http://localhost:8800`
- VITE_APP_FIREBASE_API_KEY = `Firebase api key`

### Steps to Run Client:
1. Move to the client directory `cd client`.
2. Install required packages with `npm i` or `npm install`.
3. Launch the app with `npm start` and access it at [http://localhost:3000](http://localhost:3000).
