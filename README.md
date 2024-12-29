# MERN Stack School Management System

This is a School Management System built with the MERN Stack (MongoDB, Express, React, Node). The frontend is developed with React and Vite, with styling done using styled-components.

## Features

- **Admin Dashboard:** Administrators can manage student records, teacher information, courses, exams, assignments, track student attendance, add teachers, and view school performance metrics.
- **Student Dashboard:** Students have access to their own dashboard where they can view their class schedules, assignments, submit assignments, and track their academic progress.
- **Teachers Dashboard:** Teachers can manage class schedules, assign and grade exams and assignments, and view student performance metrics.

### Operations

- **Adding Students:** Admins can add new student records, including personal details and academic information.
- **Class Management:** Admins can create and manage classes, assign teachers, and schedule classes.
- **Exam Management:** Teachers can create and manage exams, assign them to classes, and grade student submissions.
- **Assignment Management:** Teachers can create assignments, assign them to classes, and track student submissions.
- **Student Submission:** Students can submit assignments through the student dashboard.
- **Adding Teachers:** Admins can add new teachers to the system.
- **School Performance Metrics:** Admins can view various metrics related to the school's performance.

## Technologies

- **Frontend:** React, Vite, Styled-components
- **Backend:** Node, Express
- **Database:** MongoDB
- **Authentication:** JSON Web Token (JWT)

## Setup Instructions

1. **Get source code:**

Clone repository or download zip file and unzip.

2. **Install dependencies:**

`cd` into project directory
Run `npm i` or `npm install`


3. **Set up environment variables:**

- Create `.env` file in root directory.
- Define the following environment variables:

  ```
  PORT=4000
  MONGODB_URI=your_mongodb_connection_string
  SECRET_KEY=your_secret_key_for_jwt
  ```

4. **Run development servers:**

- Start frontend server:

  npm run dev

- Start backend server:

  npm start

5. **Access application:**

Open browser and navigate to `http://localhost:5173` for frontend and `http://localhost:4000` for backend.