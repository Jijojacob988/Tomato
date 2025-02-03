# Food Ordering App - Frontend

## Overview
This is the **frontend** of a full-stack MERN food ordering web application. Built with **React.js**, it provides a user-friendly interface for browsing food items, managing a cart, and placing orders.

> 🚀 The complete **full-stack** project (frontend + backend) is available [here](https://github.com/Jijojacob988/Tomatoo).

## Tech Stack
- **Frontend:** React.js, React Router, Context API
- **Styling:** Custom CSS
- **State Management:** Context API
- **Routing:** React Router DOM

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/Jijojacob988/mern-food-ordering-frontend.git
cd mern-food-ordering-frontend
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Run the Application
```sh
npm start
```
The frontend will be available at **http://localhost:3000/**.

## Folder Structure
```
/src
  ├── components/       # Reusable UI components (Navbar, Footer, etc.)
  ├── pages/            # Main pages (Home, Cart, Checkout)
  ├── context/          # Context API for global state management
  ├── assets/           # Images & icons
  ├── App.js            # Main App component
  ├── index.js          # Entry point
```

## Connecting to the Backend
Since the backend is part of the **full-stack repository**, update the API base URL in a `.env` file:
```
REACT_APP_API_BASE_URL=http://localhost:5000
```
Modify this when deploying to production.

## Full-Stack Repository
This frontend is part of a **full-stack project** that includes the backend API.  
🔗 **Full-Stack Repository:** [https://github.com/Jijojacob988/Tomatoo](https://github.com/Jijojacob988/Tomatoo)

## Deployment
- **Recommended:** Vercel / Netlify  
- **Build for Production:**
  ```sh
  npm run build
  ```
  Upload the `build/` folder to your hosting service.

## License
This project is licensed under the MIT License.

---

Happy coding!

