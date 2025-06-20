# 🚀 Task Manager Frontend

A sleek, scalable Task Management application built with **Next.js 14** (App Router) and **React.js**, designed to connect seamlessly with a **Node.js**/**Express**/**PostgreSQL** backend.

## ⚙️ Tech Stack

Frontend	Tooling
  **Next.js** (App Router)	Routing & SSR/SSG
  **React.js**	Component Architecture
  **Custom CSS**	Styling
  **Fetch	API** Integration
  **.env**	Environment Variables

---

## 🔍 Project Structure

  src/
    ├── app/
    │   ├── add/             → Add Task Page
    │   ├── edit/[id]/       → Edit Task Page
    │   ├── Home/            → Home Dashboard
    │   └── components/      → TaskCard & TaskForm
    ├── public/              → Static Files
    └── styles/              → Global Styles

### 🚀 Setup Instructions

1. **Clone the Repository**

  ```bash
  git clone https://github.com/your-username/task-manager-frontend.git

2. **Install Dependencies**

  ```bash
  npm install

3. **Configure Environment**
   
    Create a .env file in the root with the following:
    API_BASE_URL=https://task-manager-backend-e6vm.onrender.com/tasks

4. **Start Development Server**

  ```bash
  npm run dev
  
  Access at http://localhost:3000

  
## 🧩 Pages Overview

  | Route        | Description              |
  | ------------ | ------------------------ |
  | `/`          | Dashboard with task list |
  | `/add`       | Form to add a new task   |
  | `/edit/[id]` | Edit existing task       |


## 📦 Build for Production

  npm run build
  npm start