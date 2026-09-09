# LevelUp – Personal Gym Training Assistant

LevelUp is a personal gym training assistant that helps users track and manage their workouts. Users can perform CRUD operations to add, view, update, and delete workout records, making it easy to monitor progress and stay motivated.

## Features

- Add, view, update, and delete workouts
- Track workout details: title, reps, load, and timestamps
- Modern React frontend and Express/MongoDB backend

## Tech Stack

- Frontend: React, Vite, React Router
- Backend: Node.js, Express, MongoDB (Mongoose)

## Setup Instructions

### Prerequisites

- Node.js (v18+ recommended)
- npm
- MongoDB instance (local or cloud, e.g., MongoDB Atlas)

### 1. Clone the Repository

```bash
git clone <your-repo-url>
cd LevelUp.worktrees/agents-detailed-readme-setup-instructions
```

### 2. Backend Setup

```bash
cd backend
npm install
```

- Create a `.env` file in the backend directory with:
  ```
  MONGO_URI=<your-mongodb-uri>
  PORT=4000
  ```

- Start the backend server:
  ```bash
  npm run dev
  ```

### 3. Frontend Setup

```bash
cd ../frontend
npm install
npm run dev
```

- The frontend will typically run on `http://localhost:5173` (default Vite port).

## Usage

- Access the frontend in your browser.
- Add, view, update, and delete workouts.
- All data is stored in MongoDB via the backend API.

## Folder Structure

- `backend/` – Express API, MongoDB models, routes, controllers
- `frontend/` – React app (Vite), UI components

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

Let me know if you want to add more details or sections!
