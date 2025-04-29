# 💬 WRAP-CHAT

A modern full-stack chat application built using the **MERN stack**, supporting **real-time messaging**, **authentication**, and **online presence**, styled with **Tailwind CSS** and **DaisyUI**.

---

## 🚀 Features

- 🔐 Secure authentication with **JWT**
- 💬 Real-time messaging via **Socket.io**
- 📡 Online/offline user status detection
- 🗂 Global state management using **Zustand**
- 🎨 Responsive UI with **Tailwind CSS** + **DaisyUI**
- ⚙️ RESTful API with **Express**
- 🛡 Robust error handling on client and server
- 🌍 Easily deployable on platforms like **Render**, **Vercel**, or **Netlify**

---

## 🛠 Tech Stack

**Frontend**  
- React  
- Zustand  
- Socket.io-client  
- Tailwind CSS + DaisyUI  

**Backend**  
- Node.js  
- Express.js  
- MongoDB + Mongoose  
- JWT Authentication  
- Socket.io  

---

## 📁 Project Structure

mern-chat-app/ │ ├── backend/ # Express server, MongoDB, Socket.io │ ├── controllers/ │ ├── models/ │ ├── routes/ │ └── server.js │ ├── frontend/ # React app │ ├── src/ │ │ ├── components/ │ │ ├── context/ │ │ ├── pages/ │ │ └── App.js │ ├── .gitignore ├── README.md └── package.json

## 🔧 Getting Started


## 1. Clone the repository

```bash
git clone https://github.com/viivekthakur/mern-chat-app.git
cd mern-chat-app


2. Backend Setup
cd backend
npm install

Create a .env file in the backend folder and add the following:
PORT=5000
MONGO_DB_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret
NODE_ENV=development

Start the backend:
npm start


3. Frontend Setup
cd ../frontend
npm install
npm start

⚙️ Build for Production
npm run build

🧪 Example .env File
PORT=5000
MONGO_DB_URI=mongodb+srv://username:password@cluster.mongodb.net/chat-app
JWT_SECRET=my_super_secret_key
NODE_ENV=production

🛡 License
This project is licensed under the MIT License.


Made with ❤️ by Viivek Thakur

---

Let me know if you want to personalize this more (e.g., your profile picture, project link, deployment instructions, or a custom domain).
