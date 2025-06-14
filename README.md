# Zerodha Clone Frontend

## Project Overview

This project is a frontend clone of Zerodha, built with React and bootstrapped using [Create React App](https://github.com/facebook/create-react-app).

---

## Prerequisites

- [Node.js](https://nodejs.org/) (v14 or above recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- Backend and dashboard projects should also be set up for full functionality.

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/zerodha-clone-full-stack-project.git
cd zerodha-clone-full-stack-project
```

---

### 2. Setup Frontend

```bash
cd frontend
npm install
npm start
```

- The app will run in development mode.
- Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
- The page will reload when you make changes.

---

### 3. Setup Backend

```bash
cd ../backend
npm install
npm start
```

- The backend server will start (default port: 3002).
- Ensure you have a `.env` file with the correct `MONGO_URL` and other environment variables.

---

### 4. Setup Dashboard

```bash
cd ../dashboard
npm install
npm start
```

- The dashboard app will run in development mode (default port: 3001).
- Open [http://localhost:3001](http://localhost:3001) to view it in your browser.

---

### 5. Build for Production (Frontend & Dashboard)

```bash
# For frontend
cd frontend
npm run build

# For dashboard
cd ../dashboard
npm run build
```

---

### 6. Running Tests

```bash
# For frontend
cd frontend
npm test

# For dashboard
cd ../dashboard
npm test
```

---

## Project Structure

- `frontend/` - Main source code for the React frontend.
- `backend/` - Node.js/Express backend server.
- `dashboard/` - React-based dashboard application.
- `public/` - Static files and the main HTML template (inside frontend and dashboard).
- `package.json` - Project configuration and dependencies (per folder).

---

## Additional Notes

- Ensure the backend server is running for API requests to work.
- If you encounter issues with styles, verify that `index.css` is present in `src/` and properly imported in `src/index.js`.
- For any issues, check the browser console and terminal for errors.
- Make sure MongoDB is running and accessible for the backend.

---

## Learn More

- [Create React App Documentation](https://facebook.github.io/create-react-app/docs/getting-started)
- [React Documentation](https://reactjs.org/)
- [Express Documentation](https://expressjs.com/)
- [MongoDB Documentation](https://docs.mongodb.com/)

---
