# 💬 Real-Time Chat Application (MERN + Socket.IO)

![React](https://img.shields.io/badge/Frontend-ReactJS-61DAFB?logo=react\&logoColor=white\&style=flat)
![Node](https://img.shields.io/badge/Backend-Node.js-339933?logo=nodedotjs\&logoColor=white\&style=flat)
![Express](https://img.shields.io/badge/Framework-Express-000000?logo=express\&logoColor=white\&style=flat)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?logo=mongodb\&logoColor=white\&style=flat)
![Socket.IO](https://img.shields.io/badge/RealTime-Socket.IO-010101?logo=socketdotio\&logoColor=white\&style=flat)
![Render](https://img.shields.io/badge/Deployed%20On-Render-46E3B7?logo=render\&logoColor=white\&style=flat)

---

This is a **real-time chat application** built using the **MERN stack (MongoDB, Express, React, Node.js)** along with **Socket.IO**.
It allows users to **sign up, log in, search users, and chat instantly** — all with a modern UI and secure authentication.

I built this project to **strengthen my full-stack development skills**, gain **hands-on experience with real-time systems**, and add a **portfolio-worthy project** that demonstrates backend + frontend + deployment expertise.

🔗 **Live Demo:** [ChatApp on Render](https://chatapp-using-mern-1.onrender.com)

---

## 🖥️ Screenshots

**Login Page**
<img width="1919" height="909" alt="image" src="https://github.com/user-attachments/assets/11278f45-8fcc-4606-af67-a6eb42ae3610" />



**Home / Search**
<img width="1918" height="908" alt="image" src="https://github.com/user-attachments/assets/2ceb064b-736b-4341-b445-165eb9dd58d4" />


**Chat Window & Messages**
<img width="1919" height="898" alt="image" src="https://github.com/user-attachments/assets/cc8956b4-615c-4c1f-8340-2c1b0d24ac7a" />



---

## ✅ Features

* 🔐 **User Authentication** – Sign up & log in securely (Bcrypt + JWT)
* 🖼 **Profile Pictures** – Upload your avatar
* 🔎 **Search Users** – Find other registered users
* ⚡ **Real-Time Messaging** – Powered by Socket.IO
* 💾 **Persistent Messages** – Stored safely in MongoDB
* 📱 **Responsive UI** – Built with React + Tailwind + DaisyUI

---

## 🛠️ Tech Stack

* **Frontend:** ReactJS, TailwindCSS, DaisyUI, Redux
* **Backend:** Node.js, Express.js, Socket.IO
* **Database:** MongoDB Atlas
* **Authentication:** JWT + Bcrypt.js
* **Deployment:** Render

---

## ▶️ How to Run

1. **Clone the Repository**

```bash
git clone https://github.com/krishna06045/ChatApp-using-MERN.git
cd ChatApp-using-MERN
```

2. **Install Dependencies**

   * Backend:

   ```bash
   cd backend
   npm install
   ```

   * Frontend:

   ```bash
   cd frontend
   npm install
   ```

3. **Setup Environment Variables**
   Create a `.env` file inside `backend/` with:

```env
MONGO_URI=your-mongodb-connection
JWT_SECRET=your-secret-key
```

4. **Run the App**

   * Start backend:

   ```bash
   cd backend
   npm start
   ```

   * Start frontend (in a new terminal):

   ```bash
   cd frontend
   npm start
   ```

5. **Open in Browser**
   👉 [http://localhost:3000](http://localhost:3000)

---

## 🌟 Why I Built This

* Real-time communication is the backbone of modern applications (WhatsApp, Slack, MS Teams). I wanted to understand how chat systems work under the hood rather than just using them.
* This project gave me hands-on experience with WebSockets, event-driven architecture, and scaling real-time systems, which are critical in any large-scale application.
* I wanted to simulate a real-world use case: secure messaging with authentication, persistent storage, and responsive design — just like production apps.

