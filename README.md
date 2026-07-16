# 📦 Version Control System

> A powerful full-stack web application for version control and repository management, built with modern web technologies.

<p align="center">
  <a href="https://github.com/vraj2409/Version-Control-System/stargazers">
    <img src="https://img.shields.io/github/stars/vraj2409/Version-Control-System?style=for-the-badge&color=FFD700&logo=github" alt="GitHub Stars">
  </a>
  <a href="https://nodejs.org/">
    <img src="https://img.shields.io/badge/Node.js-v14%2B-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  </a>
  <a href="https://reactjs.org/">
    <img src="https://img.shields.io/badge/React-18%2B-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
  </a>
  <a href="https://expressjs.com/">
    <img src="https://img.shields.io/badge/Express.js-Latest-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express">
  </a>
</p>

<hr>
<hr>

## ✨ Features

| 🎯 Feature | 📝 Description |
|---|---|
| 🔐 **Authentication** | Secure JWT-based user registration & login |
| 📚 **Repositories** | Create, initialize, and manage repositories |
| 💾 **Commits** | Track changes with detailed commit messages |
| 🐛 **Issues** | Create and manage project issues efficiently |
| ⬆️⬇️ **Push/Pull** | Push and pull changes from repositories |
| 👤 **Profiles** | Manage user profiles and account settings |
| 🔍 **Search** | Search and discover repositories instantly |

## 🛠️ Tech Stack

<table>
  <tr>
    <td width="50%">
      <h3>🖥️ Backend Stack</h3>
      <ul>
        <li>⚡ <strong>Node.js</strong> - JavaScript runtime</li>
        <li>🚀 <strong>Express.js</strong> - Web framework</li>
        <li>🔑 <strong>JWT</strong> - Authentication</li>
        <li>☁️ <strong>AWS</strong> - Cloud services</li>
        <li>📊 <strong>Database</strong> - MongoDB/SQL</li>
      </ul>
    </td>
    <td width="50%">
      <h3>🎨 Frontend Stack</h3>
      <ul>
        <li>⚛️ <strong>React 18+</strong> - UI library</li>
        <li>⚙️ <strong>Vite</strong> - Fast build tool</li>
        <li>🎭 <strong>CSS</strong> - Modern styling</li>
        <li>🌐 <strong>Context API</strong> - State management</li>
        <li>📡 <strong>Axios</strong> - HTTP client</li>
      </ul>
    </td>
  </tr>
</table>

## 📁 Project Structure

```
📦 Version-Control-System/
├── 🔧 backend/
│   ├── 🎮 controllers/          # Request handlers
│   │   ├── 👤 userController.js
│   │   ├── 📚 repoController.js
│   │   ├── 💾 commitController.js
│   │   └── 🐛 issueController.js
│   ├── 🗄️ models/              # Database models
│   ├── 🛣️ routes/              # API routes
│   ├── 🔐 middleware/          # Auth & authorization
│   ├── ⚙️ config/              # Configuration
│   ├── 🚀 server.js            # Entry point
│   └── 📦 package.json
│
└── 🎨 frontend/
    ├── 📄 src/
    │   ├── 🧩 components/      # React components
    │   ├── 📄 pages/          # Page components
    │   ├── 🌐 context/        # Context providers
    │   ├── 📊 services/       # API services
    │   ├── 🎯 App.jsx         # Root component
    │   └── 🔗 main.jsx        # Entry point
    ├── ⚙️ vite.config.js
    └── 📦 package.json
```

## 🚀 Quick Start

### 📋 Prerequisites
```
✅ Node.js (v14 or higher)
✅ npm or yarn
✅ AWS credentials configured
```

### 💻 Backend Installation

```bash
cd backend
npm install
```

**⚙️ Configure AWS** in `config/aws-config.js` with your credentials.

### 🎨 Frontend Installation

```bash
cd frontend
npm install
```

<hr>

## 🏃 Running the Project

### 🔧 Start Backend Server

```bash
cd backend
npm start
```
or
```bash
node server.js
```

> **🖥️ Backend** → `http://localhost:3000`

---

### 🎨 Start Frontend Application

```bash
cd frontend
npm run dev
```

> **🌐 Frontend** → `http://localhost:5173`

<hr>

## � API Routes

### 👤 User Routes
- 🔴 `POST /api/users/register` - Register new user
- 🟢 `POST /api/users/login` - Login user
- 🟡 `GET /api/users/profile` - Get user profile

### 📚 Repository Routes
- 🔴 `POST /api/repos/init` - Initialize repository
- 🟡 `GET /api/repos` - Get all repositories
- 🟡 `GET /api/repos/:id` - Get repository details

### 💾 Commit Routes
- 🔴 `POST /api/commits` - Create commit
- 🟡 `GET /api/commits` - Get commits

### 🐛 Issue Routes
- 🔴 `POST /api/issues` - Create issue
- 🟡 `GET /api/issues` - Get issues

**Legend:** 🔴 POST | 🟡 GET | 🟢 Login

## 🔐 Security & Authentication

🔒 The application uses **JWT tokens** for secure authentication.

Configure the auth middleware in `backend/middleware/auth.js` with your secret key.

## 📦 Dependencies

- **Backend**: See [backend/package.json](backend/package.json)
- **Frontend**: See [frontend/package.json](frontend/package.json)

## 🤝 Contributing

We welcome contributions! Here's how:

1. 🍴 Fork the repository
2. 🌿 Create a feature branch (`git checkout -b feature/amazing-feature`)
3. 💾 Commit changes (`git commit -m 'Add amazing feature'`)
4. 📤 Push to branch (`git push origin feature/amazing-feature`)
5. 📥 Open a Pull Request

