# UMC 9th Mission - Web Application

This project is a React-based web application developed for the UMC 9th Mission. It features a complete authentication system and content management for "LP" (posts/articles).

## 🛠 Tech Stack

-   **Framework**: [React](https://react.dev/) + [Vite](https://vitejs.dev/)
-   **Language**: [TypeScript](https://www.typescriptlang.org/)
-   **Styling**: [Tailwind CSS](https://tailwindcss.com/)
-   **State Management**: [TanStack Query (React Query)](https://tanstack.com/query/latest) + Context API
-   **Routing**: [React Router DOM](https://reactrouter.com/)
-   **Form Handling**: [React Hook Form](https://react-hook-form.com/) + [Zod](https://zod.dev/)
-   **HTTP Client**: [Axios](https://axios-http.com/)

## ✨ Key Features

-   **Authentication**:
    -   Sign Up & Login
    -   Google OAuth Integration
    -   Protected Routes (Private/Public guards)
-   **LP (Content) Management**:
    -   View List of LPs (Home)
    -   View LP Details (`/lp/:id`)
    -   Create New LP (`/create`)
-   **User Profile**:
    -   My Page (`/my`)

## 📂 Project Structure

```
src/
├── apis/        # API integration modules
├── assets/      # Static assets (images, fonts)
├── components/  # Reusable UI components
├── constants/   # Global constants
├── context/     # React Context (e.g., AuthContext)
├── hooks/       # Custom React Hooks
├── layouts/     # Page layouts (HomeLayout, ProtectedLayout)
├── pages/       # Application pages (Views)
├── types/       # TypeScript type definitions
└── utils/       # Utility functions
```

## 🚀 Getting Started

1.  **Install dependencies**:
    ```bash
    npm install
    # or
    pnpm install
    ```

2.  **Run the development server**:
    ```bash
    npm run dev
    # or
    pnpm dev
    ```

3.  **Build for production**:
    ```bash
    npm run build
    # or
    pnpm build
    ```
