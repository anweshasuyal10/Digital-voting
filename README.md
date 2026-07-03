# 🗳️ SecureVote - Full Stack Online Voting System

SecureVote is a full-stack web application designed to provide a **secure, encrypted, and user-friendly online voting experience**. It allows both **users** and **admins** to register and perform role-specific actions like voting, managing elections, and viewing results. The system uses **JWT authentication**, **MongoDB**, **Node.js**, and **React** with a **3D dynamic UI** for a modern user experience.

---

## 🚀 Features

- 🔐 **User/Admin Registration & Login**
- 🧾 **JWT Authentication & Authorization**
- 📱 **Mobile-Friendly UI with 3D Animations**
- 🧑‍⚖️ **Admin Dashboard to Create & Manage Elections**
- 🗳️ **User Dashboard to Vote in Active Elections**
- 📊 **Real-time Results Visualization**
- 🧬 **Encrypted Voting Mechanism**
- 🌐 **Fully Responsive Design**
- 🎨 **Attractive UI with Landing, About, and Contact Sections**

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- Framer Motion (for animations)

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- JSON Web Tokens (JWT)
- Bcrypt for password encryption

---

## 🧪 Getting Started

### 🖥️ Prerequisites

- Node.js (v18 or higher)
- MongoDB (local or Atlas)

### 📦 Installation

```bash
git clone https://github.com/your-username/secure-vote.git
cd secure-vote
Backend Setup
bash
Copy
Edit
cd server
npm install
npm run dev
Frontend Setup
bash
Copy
Edit
cd client
npm install
npm start
🧾 .env Configuration
Create a .env file inside /server:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
ENCRYPTION_KEY=your-32-character-secret-key
PORT=5000
📸 UI Preview
🏠 Landing Page with background image and animations

👤 Separate Dashboards for Admin and Users

🧩 3D Dynamic Components for Voting & Result Display

📚 Folder Structure
pgsql
Copy
Edit
project/
│
├── server/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── middleware/
│
├── client/
│   ├── public/
│   └── src/
│       ├── pages/
│       ├── components/
│       └── assets/
📌 Future Features
Blockchain-based vote ledger

Face recognition voter authentication

Multi-language support

🤝 Contributing
Fork the repo

Create your feature branch (git checkout -b feature/add-feature)

Commit your changes (git commit -m 'Add some feature')

Push to the branch (git push origin feature/add-feature)

Open a Pull Request

📄 License
This project is licensed under the MIT License.



