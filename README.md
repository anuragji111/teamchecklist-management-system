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

----
## 📷 Project Screenshots:

1. Log-In.jpg :
   <img width="1860" height="942" alt="1  Log-In" src="https://github.com/user-attachments/assets/d0931dc6-0b3a-4cc6-92da-035d0e68f2ad" />

2. Dashboard.jpg:
   <img width="1898" height="962" alt="2  Dashboard" src="https://github.com/user-attachments/assets/8cbbdcf3-af36-46ad-8f16-65ff319ccb84" />

2-i. Dashboard.jpg:
   <img width="1919" height="1021" alt="2-i  Dashboard" src="https://github.com/user-attachments/assets/4dd5f21a-f58f-4afc-896d-854f1abc8236" />

3. Project Checklist.jpg:
  <img width="1884" height="1020" alt="3  Project Checklist" src="https://github.com/user-attachments/assets/a0d10cfa-0a04-445e-bd7d-c561fce4020e" />

4. Add Checklist Items.jpg:
   <img width="1919" height="1017" alt="4  Add Checklist Items" src="https://github.com/user-attachments/assets/10d154b2-58fa-4273-a38a-1a8857cd4b7c" />

5. List View.jpg:
   <img width="1899" height="1024" alt="5  List View" src="https://github.com/user-attachments/assets/50f7aab8-61c9-4a77-8609-9c0bb1ea7fa6" />

6. Completed Tasks.jpg:
   <img width="1351" height="1023" alt="6  Completed Tasks" src="https://github.com/user-attachments/assets/fb316223-bd31-4144-afa1-0825d9fee729" />

7.  In Progress Tasks.jpg:
   <img width="1919" height="1015" alt="7  In Progress Tasks" src="https://github.com/user-attachments/assets/f44915e8-550f-477c-a413-1cf2d11aebde" />

8. Project Team Members.jpg:
   <img width="1896" height="1017" alt="8  Project Team Members" src="https://github.com/user-attachments/assets/a6ea7a89-1fa3-4824-8e91-2ade93ed12ca" />

9. Add Team Members.jpg:
    <img width="1438" height="1027" alt="9  Add Team Members" src="https://github.com/user-attachments/assets/6cf2c984-52ed-48d5-a278-571a056b1541" />

10. Deleted Checklists.jpg:
    <img width="1917" height="1019" alt="10  Deleted Checklists" src="https://github.com/user-attachments/assets/bb9e6810-39da-4d0d-b975-e55644db2c14" />

11. Notifications and alerts.jpg:
    <img width="733" height="720" alt="11  Notifications and alerts" src="https://github.com/user-attachments/assets/4dcd4921-a267-4b66-9062-ea012a9ee75c" />

12. Profile Update.jpg:
    <img width="1884" height="1033" alt="12  Profile Update" src="https://github.com/user-attachments/assets/bb8aef89-54f5-466f-ace0-428b082161e1" />

13. Change Password feature.jpg:
    <img width="1919" height="1022" alt="13  Change Password feature" src="https://github.com/user-attachments/assets/42042829-8eaf-4d29-a496-4cc7eca627c1" />

14. Mongodb Data Collections.jpg:
    <img width="1919" height="1022" alt="14  Mongodb Data Collections" src="https://github.com/user-attachments/assets/3d850c92-722e-46fd-b3d7-7ca1fcc99921" />

15. Frontend-code-1.jpg:
    <img width="1847" height="1032" alt="15  Frontend-code-1" src="https://github.com/user-attachments/assets/acda7b77-592a-45ee-aa71-083675a46135" />

15. Frontend-code-2.jpg:
    <img width="1703" height="1032" alt="15  Frontend-code-2" src="https://github.com/user-attachments/assets/9fed2e38-772a-4cd0-b427-bf74d339cb5d" />

16. Backend-code-1.jpg:
    <img width="1799" height="1030" alt="16  Backend-code-1" src="https://github.com/user-attachments/assets/08d8a48a-96a5-4883-b57d-e0d2af735673" />

17. Combined-frontend-backend-code-1.jpg:
    <img width="1845" height="1031" alt="17  Combined-frontend-backend-code-1" src="https://github.com/user-attachments/assets/dcb1b951-1e87-4e6c-a760-76da56ebd8a8" />

18-i. Render-backend-deploy-hosting.jpg:
    <img width="1861" height="1021" alt="18-i  Render-backend-deploy-hosting" src="https://github.com/user-attachments/assets/36e3f8c6-c7cc-4c77-baca-293e929c8a8b" />

18-ii. Render-backend-deploy-hosting.jpg:
    <img width="1919" height="1025" alt="18-ii  Render-backend-deploy-hosting" src="https://github.com/user-attachments/assets/96edbca5-c6fe-4470-b9bd-fb9ef0cef4a0" />

19-i. Vercel-frontend-deploy-hosting.jpg:
   <img width="1905" height="1023" alt="19-i  Vercel-frontend-deploy-hosting" src="https://github.com/user-attachments/assets/c74f7572-3ff4-4d35-8592-0907e6c568f2" />

19-ii. Vercel-frontend-deploy-hosting.jpg:
   <img width="1904" height="1019" alt="19-ii  Vercel-frontend-deploy-hosting" src="https://github.com/user-attachments/assets/6e841c2f-54f1-412f-b7c5-f9fbad127e55" />

20-i-github.jpg:
   <img width="1918" height="1027" alt="20-i-github" src="https://github.com/user-attachments/assets/8d77068a-feee-4e3b-858c-607f2ccd16ab" />

20-ii-github.jpg:
   <img width="1892" height="1023" alt="20-ii-github" src="https://github.com/user-attachments/assets/bbd513af-294e-4ce0-80a9-981a0ad18263" />

----
## 📷 Frontend Documentation Pictures:

1. Component Design:
   <img width="1911" height="593" alt="Component Design" src="https://github.com/user-attachments/assets/c4ec51f8-42f5-4a01-8604-dbaecad8cbe0" />

2. Frontend Architecture Diagram:
   <img width="776" height="1385" alt="Frontend Architecture Diagram" src="https://github.com/user-attachments/assets/84fe1921-ff9e-4b5b-b0e6-71ec5b65ef33" />

3. Hosting & Live Deployment:
   <img width="1004" height="192" alt="Hosting   Live Deployment" src="https://github.com/user-attachments/assets/87f3afe8-1a5a-428c-b1b5-994655a8ad95" />

4. User Interface Features:
   <img width="1514" height="998" alt="User Interface Features" src="https://github.com/user-attachments/assets/ede47804-e22c-40e8-a739-fa63c2b6ec24" />

----
## 📷 Backend Documentation Pictures:

1. Authentication & Basic Security:
   <img width="855" height="1473" alt="Authentication   Basic Security" src="https://github.com/user-attachments/assets/4f1e111a-ec52-42a5-bedf-2840ede70549" />

2. Backend Architecture & API Design:
   <img width="1434" height="506" alt="Backend Architecture   API Design" src="https://github.com/user-attachments/assets/360a7494-018a-4e1c-815f-6642bd641738" />

3. Database Design & Data Handling:
   <img width="978" height="606" alt="Database Design   Data Handling" src="https://github.com/user-attachments/assets/9d6e05b1-c915-409c-8117-959524a52140" />

4. Hosting & Live Deployment:
   <img width="1358" height="229" alt="Hosting   Live Deployment" src="https://github.com/user-attachments/assets/3968c9b3-fe96-4b93-9f49-07aab8ea7e55" />

5. System Architecture-diagram:
   <img width="967" height="300" alt="System Architecture-diagram" src="https://github.com/user-attachments/assets/4a9a4a6a-5fd5-4a36-ac44-c5ccb6b0e217" />

----
## 📷 PPT Technology Stack:
 <img width="696" height="594" alt="Technology Stack" src="https://github.com/user-attachments/assets/ed78075f-a7ad-4dd7-97be-08f531af92bd" />

 Thank you.
