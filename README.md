# Job Notification Tracker

A premium SaaS-style web application designed to help users track job applications with a calm, intentional, and coherent interface. This project demonstrates a serious B2C product feel using vanilla web technologies without external frameworks.

## 🚀 Features

-   **Smart Dashboard**: View realistic job listings with intelligent match scoring based on your preferences.
-   **Preference Engine**: Configure role keywords, locations, work modes, and skills to tailor the job feed.
-   **Match Scoring**: Deterministic scoring algorithm (0-100) to highlight the best opportunities based on user criteria.
-   **Daily Digest**: Simulate a daily 9AM email digest of top-matched jobs.
-   **Status Tracking**: Track application status (Not Applied, Applied, Rejected, Selected) with visual badges and history.
-   **Saved Jobs**: Bookmark interesting roles for later.
-   **System Testing**: Built-in checklist to verify system integrity before "shipping".
-   **Proof & Submission**: Artifact collection and validation workflow.
-   **Persistence**: All data (preferences, status, saved jobs, history) persists via `localStorage`.

## 🎨 Design Philosophy

-   **Calm & Intentional**: No flashy animations, gradients, or noise. High whitespace and muted colors.
-   **Coherent**: Strict adherence to a 4-color palette and consistent spacing scale (8px, 16px, 24px, 40px, 64px).
-   **Typography**: Confident serif headings (*Libre Baskerville*) paired with clean sans-serif body text (*Inter*).

## 🛠️ Tech Stack

-   **HTML5**: Semantic structure.
-   **CSS3**: Custom design system with CSS variables for strict consistency.
-   **JavaScript (Vanilla)**: Single Page Application (SPA) logic using hash routing and local storage state management.

## 📂 Project Structure

```text
D:\Job_Notification_Tracker
├── index.html      # Main application logic, routing, and layout
├── styles.css      # Design system, tokens, and component styles
└── README.md       # Project documentation
```

## 🚦 How to Run

1.  Navigate to the project folder `D:\Job_Notification_Tracker`.
2.  Open `index.html` in any modern web browser (Chrome, Edge, Firefox).
3.  The app will launch directly; no build step or server is required.

## 🧪 Testing & Usage

1.  **Start**: Click "Start Tracking" on the home page.
2.  **Configure**: Go to **Settings** to define your role, location, and skills.
3.  **Browse**: Check the **Dashboard** to see jobs scored against your preferences.
4.  **Verify**: Navigate to the **Proof** tab (or `/jt/07-test`) to access the built-in system test checklist.

## 📦 Deployment

This project is static and can be deployed to any static host (Vercel, Netlify, GitHub Pages) by uploading the `index.html` and `styles.css` files.

---
*Built with a focus on premium UI/UX principles.*