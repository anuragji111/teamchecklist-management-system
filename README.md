Collaborative Checklist Management System for Project Teams
Overview

The Collaborative Checklist Management System is a full-stack web application developed using the MERN Stack (MongoDB, Express.js, React.js, Node.js).

The platform helps project teams efficiently manage checklists, assign tasks to members, track completion progress, manage deadlines, and receive notifications for pending tasks.

This system improves team collaboration by providing a centralized environment for task monitoring and workflow management.

----

Problem Statement

In project teams, tracking responsibilities and deadlines can be difficult when tasks are managed manually using spreadsheets or messaging platforms.

This project provides a structured solution where teams can:

Create collaborative checklists
Assign tasks to specific members
Track completion status
Set deadlines
Receive notifications for pending tasks

----

Key Features

User Authentication

Secure login system
Role-based access control

Checklist & Task Management

Create project checklists
Add multiple tasks under each checklist
Assign tasks to team members

Task Tracking

Track task status:
To Do
In Progress
Completed

Deadline Management
Assign deadlines to tasks
Monitor overdue or pending tasks

Notifications

Users receive notifications for:
Newly assigned tasks
Pending tasks
Approaching deadlines

Team Management

Add or remove team members
Assign roles and responsibilities

Dashboard

Displays:

Total tasks
Completed tasks
Tasks in progress
Pending tasks

----

Technology Stack

Frontend

React.js
Tailwind CSS
Redux Toolkit
Headless UI

Backend

Node.js
Express.js

Database

MongoDB (MongoDB Atlas)

----

Project Architecture
client/
  components/
  pages/
  redux/

server/
  controllers/
  models/
  routes/
  middleware/

----

Installation

Clone the repository
git clone https://github.com/YOURUSERNAME/teamchecklist-management-system.git

----

Install dependencies

Server:
cd server
npm install

Client:
cd client
npm install

----

Environment Variables

Server .env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=8800
NODE_ENV=development

Client .env
VITE_APP_BASE_URL=http://localhost:8800

----

Run the Application

Start backend:
cd server
npm start

Start frontend:
cd client
npm run dev

Application runs at:
http://localhost:3000
