# 1 Setup & Installation

Clone the repository.
```bash
git clone https://github.com/your-username/task-manager-app.git
cd task-manager-app

```
# 2 Backend Setup (Node.js + Express)
```bash
cd backend
npm install
```
# 3 Create a .env file

example .env
## Edit .env with your MongoDB URL and PORT

# 4 Frontend Setup (Next.js)

```bash
   cd ../frontend
   npm install
   npm run dev
```

## Starts the frontend on: http://localhost:3000

## Ensure the backend is running before accessing the frontend.

# API DOCUMENTATION

# Base URL

http://localhost:3000/api/tasks

Endpoints
GET /tasks
Get all tasks

GET /tasks/:id
Get task by ID

POST /tasks
Create a new task

```bash
{
  "title": "Task Title",
  "description": "Details...",
  "dueDate": "2025-05-01",
  "priority": "High"
}
```
PUT /tasks/:id
Update a task by ID (same body as POST)

DELETE /tasks/:id
Delete a task

# Tech Stack
Frontend: React + Next.js (App Router)

Backend: Node.js + Express

Database: MongoDB with Mongoose




