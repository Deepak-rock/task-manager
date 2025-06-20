# 🧠🚀 Task Manager – Full Stack Edition


An end-to-end task management application built for **performance**, **scalability**, and **simplicity**. Built with a **React** + **Next.js frontend** and a **Node.js** + **Express** + **PostgreSQL backend**, this app is ready for real-world use, rapid iteration, and ambitious features.


## 🌐 Live Demo

    🧪 **Demo** - https://taskmanagery.netlify.app



## 🏗️ Tech Stack


### Frontend (Next.js 14)

- **Next.js (App Router)** – Routing, SSR/SSG

- **React.js** – Component architecture

- **Custom CSS**  – Styling

- **Fetch** – API calls

- **.env** – Environment variables

### Backend (Node.js + Express)

- **Node.js** – JavaScript runtime

- **Express.js** – RESTful API framework

- **PostgreSQL** – Relational DB

- **TypeORM** – ORM (can be swapped)

- **dotenv** – Secure config

---

## 📂 Monorepo Structure

    task-manager/
    ├── frontend/              # Next.js frontend
    │   └── src/
    │       ├── app/
    │       │   ├── add/
    │       │   ├── edit/[id]/
    │       │   ├── Home/
    │       │   └── components/
    │       ├── public/
    │       └── styles/
    ├── backend/               # Express backend
    │   └── src/
    │       ├── entity/
    │       │   └── Task.js
    │       ├── data-source.js
    │       ├── routes.js
    │       └── index.js
    └── README.md

---

## 🚀 Setup Instructions

### 🛠 Prerequisites
    Node.js (v18+)

    PostgreSQL (local, Docker, or cloud instance)

    npm

## 🧩 Backend Setup

1. **Install dependencies**

    ```bash
    npm install


2. **Configure environment**

Create a .env file in the root:

    # You can provide any Port
    PORT=5001
    # Provide your Database Url from render || docker || local.  
    DB_URL= postgresql://username:password@port/your_database_name 

Copy from .env.example if available.


3. **Start the server**

    npm run dev     # For development with nodemon
    npm start       # For production


### 🧠 API Endpoints

    | Method | Endpoint     | Description       |
    | ------ | ------------ | ----------------- |
    | GET    | `/tasks`     | Get all tasks     |
    | POST   | `/tasks`     | Create a new task |
    | PUT    | `/tasks/:id` | Update a task     |
    | DELETE | `/tasks/:id` | Delete a task     |

---

## 💻 Frontend Setup

1. **Install dependencies**

    ```bash
    npm install


2. **Configure environment**

    Create .env:

    API_BASE_URL=https://task-manager-backend-e6vm.onrender.com/tasks


3. **Run locally**: 

    npm run dev
    Access: http://localhost:3000


## 🧠 Frontend Routes

    |   Path     |      Description        |
    |   ----     |   -----------------     |
    | /          |   Dashboard (task list) |
    | /add       |   Add new task          |
    | /edit/[id] |   Edit existing task    |


## 🧪 Scripts


### Backend (/backend/package.json)

    "scripts": {
    "start": "node src/index.js",
    "dev": "nodemon src/index.js",
    "test": "echo \"Test suite coming soon\""
    }

### Frontend (/frontend/package.json)

    "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
    }


## ✨ Contribution
We welcome contributions from developers, designers, and dreamers.
Clone → Build → Improve → Pull Request 🚀

    git clone https://github.com/Deepak-rock/task-manager