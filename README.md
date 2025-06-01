# Chat Application

A real-time chat application with user authentication built using Ruby on Rails API backend and React frontend.

## Project Structure

- `backend/` - Ruby on Rails API
- `frontend/` - React application

## Prerequisites

- Ruby 3.2.0+
- Node.js 18+
- PostgreSQL

## Setup Instructions

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Setup database:
   ```bash
   rails db:create db:migrate
   ```

4. Start the Rails server:
   ```bash
   rails server -p 3001
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

The frontend will be available at http://localhost:3000 and the backend API at http://localhost:3001.