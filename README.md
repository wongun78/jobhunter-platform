# 🎯 Job Hunter Platform

A modern, full-featured job hunting platform built with React, TypeScript, and Vite. This application connects job seekers with employers, providing a seamless experience for job searching, application management, and recruitment.

## ✨ Features

### For Job Seekers
- 🔍 Advanced job search with filters (location, salary, skills, etc.)
- 📝 Easy job application submission
- 👤 Personal account management
- 📊 Application tracking and status monitoring
- 💼 Company profile viewing

### For Employers/Admins
- 📋 Job posting management
- 👥 User management system
- 🏢 Company profile management
- 📄 Resume/CV review
- 🔐 Role-based access control (RBAC)
- 🛠️ Skills and permissions management

## 🛠️ Tech Stack

- **Frontend Framework:** React 18.2.0
- **Language:** TypeScript 5.3.3
- **Build Tool:** Vite 4.5.14
- **UI Library:** Ant Design 5.13.1 + Ant Design Pro Components
- **State Management:** Redux Toolkit 1.9.3
- **Routing:** React Router DOM 6.11.2
- **HTTP Client:** Axios 1.13.2
- **Styling:** SASS/SCSS
- **Rich Text Editor:** React Quill 2.0.0
- **Date Handling:** Day.js 1.11.8

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js:** v16.20.0 or higher ([Download here](https://nodejs.org/download/release/v16.20.0/))
- **npm:** 7.x or higher (comes with Node.js)
- **Git:** For version control

## 🚀 Getting Started

### Development Mode

1. **Clone the repository**
   ```bash
   git clone https://github.com/wongun78/jobhunter-platform.git
   cd jobhunter-platform
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure environment variables**
   - Copy `.env.development` and update the values as needed
   - Set your backend API URL and other configuration

4. **Start the development server**
   ```bash
   npm run dev
   ```
   The application will be available at `http://localhost:5173`

### Production Mode

1. **Clone and install** (steps 1-2 from above)

2. **Configure production environment**
   - Update `.env.production` with production API URLs and settings

3. **Build the project**
   ```bash
   npm run build
   ```

4. **Preview the production build**
   ```bash
   npm run preview
   ```

5. **Deploy**
   - The `dist` folder contains the production-ready files
   - Deploy to your preferred hosting service (Vercel, Netlify, AWS, etc.)

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── admin/          # Admin-specific components
│   ├── client/         # Client-facing components
│   └── share/          # Shared components
├── config/             # Configuration files
│   ├── api.ts         # API endpoints
│   ├── axios-customize.ts
│   └── permissions.ts  # Permission definitions
├── pages/              # Page components
│   ├── admin/         # Admin pages
│   ├── auth/          # Authentication pages
│   ├── company/       # Company pages
│   ├── job/           # Job pages
│   └── home/          # Home page
├── redux/              # Redux state management
│   ├── slice/         # Redux slices
│   └── store.ts       # Redux store configuration
├── styles/             # Global styles and SCSS modules
└── types/              # TypeScript type definitions
```

## 🔧 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run start` | Alias for `npm run dev` |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint (if configured) |

## 🔑 Key Dependencies

- **@ant-design/pro-components** - Advanced UI components for enterprise applications
- **@reduxjs/toolkit** - State management with Redux
- **react-router-dom** - Client-side routing
- **axios** - HTTP client for API requests
- **react-quill** - Rich text editor for job descriptions
- **dayjs** - Lightweight date manipulation

## 🌐 Environment Variables

Create `.env.development` and `.env.production` files with the following variables:

```env
VITE_BACKEND_URL=your_backend_api_url
# Add other environment variables as needed
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is private and proprietary.

## 👨‍💻 Author

**Kien Nguyen**
- GitHub: [@wongun78](https://github.com/wongun78)

## 📞 Support

For support, please open an issue in the GitHub repository.

---

⭐ If you find this project useful, please consider giving it a star on GitHub!