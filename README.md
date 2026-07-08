# senital_android_public_servent
# Sentinel

Sentinel is a community issue-reporting app that lets users report problems (bugs, complaints, or real-world issues) with location tagging, while admins track, manage, and resolve them from a centralized dashboard.

## 🚀 Features

- **User Authentication** — Secure email/password login and registration with persistent sessions
- **Automatic Profile Creation** — Every new user gets a default profile on sign-up
- **Report Issue** — Users can submit complaints/issues with description, severity, category, and optional screenshot
- **Location Tagging** — Complaints are tagged with the user's location and shown on an interactive map
- **Complaint History** — Users can view the status and history of all their submitted reports
- **Admin Dashboard** — Admins can view, filter, and manage all complaints, update statuses, and see complaint locations on a map
- **Role-Based Access Control** — Clear separation between user and admin permissions, enforced at the database level

## 🛠 Tech Stack

- **Frontend:** React
- **Backend / Database:** Firebase Firestore
- **Authentication:** Firebase Authentication (Email/Password)
- **Maps:** Google Maps / Leaflet
- **Hosting:** Google Cloud Run

## 📂 Project Structure

```
sentinel/
├── src/
│   ├── components/       # Reusable UI components (buttons, forms, cards)
│   ├── pages/            # Main app screens (Login, Dashboard, Admin, Report Issue)
│   ├── services/         # Firebase config, auth, and database logic
│   └── utils/            # Helper functions
├── public/               # Static assets
├── .env                  # Environment variables (not committed)
└── README.md
```

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/sentinel.git
cd sentinel
```

### 2. Install dependencies
```bash
npm install
```

### 3. Configure environment variables
Create a `.env` file in the root directory:
```
GEMINI_API_KEY=your_gemini_api_key
FIREBASE_API_KEY=your_firebase_api_key
FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
FIREBASE_PROJECT_ID=your_project_id
```
> ⚠️ Never commit your `.env` file — make sure it's listed in `.gitignore`.

### 4. Run the app locally
```bash
npm run dev
```
The app should now be running at `http://localhost:3000` (or the port shown in your terminal).

## 🔐 Roles & Permissions

| Role  | Permissions |
|-------|-------------|
| User  | Submit complaints, view own complaint history and status |
| Admin | View all complaints, update status, view complaint locations on map, manage users |

Admin access is granted manually via Firebase custom claims — it cannot be self-assigned by any user.

## 🗺 Roadmap / Future Improvements

- Push notifications for complaint status updates
- Complaint categorization with AI-assisted tagging
- Multi-language support

## 👥 Team

| Name | Role |
|------|------|
| _SAI PRASAD _ | _e.g. Full-stack Developer_ |
| _TANVESH_  | _e.g. UI/UX Designer_ |
| _DIVYA_  | _e.g. Backend Developer_ |

## 📄 License

This project was built for [HACK 2 SKILLS
] and is licensed under the MIT License.
