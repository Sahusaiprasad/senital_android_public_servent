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


 SENITAL_APP_WORK_FLOW

=======APP ICON 
<img width="1254" height="1254" alt="ChatGPT Image Jul 7, 2026, 06_07_51 PM" src="https://github.com/user-attachments/assets/31a5a0d2-2852-46d3-8a72-36b2bcaca9f8" />


=== > INTERFACE 

<img width="1080" height="2404" alt="Screenshot_20260708_181012" src="https://github.com/user-attachments/assets/19e64464-8fa3-4776-91fb-4f4c7722f324" />
== > ALLOW PERMISSON
<img width="1080" height="2404" alt="Screenshot_20260708_185013" src="https://github.com/user-attachments/assets/8cb05021-9861-44c0-a871-f8d69cc4d703" />

==> USER ACCOUNT
<img width="1080" height="2404" alt="Screenshot_20260708_183730" src="https://github.com/user-attachments/assets/48556495-6c69-4d1c-abae-dac117b84101" />
== >  HOME PAGE
<img width="1080" height="2404" alt="Screenshot_20260708_181003" src="https://github.com/user-attachments/assets/5dd6c003-1f15-46da-8c84-bfe729a18727" />
==> CONNECTION WITH FIREBASE
<img width="1080" height="2404" alt="Screenshot_20260708_174317" src="https://github.com/user-attachments/assets/07ddd0f5-316e-4bb0-8dbe-4e32e4eb7f90" />
== > REPORT ISSUE(COMPLAINT)
<img width="1080" height="2404" alt="Screenshot_20260708_185104" src="https://github.com/user-attachments/assets/d8df0109-3a47-4641-aa9c-10db94c4995e" />
== > USER TAB 
<img width="1080" height="2404" alt="Screenshot_20260708_185216" src="https://github.com/user-attachments/assets/026d355a-8fe5-4049-8220-afc5437136dc" />
  
  =====ADMIN TAB LOGIN
== LOGIN
<img width="1080" height="2404" alt="Screenshot_20260708_173554" src="https://github.com/user-attachments/assets/4fd4e266-19f9-4dfc-86fe-3a6f1b5e924f" />
== > ADMIN DASHBOARD
<img width="1080" height="2404" alt="Screenshot_20260708_185237" src="https://github.com/user-attachments/assets/7781feae-9621-495f-83ca-3a7f7e88b530" />
== > COMPLAINT HISTORY
<img width="1080" height="2404" alt="Screenshot_20260708_185242" src="https://github.com/user-attachments/assets/d0e6eb5d-8f07-4c39-aa6e-012a49a0568a" />
== > SOLVING PROBLEM
<img width="1080" height="2404" alt="Screenshot_20260708_185248" src="https://github.com/user-attachments/assets/62955059-a30f-4391-9877-ceb88491e9c2" />











