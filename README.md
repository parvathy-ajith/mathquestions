
# mathquestions

## Overview
Question Bank for Mathematics.
This is a platform designed for students and teachers to collaborate and enhance learning. Students can access a wide range of math problems, practice solving them, and track their progress. Teachers can easily add new questions, categorize them by topic or difficulty, and manage the question bank. The site is user-friendly, helping students improve their math skills while allowing teachers to contribute and monitor performance.

Developed as Full-Stack MERN application using MongoDB, Express, React, and Node.js. 

## Details 

### Frontend: React Application
The frontend of this application is built using React to provide a user-friendly interface. 

**Students** can:

- Browse and search for math questions by topic or difficulty.
- Solve questions and see their progress over time.
- View hints or solutions provided by teachers (if available).

**Teachers** can:

- Add new math questions to the platform.
- Edit or delete existing questions.
- Categorize questions based on topic or difficulty level.

The React app communicates with the backend **REST API** using **Axios** to fetch and manage data.

### Backend: Express REST API
The backend of the application is developed using Node.js and Express. It serves as the API for handling student and teacher data and managing the question bank. 

The backend provides **RESTful endpoints** that allow for the following:

- CRUD operations on math questions (Create, Read, Update, Delete).
- User authentication and authorization 
    - teachers can add/edit questions
    - students can view/solve them.
- Data storage using MongoDB.
- Security features, including JWT-based authentication for teachers and students