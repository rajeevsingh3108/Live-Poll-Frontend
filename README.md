# Live Poll - Frontend

## Overview
This project is a real-time polling system that allows teachers to create live polls and students to participate in them. The frontend is built with **React** (using Vite as the build tool). **Socket.IO** is used for real-time communication between the server and clients.

## 🚀 Features

### 👨‍🏫 Teacher Interface
- Create and manage live polls
- View responses in real-time
- Access poll history
- Moderate live chat with participants

### 👩‍🎓 Student Interface
- Join polls using unique codes
- Submit answers in real-time
- Participate in live discussions
- View results dynamically

### 💬 Common Features
- Live chat system for engagement
- Protected routes for teachers and students
- Responsive and clean UI
- Fast build with Vite

## 🧱 Project Structure

```
src/
├── Pages/
│   ├── loginPage/
│   ├── poll-history/
│   ├── student-landing/
│   ├── student-poll/
│   ├── teacher-landing/
│   └── teacher-poll/
├── components/
│   ├── chat/
│   └── route-protect/
├── assets/
├── App.jsx
├── main.jsx
└── index.css
```

## ⚙️ Tech Stack

| Category | Technology |
|----------|------------|
| Frontend Framework | React (Vite) |
| Styling | CSS |
| Routing & Protection | React Router |
| State Management | React Hooks |
| Build Tool | Vite |
| Package Manager | npm or yarn |

## 🧩 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/rajeevsingh3108/Live-Poll-Frontend.git
cd live-poll-frontend
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Start the development server
```bash
npm run dev
```

### 4️⃣ Build for production
```bash
npm run build
```

## 🧠 Usage

- Teachers can log in and start a new poll from the dashboard
- Students can join polls using the generated poll code
- Both users can chat and view poll results live

## 🔒 Environment Variables

Create a `.env` file in the project root:
```ini
VITE_API_URL=<your_backend_api_url>
```

## 🧑‍💻 Development Notes

- Built with modular React components for reusability
- Follows a page-based structure for routing
- Ideal for classroom or technical interview use-cases

## 🌐 Deployment

To deploy on Netlify or Vercel:
1. Push to GitHub
2. Connect your repository
3. Set build command: `npm run build`
4. Set publish directory: `dist/`

## 📄 License

This project is licensed under the MIT License.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.