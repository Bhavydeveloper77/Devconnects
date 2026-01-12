# DevConnects - Developer Community Platform

**DevConnects** (formerly CodeRush) is a modern, beginner-friendly developer community platform designed to help coders connect, learn, and build together. It features monthly hackathons, a member directory, and a gamified leaderboard system.

## 🚀 Features

*   **Community Hub**: A landing page with rich animations and "Join Community" calls to action.
*   **Member Registration**: Simple one-time registration flow that unlocks Discord and Telegram community links.
*   **Monthly Hackathons**: Dedicated section for monthly coding challenges with a live leaderboard.
*   **Gamified Leaderboard**: Top 3 animated podium and detailed scoring breakdown (Quality, Innovation, Presentation).
*   **Member Directory**: Explore registered members, their skills, and bios.
*   **Admin Panel**: A mock admin interface to grade submissions and manage leaderboards.
*   **Neon-Dark Theme**: A sleek, developer-focused UI built with Tailwind CSS.

## 🛠️ Tech Stack

*   **Frontend**: [React](https://react.dev/) (Vite)
*   **Styling**: [Tailwind CSS](https://tailwindcss.com/) + CSS Modules
*   **Animations**: [Framer Motion](https://www.framer.com/motion/)
*   **Icons**: [React Icons](https://react-icons.github.io/react-icons/) (FontAwesome, Bootstrap)
*   **State/Persistence**: LocalStorage (Mock Backend)

## 📦 Installation & Setup

1.  **Clone the repository** (or unzip the project):
    ```bash
    git clone https://github.com/yourusername/DevConnects.git
    cd DevConnects
    ```

2.  **Install Dependencies**:
    ```bash
    npm install
    ```

3.  **Run Locally**:
    ```bash
    npm run dev
    ```
    The app will start at `http://localhost:5173` (or similar).

## 🧪 Testing

*   **Unit Tests**: Run Jest tests for logic validation.
    ```bash
    npm test
    ```
*   **E2E Tests**: Run Cypress for end-to-end user flows.
    ```bash
    npm run e2e
    ```

## 🔑 Admin Access (Mock)

To grade hackathon submissions, access the admin panel at `/admin`.

*   **URL**: `http://localhost:5173/admin`
*   **Username**: `Bhavy_Admin`
*   **Password**: `ADMIN123`

## 📂 Project Structure

```
DevConnects/
├── src/
│   ├── components/    # Reusable UI (Navbar, Footer, Leaderboard)
│   ├── pages/         # Page Views (Home, Join, Hackathon, Members, Admin)
│   ├── utils/         # Helpers (storage.js for persistence)
│   ├── __tests__/     # Unit Tests
│   ├── App.jsx        # Main Router
│   └── config.js      # Global Config (Links, Branding)
├── cypress/           # E2E Tests
└── ...
```

## 📝 License

© 2026 DevConnects Community. All rights reserved.
