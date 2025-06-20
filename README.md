# 🎓 CMS-Frontend - College Management System Frontend

Welcome to the **CMS-Frontend** repository! 🚀 This is the frontend for the College Management System, designed to provide an intuitive and responsive user interface for students, teachers, and admins. Built with modern web technologies, it seamlessly integrates with the backend to manage college operations. 📚💻

## 🌟 Features

- **User Dashboard** 👤: Personalized dashboards for admins, teachers, and students.
- **Onboarding** 🌱: Smooth user onboarding with form enhancements.
- **Course & Quiz Management** 📚🎯: View and manage courses, quizzes, and enrollments.
- **Responsive Design** 📱: Optimized for desktop and mobile devices.
- **Gallery & Contact** 🖼️📧: Showcase college gallery and contact information.
- **Secure Navigation** 🔒: Role-based access with user enrollment tracking.

## 🛠️ Tech Stack

- **Framework**: Next.js 🌐
- **Styling**: Tailwind CSS 🎨, PostCSS
- **TypeScript**: Type safety with `.tsx` and `.ts` files 🔍
- **Configuration**: ESLint, Prettier, and custom middleware ⚙️

## 🚀 Getting Started

### 📋 Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher) 🛠️
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/) 📦
- [Git](https://git-scm.com/) for cloning 📥

### ⚙️ Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Collage-Management-System/CMS-Frontend.git
   cd CMS-Frontend
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   # OR
   yarn install
   ```

3. **Set Up Environment**:
   Create a `.env` file based on `.env.example` and update with your backend API URL:
   ```env
   NEXT_PUBLIC_API_URL=http://localhost:3000/api
   ```

4. **Run the Development Server**:
   ```bash
   npm run dev
   # OR
   yarn dev
   ```
   Open [http://localhost:3000](http://localhost:3000) to see the app.

## 📁 Project Structure

- **app/** 📂: Main application pages and layouts.
  - `(Admin)`, `(auth)`, `(teacher)`, `(user)`, `about`, `actions`, `api`, `contactUs`, `globals.css`, `layout.tsx`, `page.tsx`.
- **components/** 🧩: Reusable UI components.
  - `about`, `collegeGallery`, `contactUs`, `department`, `home`, `onboarding`, `quizzes`, `reUsed`, `styling`, `subject`, `ui`, `userDashboard`, `userEnrollments`.
- **config/** ⚙️: Configuration files.
  - `components.json`, `eslint.config.mjs`, `middleware.ts`, `next-config.ts`, `package-lock.json`, `package.json`, `postcss.config.mjs`, `tailwind.config.js`, `tsconfig.json`.
- **lib/** 📚: Utility libraries.
- **node_modules/** 📦: Dependency files (auto-generated).
- **public/** 🌐: Static assets.
  - `.env`, `.env.example`, `.gitignore`, `README.md`, `TODO.todo`, `favicon.ico`.
- **types/** 🔍: Type definitions.
  - `globals.d.ts`, `types.ts`.
- **utils/** 🛠️: Utility functions.
  - `motion.ts`, `roles.ts`, `env`.
- **Root Files** 📄:
  - `.env`, `.example.env`, `.gitignore`, `components.json`, `eslint.config.mjs`, `middleware.ts`, `next-config.ts`, `package-lock.json`, `package.json`, `postcss.config.mjs`, `README.md`.

## 🧪 Testing

Test the app locally by running the development server and checking responsiveness across devices.

## 🌐 Deployment

Deploy using Vercel (recommended for Next.js):
1. Push to GitHub.
2. Connect to [Vercel](https://vercel.com/) and deploy.

Or use Docker:
```bash
docker build -t cms-frontend .
docker run -p 3000:3000 cms-frontend
```

