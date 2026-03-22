# 🎓 NaijaSchool Portal

A full-featured school management web application for Nigerian Primary and Secondary School students.

## Features

- 🔐 **Secure Student Login** — Each student logs in with a unique student ID and password
- 📋 **Attendance Registration** — Students register their presence each term online
- 📝 **Online Examinations** — Students write CBT (Computer-Based Tests) exams with password-protected access
- 📊 **Results Dashboard** — Students can view their exam scores and performance
- 👨‍🏫 **Admin/Teacher Panel** — Admins can manage students, set exam questions, and view attendance records
- 📅 **Term Management** — First, Second, and Third term tracking
- 🏫 **Class Management** — Supports Primary 1–6 and JSS1–SSS3

## Tech Stack

- **Frontend**: React.js (with hooks)
- **Styling**: CSS (custom, no framework)
- **State Management**: React Context API
- **Storage**: localStorage (can be replaced with a backend/database)

## Getting Started

### Prerequisites
- Node.js v16+
- npm or yarn

### Installation

```bash
git clone https://github.com/YOUR_USERNAME/naija-school-app.git
cd naija-school-app
npm install
npm start
```

The app runs on `http://localhost:3000`

## Demo Credentials

### Admin Login
- **Username**: `admin`
- **Password**: `admin123`

### Sample Student Login
- **Student ID**: `PS/2024/001`
- **Password**: `student123`

### Exam Access Password
- Each exam has a unique password set by the admin. Sample: `EXAM2024`

## Project Structure

```
src/
├── components/        # Reusable UI components
├── pages/             # Page components (Login, Dashboard, Exam, etc.)
├── context/           # Global state (AuthContext, AppContext)
├── data/              # Sample data (students, questions, subjects)
└── utils/             # Helper functions
```

## Screenshots

> Add screenshots after running the app locally.

## Contributing

Pull requests are welcome. For major changes, please open an issue first.

## License

MIT
