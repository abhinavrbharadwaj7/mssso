# My POC Project

This repository contains the **frontend** and **backend** code for a Proof of Concept (POC) project. The application is designed with a modern architecture, featuring a **React + TypeScript** frontend and a **Fastify + MongoDB** backend.

---

## 🗂️ Folder Structure

- **`my-poc-frontend/`**: Contains the source code for the frontend application.
- **`my-poc-backend/`**: Contains the source code for the backend application.

> Note: Both folders have had their `node_modules` directories removed to reduce repository size. You need to run `npm install` to install the required dependencies before running the project.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed on your system:

1. **Node.js** (v16 or higher)
2. **npm** (comes with Node.js) or **yarn**
3. **MongoDB** (for database operations)

---

### ⚙️ Frontend Setup

1. **Navigate to the Frontend Directory**:
   ```bash
   cd my-poc-frontend
Install Dependencies:

npm install
Start the Development Server:

npm start
Access the Frontend: Open your browser and go to:

http://localhost:3000
📁 Key Frontend Files:
src/: Main source code for the React application.
public/: Static assets like HTML and images.
🛠️ Backend Setup
Navigate to the Backend Directory:


cd my-poc-backend
Install Dependencies:

e
npm install
Setup Environment Variables: Create a .env file in the my-poc-backend directory with the following content:

bash
Copy code
PORT=4000
MONGO_URI=mongodb://localhost:27017/my-poc-db
Start the Development Server:

bash
Copy code
npm run dev
Access the Backend API: The backend server will run at:


http://localhost:4000
📁 Key Backend Files:
src/: Contains routes, controllers, and services.
models/: MongoDB models for data schema definitions.
🔧 Project Features
Frontend
User-friendly React interface with responsive design.
Dynamic components for user login and profile management.
Integrated with backend APIs for user authentication.
Backend
RESTful APIs built with Fastify for high performance.
MongoDB integration for data persistence.
Handles user authentication, profile updates, and session management.
📝 Development Notes
No node_modules:

The node_modules directories were deleted from both my-poc-frontend and my-poc-backend to save repository space.
After cloning the repository, run npm install in both folders to install the necessary dependencies.
Environment Configuration:

Ensure MongoDB is running locally or configure a remote database URL in the backend .env file.
🛠️ How to Contribute
Fork this repository.
Clone your forked copy:

git clone https://github.com/<your-username>/mssso.git
Create a new branch for your feature:

git checkout -b feature-name
Commit your changes:

git commit -m "Added feature"
Push to your branch:

git push origin feature-name
Open a Pull Request on the original repository.
📃 License
This project is licensed under the MIT License. See the LICENSE file for more details.

📞 Contact
For questions or support, feel free to reach out:

GitHub: abhinavrbharadwaj7
Email: abhinavrbharadwaj86@gmail.com


---

   git push
