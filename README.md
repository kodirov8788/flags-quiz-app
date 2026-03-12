# 🌍 World Flags Quiz & Management System

A comprehensive, interactive web application built with React and Tailwind CSS, designed for learning and testing knowledge of world flags. This project includes both a user-facing quiz platform and a robust administrative backend for content management.

![Project Banner](https://img.shields.io/badge/Tech-React%20%2B%20Tailwind-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🚀 Overview

This application provides an engaging way for users to master world flags through interactive quizzes. It features a complete administrative console that allows creators to manage categories, test sets, and product mappings dynamically.

### 🌟 Key Features

#### **User Experience**
- **Interactive Quizzes**: Multiple-choice flag identification tests.
- **Adaptive UI**: Responsive design built with Flowbite and Tailwind CSS for mobile and desktop.
- **Auth System**: Secure Login/Signup integration to track user progress.
- **Dynamic Content**: Quizzes populated from a large internal dataset (100+ countries).

#### **Admin Management**
- **Content Dashboard**: Overview of system statistics.
- **Category CRUD**: Create, read, update, and delete flag categories.
- **Test Management**: Add or edit specific test items and mappings via a dedicated interface.
- **Role-based Routing**: Protected administrative routes using React Context API.

---

## 🛠 Tech Stack

- **Frontend Core**: [React 18](https://reactjs.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/), [Flowbite](https://flowbite.com/)
- **State Management**: React Context API & Hooks
- **Routing**: [React Router Dom v6](https://reactrouter.com/)
- **Networking**: [Axios](https://axios-http.com/)
- **UI Components**: [Swiper](https://swiperjs.com/) (Carousels), [React Toastify](https://fkhadra.github.io/react-toastify/) (Notifications)
- **Icons**: [React Icons](https://react-icons.github.io/react-icons/)

---

## 📦 Project Structure

```bash
src/
├── admin/          # Administrative dashboard and CRUD components
├── api/            # API configuration and service layers
├── components/     # Reusable UI elements (Navbar, Buttons, etc.)
├── context/        # Authentication and Global State providers
├── hooks/          # Custom utility hooks (useAuth, etc.)
├── pages/          # Main views (MainPage, Testpage, Login, Signup)
├── Static_data.js  # Core flag dataset and multichoice options
└── Routers.js      # App navigation and route protection
```

---

## ⚙️ Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/kodirov8788/Flags.git
   cd Flags
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

---

## 🤝 Contribution

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git checkout origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

Developed with ❤️ by [Kodirov](https://github.com/kodirov8788)
