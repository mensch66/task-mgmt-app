# Task Manager Application

A full-stack task management application built with React, Node.js, and MongoDB. This application allows users to create, manage, and track their tasks efficiently with a modern and responsive user interface.

## Features

- **Task Management**
  - Create, read, update, and delete tasks
  - Mark tasks as complete/incomplete
  - Set task priorities
  - Add due dates
  - Task categorization

- **User Interface**
  - Modern and responsive design
  - Dark/Light mode support
  - Intuitive task organization
  - Real-time updates
  - Smooth animations

- **Technical Features**
  - RESTful API architecture
  - MongoDB database integration
  - JWT authentication
  - State management with Redux
  - Responsive design with Tailwind CSS

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd task-manager
   ```

2. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Set up environment variables**
   - Create `.env` file in the backend directory
   - Add the following variables:
     ```
     PORT=5000
     MONGODB_URI=your_mongodb_uri
     JWT_SECRET=your_jwt_secret
     ```

### Running the Application

1. **Start the backend server**
   ```bash
   cd backend
   npm run dev
   ```

2. **Start the frontend development server**
   ```bash
   cd frontend
   npm start
   ```

The application will be available at `http://localhost:3000`

## Tech Stack

### Frontend
- React.js
- Redux Toolkit
- Tailwind CSS
- React Router
- Axios
- React Icons

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Bcrypt

## Project Structure
task-manager/
├── frontend/ # React frontend application
│ ├── public/ # Static files
│ └── src/ # Source files
│ ├── components/ # React components
│ ├── pages/ # Page components
│ ├── redux/ # Redux store and slices
│ ├── services/ # API services
│ └── utils/ # Utility functions
│
└── backend/ # Node.js backend application
├── config/ # Configuration files
├── controllers/ # Route controllers
├── middleware/ # Custom middleware
├── models/ # Database models
└── routes/ # API routes


## API Endpoints

### Tasks
- `GET /api/tasks` - Get all tasks
- `POST /api/tasks` - Create a new task
- `GET /api/tasks/:id` - Get a specific task
- `PUT /api/tasks/:id` - Update a task
- `DELETE /api/tasks/:id` - Delete a task

## Authors

- Allen 
