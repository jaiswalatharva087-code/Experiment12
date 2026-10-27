# Campusly – Student Management System

Campusly is a modern and responsive student management web application built using **React and Vite**. It provides a user-friendly interface for students to explore the platform, register, log in, and contact support.

The project demonstrates component-based architecture, client-side routing, form state management, and responsive UI design.

## 📸 Key Features

- **Home Page:** Welcoming landing page with an overview of the platform.
- **About Page:** Information about the purpose and features of Campusly.
- **Student Registration:** Form for entering student details, including name, email, and password, with client-side state management and validation.
- **User Login:** Login interface with email and password fields.
- **Contact Support:** Displays contact information and support details.
- **SPA Navigation:** Fast client-side navigation using React Router without full-page reloads.
- **Responsive Design:** Adapts to desktop, tablet, and mobile screen sizes.
- **Reusable Components:** Organized React components for easier maintenance and development.

## 🛠️ Tech Stack

- **Frontend Framework:** React
- **Build Tool:** Vite
- **Routing:** React Router DOM
- **Styling:** CSS3, Flexbox, Grid, and media queries
- **Programming Language:** JavaScript (ES6+)
- **Package Manager:** npm

## 📂 Project Structure

```text
Campusly/
├── dist/                  # Production build output
├── public/                # Public static assets (if present)
├── src/
│   ├── components/
│   │   ├── About.jsx      # About page
│   │   ├── Contact.jsx    # Contact and support page
│   │   ├── Home.jsx       # Home page
│   │   ├── Login.jsx      # Login form
│   │   └── Register.jsx   # Registration form
│   ├── App.jsx            # Main application and route definitions
│   ├── main.jsx           # Application entry point
│   └── styles.css         # Global styles and responsive layouts
├── index.html             # HTML entry point
├── package.json           # Dependencies and npm scripts
├── package-lock.json      # Dependency lock file (if present)
└── README.md              # Project documentation
```

*Note: `node_modules/` is generated during dependency installation, and `dist/` is generated during the production build. These folders generally do not need to be committed to GitHub.*

## 🚀 Getting Started

Follow these steps to run Campusly locally.

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- npm (included with Node.js)
- Git

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/padarthidivyasri/Experiment12.git
```

**2. Navigate to the project directory**

```bash
cd Experiment12
```

**3. Install dependencies**

```bash
npm install
```

**4. Start the development server**

```bash
npm run dev
```

**5. Open the application**

Visit the following URL in your browser:

[http://localhost:5173](http://localhost:5173)

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Starts the Vite development server with hot module replacement (HMR). |
| `npm run build` | Builds and optimizes the application for production in the `dist/` folder. |
| `npm run preview` | Runs a local server to preview the production build. |

## 🧭 Routes Overview

| Page | Route | Description |
|---|---|---|
| Home | `/` | Main landing page and platform overview. |
| About | `/about` | Information about Campusly. |
| Contact | `/contact` | Contact information and support details. |
| Register | `/register` | Student registration form. |
| Login | `/login` | Login interface for registered users. |

## ⚠️ Scope and Limitations

- **Frontend-Focused:** The project demonstrates React UI development, client-side routing, and form state management.
- **No Backend Integration:** Registration and login are simulated on the client side and do not connect to a live backend or database.
- **No Real Authentication:** The current implementation does not provide production-grade authentication or persistent user accounts.

A backend service and database, such as Express.js with MongoDB or SQLite, could be integrated in the future to support persistent student records and real authentication.

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature/AmazingFeature
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add some AmazingFeature"
   ```

4. Push your branch:

   ```bash
   git push origin feature/AmazingFeature
   ```

5. Open a Pull Request.

## 📄 License

This project is distributed under the **MIT License**. See the `LICENSE` file for details.
