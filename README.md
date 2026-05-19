# FASCO 🛍️✨

FASCO is a modern, feature-rich E-Commerce platform for clothing, built from the ground up with React. This project serves as a complete storefront experience, allowing users to browse products, manage their cart, and proceed through a simulated checkout process. It demonstrates best practices in modern frontend development, including component-based architecture, state management with the Context API, and client-side routing.

---

## 🌍 Live Demo

Experience the live version of the application here:
👉 [https://e-commrce-iti-project-react.vercel.app/](https://e-commrce-iti-project-react.vercel.app/)

---

## ✨ Features

- 🏠 **Dynamic Homepage** — Engaging layout with featured products and promotional sections
- 🧥 **Shop & Product Pages** — Browse all items and view detailed individual product pages
- 🔐 **User Authentication** — Secure registration, login, and forgot password functionality
- 🛒 **Advanced Shopping Cart** — Add, remove, and update quantities in a persistent cart modal
- ✅ **Smooth Checkout Flow** — Multi-step checkout process simulating a real purchase
- 📱 **Fully Responsive Design** — Seamless experience across desktop, tablet, and mobile
- ⚡ **Modern State Management** — React Context API for global cart and auth state
- 🔄 **Client-Side Routing** — Fast navigation without full-page reloads via React Router

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React.js |
| Routing | React Router |
| State Management | React Context API |
| Styling | CSS / CSS Modules |
| Build Tool | Vite |

---

## 📂 Project Structure

```
/
├── public/                  # Static assets and index.html
├── src/
│   ├── assets/              # Images, icons, and other static assets
│   ├── components/          # Reusable UI components
│   │   ├── ProductPage/     # Components specific to product details view
│   │   ├── footer.jsx
│   │   ├── HomeNavbar.jsx
│   │   ├── Loader.jsx
│   │   ├── Navbar.jsx
│   │   └── ShoppingCartModal.jsx
│   ├── contexts/            # React Context for global state
│   │   ├── AuthContext.js
│   │   └── CartContext.js
│   ├── pages/               # Top-level page components
│   │   ├── auth/
│   │   │   ├── ForgotPasswordPage.jsx
│   │   │   ├── LoginPage.jsx
│   │   │   └── SignupPage.jsx
│   │   ├── Cart.jsx
│   │   ├── Checkout.jsx
│   │   ├── home.jsx
│   │   ├── ProductPage.jsx
│   │   └── shopPage.jsx
│   ├── styles/              # Global and page-specific CSS
│   │   ├── App.css
│   │   ├── auth.css
│   │   ├── Cart.css
│   │   └── ...
│   ├── App.jsx              # Main app component with routing setup
│   └── main.jsx             # Application entry point
├── .gitignore
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Elsebae/E-commrce_ITI-Project_React
   ```

2. **Navigate to the project directory**
   ```bash
   cd FASCO
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

The app will be running at **http://localhost:5173**

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit with a clear message
4. Push your branch and open a Pull Request

You can also open an [Issue](../../issues) to report bugs or suggest new features.
