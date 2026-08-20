# 🏫 School Management System — Frontend

A modern, responsive **School Management System** frontend built with **Next.js and React**. The application provides a structured interface for managing different aspects of a school ecosystem, including authentication, school-specific pages, applications, finance-related modules, and reusable UI components.

This project is designed with a modular architecture to make the application easy to maintain, extend, and scale.

---

## ✨ Features

* 🔐 **Authentication**

  * User authentication and authorization interfaces
  * Dedicated authentication components and routes

* 🏫 **School Management**

  * School-specific dynamic routes
  * Structured school administration interface
  * Modular pages for different school operations

* 📝 **Application Management**

  * Application-related pages and workflows
  * Organized application interface

* 💰 **Finance Management**

  * Finance-related dashboard components
  * Reusable components for financial data and operations
  * Data visualization support

* 📊 **Data Visualization**

  * Interactive charts using Recharts
  * Dashboard-friendly visual representations of data

* 🎨 **Modern UI**

  * Responsive and clean interface
  * Reusable UI components
  * Light/Dark theme support
  * Accessible components powered by Radix UI and shadcn

* 🌐 **Multi-language Support**

  * Language provider architecture for supporting multiple languages

* 🧩 **Reusable Component Architecture**

  * Authentication components
  * Finance components
  * Shell/layout components
  * UI components
  * Theme and language providers

---

## 🛠️ Tech Stack

### Frontend

* **Next.js 16.2.6**
* **React 19.2.4**
* **JavaScript**
* **Tailwind CSS 4**

### UI & Styling

* **shadcn/ui**
* **Radix UI**
* **Lucide React**
* **Tailwind Merge**
* **Class Variance Authority**

### Data Visualization

* **Recharts**

### Utilities

* **date-fns**
* **React Day Picker**
* **next-themes**

### Development Tools

* **ESLint**
* **PostCSS**
* **npm**

The project's `package.json` confirms the core framework, UI libraries, charting library, styling stack, and development scripts listed above.

---

## 📁 Project Structure

```text
frontend/
│
├── app/
│   ├── [schoolSlug]/
│   ├── apply/
│   ├── auth/
│   ├── globals.css
│   ├── layout.js
│   └── page.js
│
├── components/
│   ├── auth/
│   ├── finance/
│   ├── shells/
│   ├── ui/
│   ├── language-provider.jsx
│   ├── theme-provider.jsx
│   └── theme-toggle.jsx
│
├── lib/
│
├── public/
│
├── .gitignore
├── components.json
├── eslint.config.mjs
├── jsconfig.json
├── next.config.mjs
├── package.json
├── postcss.config.mjs
└── README.md
```

The repository currently separates application routes under `app/` and reusable functionality under `components/`, including authentication, finance, shells, and UI components.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/mehul9mayank/School_Management.git
```

### 2. Navigate to the Frontend

```bash
cd School_Management/frontend
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm run dev
```

The project uses Next.js's development server and runs locally on:

```text
http://localhost:3000
```

These commands are also reflected in the project's existing Next.js setup.

---

## 📜 Available Scripts

| Command         | Description                   |
| --------------- | ----------------------------- |
| `npm run dev`   | Starts the development server |
| `npm run build` | Creates a production build    |
| `npm run start` | Starts the production server  |
| `npm run lint`  | Runs ESLint                   |

---

## 🏗️ Architecture

The frontend follows a modular Next.js architecture:

```text
                    ┌─────────────────────┐
                    │     Next.js App     │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              │                │                │
        ┌─────▼─────┐    ┌─────▼─────┐    ┌────▼─────┐
        │    App    │    │ Components │    │   Lib    │
        │   Routes  │    │  & UI      │    │ Utilities│
        └─────┬─────┘    └─────┬─────┘    └────┬─────┘
              │                │                │
              └────────────────┼────────────────┘
                               │
                       ┌───────▼────────┐
                       │ School Mgmt UI │
                       └────────────────┘
```

The application uses Next.js's App Router structure with dynamic school routes, authentication routes, and application pages.

---

## 🎯 Project Goals

The main goals of the frontend are to:

* Provide a centralized interface for school management.
* Create a clean and intuitive user experience.
* Separate functionality into reusable components.
* Support scalable school-specific routes.
* Provide dashboards and visualizations for important information.
* Maintain a responsive interface across devices.
* Keep the codebase modular and maintainable.

---

## 🔮 Future Improvements

Potential improvements include:

* 📱 Enhanced mobile responsiveness
* 🔔 Real-time notifications
* 📈 Advanced analytics dashboards
* 👨‍🏫 Teacher management
* 👨‍🎓 Student performance tracking
* 📚 Attendance and academic management
* 💳 Online fee/payment integration
* 📧 Email and notification integration
* 🔐 Role-based access control
* 🌍 Expanded multilingual support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature/your-feature
```

3. Make your changes.
4. Commit your changes.

```bash
git commit -m "Add: your feature"
```

5. Push the branch.

```bash
git push origin feature/your-feature
```

6. Open a Pull Request.

---

## 📌 Repository

**GitHub:**
https://github.com/mehul9mayank/School_Management

**Frontend Branch:**
https://github.com/mehul9mayank/School_Management/tree/Sangita/frontend

---

## 👨‍💻 Author

**Mehul Mayank**

GitHub: [@mehul9mayank](https://github.com/mehul9mayank)

---

## ⭐ Support

If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub!

---

### Built with ❤️ using Next.js & React
