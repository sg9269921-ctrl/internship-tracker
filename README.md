# 🎯 Internship Tracker

A modern, full-featured Internship Tracker web application built with React and Vite that helps students manage, track, and analyze their internship applications in one centralized platform. This project showcases clean UI design, authentication flow, state management, and scalable component architecture — perfect for your portfolio.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18+-61DAFB?logo=react)
![Vite](https://img.shields.io/badge/Vite-5+-646CFF?logo=vite)

---

## 🚀 Live Demo

🔗 [Coming Soon - Deploy on Vercel/Netlify](#)

---

## ✨ Features

### 🔐 Authentication
- **Login & Signup** pages with form validation
- **Protected Routes** using custom `ProtectedRoute` component
- Authentication state managed via **Context API**
- Persistent sessions using Local Storage

### 📊 Dashboard
- Personalized welcome message with user's name
- **Summary cards** displaying internship statistics by status
- Quick overview of application progress
- Seamless logout functionality

### 📝 Internship Management
- **Add new internship** entries with detailed information:
  - Company name
  - Role/Position
  - Application status
  - Date applied
- **Delete internship** entries with confirmation
- Clean, intuitive form interface

### 🔍 Filtering & Search
- **Filter by status:**
  - All Applications
  - Applied
  - Interview Scheduled
  - Offer Received
  - Rejected
- **Search functionality** by company name or role
- Real-time filtering for instant results

### 🎨 Modern UI/UX
- Stunning gradient backgrounds
- **Glassmorphism** card design
- Fully responsive layout (mobile, tablet, desktop)
- Consistent styling with modern CSS
- Smooth animations and transitions

---

## 🛠️ Tech Stack

### Frontend
| Technology | Purpose |
|-----------|---------|
| **React** | Component-based UI library |
| **Vite** | Fast build tool and dev server |
| **JavaScript (ES6+)** | Modern JavaScript features |
| **CSS3** | Glassmorphism & responsive design |
| **React Router DOM** | Client-side routing |

### State Management & Storage
| Technology | Purpose |
|-----------|---------|
| **React Context API** | Global state management |
| **Local Storage** | Temporary data persistence |

---

## 📁 Project Structure

```
internship-tracker/
│
├── src/
│   ├── auth/
│   │   ├── Login.jsx              # Login page component
│   │   ├── Signup.jsx             # Signup page component
│   │   └── ProtectedRoute.jsx     # Route protection wrapper
│   │
│   ├── components/
│   │   ├── DashboardCards.jsx     # Summary statistics cards
│   │   ├── FilterBar.jsx          # Filter and search bar
│   │   ├── InternshipForm.jsx     # Form to add internships
│   │   ├── InternshipItem.jsx     # Individual internship card
│   │   └── InternshipList.jsx     # List of all internships
│   │
│   ├── context/
│   │   └── AuthContext.jsx        # Authentication context provider
│   │
│   ├── pages/
│   │   └── Dashboard.jsx          # Main dashboard page
│   │
│   ├── utils/
│   │   └── storage.js             # Local storage helper functions
│   │
│   ├── App.jsx                    # Main app component with routing
│   ├── main.jsx                   # Application entry point
│   └── index.css                  # Global styles
│
├── public/                        # Static assets
├── index.html                     # HTML template
├── package.json                   # Dependencies and scripts
├── vite.config.js                 # Vite configuration
└── README.md                      # Project documentation
```

---

## 📦 Installation & Setup

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/internship-tracker.git
cd internship-tracker
```

### 2️⃣ Install Dependencies

```bash
npm install
# or
yarn install
```

### 3️⃣ Run the Development Server

```bash
npm run dev
# or
yarn dev
```

### 4️⃣ Open in Browser

Navigate to:
```
http://localhost:5173
```

### 5️⃣ Build for Production

```bash
npm run build
# or
yarn build
```

---

## 🎓 Learning Outcomes

Through building this project, you'll gain hands-on experience with:

- ✅ Building a **real-world React application** from scratch
- ✅ Understanding **component-based architecture** and reusability
- ✅ Implementing **authentication** and **route protection**
- ✅ Managing **global state** using Context API
- ✅ Designing **reusable and scalable components**
- ✅ Structuring a **production-ready React project**
- ✅ Creating **modern UI/UX** with CSS3 and glassmorphism
- ✅ Handling **form submissions** and **data validation**

---

## 🚧 Roadmap & Planned Enhancements

### Phase 1: Backend Integration
- [ ] Node.js + Express API
- [ ] RESTful endpoints for CRUD operations
- [ ] User authentication with JWT tokens
- [ ] Password hashing with bcrypt

### Phase 2: Database
- [ ] MongoDB integration
- [ ] User and internship data models
- [ ] Cloud database hosting (MongoDB Atlas)

### Phase 3: Advanced Features
- [ ] **Edit internship** functionality
- [ ] **Application analytics** with charts (Chart.js/Recharts)
- [ ] **Deadline reminders** and notifications
- [ ] **Export data** to CSV/PDF
- [ ] **Email notifications** for important updates

### Phase 4: UI/UX Enhancements
- [ ] **Dark mode** toggle
- [ ] Advanced filtering (date range, salary, location)
- [ ] Drag-and-drop status updates
- [ ] Mobile app version (React Native)

### Phase 5: Deployment
- [ ] Deploy frontend on **Vercel** or **Netlify**
- [ ] Deploy backend on **Railway** or **Render**
- [ ] Configure custom domain
- [ ] Set up CI/CD pipeline

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/internship-tracker/issues).

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 👤 Author

**Saurabh Gaikwad**

- 🎓 CSE Final Year Student
- 💻 MERN Stack Developer
- 🐱 GitHub: [@saurabh7](https://github.com/saurabh&)
- 📧 Email: your.email@example.com

---

## 🙏 Acknowledgments

- React Documentation
- Vite Documentation
- Inspiration from modern web applications
- Open-source community

---

## 📸 Screenshots

> Add screenshots of your application here

### Login Page
![Login Page...](#)

### Dashboard
![Dashboard...](#)

### Add Internship
![Add Internship Form...](#)

---

<div align="center">
  <p>Made with ❤️ by Saurabh Gaikwad</p>
  <p>⭐ Star this repo if you find it helpful!</p>
</div>
