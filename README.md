# IntelliHire

### Your AI-powered mock interview platform for role-based dynamic preparation with real-time feedback, intelligent assessment, and personalized dashboard.

---

## 📌 Project Description

**IntelliHire** is an AI-powered mock interview platform that provides tailored interview experiences based on a candidate’s selected role, tech stack, and experience level. It integrates speech-to-text, text-to-speech, and AI-driven dynamic question generation to simulate real interviews.

Users can sign in using **Clerk authentication**, practice **DSA**, **aptitude**, and **verbal reasoning** questions, and receive **question-wise** and **overall feedback** along with **score tracking** in a personalized dashboard. The platform supports **company-specific behavioral questions**, offers **practice assessments**, and includes **premium subscription tiers** with a **7-day free trial** and **test-mode payment gateway**.

---

## 🧠 Why IntelliHire?

Preparing for interviews can be overwhelming and unstructured. IntelliHire streamlines this by offering:
- A structured, AI-driven mock interview experience
- Real-time feedback and improvement tracking
- Centralized resources for DSA, aptitude, and company-specific preparation
- Seamless onboarding and accessible UI for any level of user

---

## 🚀 Features

### 🔐 Authentication & User Management
- Secure Sign-in/Sign-up with **Clerk Authentication**
- Personalized user data and session tracking

### 🧑‍💻 AI Mock Interviews
- Role and experience-based question generation using AI
- Dynamic and intelligent interviews covering:
  - DSA (Leetcode-level)
  - Aptitude
  - Verbal Reasoning
  - Company-specific behavioral rounds

### 🔊 Real-Time Communication
- **Text-to-Speech**: AI reads the questions aloud
- **Speech-to-Text**: Converts user’s spoken answers to text

### 📊 Dashboard
- View **Best**, **Average**, and **Recent Scores**
- Track **Question-wise feedback** and **Overall performance**
- Highlighted areas of improvement and strengths

### 📚 Practice & Assessment
- Access syllabus-wise content for:
  - DSA
  - Aptitude
  - Verbal
- Attempt time-bound **practice assessments**
- Review **company-wise behavioral questions**

### 💰 Pricing & Subscription
- Dedicated **Pricing Page**
- **Premium access** with additional features
- Integrated **payment gateway (test mode)**
- **7-Day Free Trial** for new users

### 🧾 About & Footer
- **About Us** section:
  - Purpose of IntelliHire
  - How it works
  - Features breakdown
- **Footer**:
  - Subscription form
  - Quick links to other important pages

---


## 📂 Project Structure 

AI-MOCK-INTERVIEW-BUILDVERSE/
├── backend/                      # Express.js backend handling API routes and logic
│   ├── controllers/             # Contains route handlers (feedback, mock interviews, etc.)
│   ├── models/                  # MongoDB schema definitions (e.g., Feedback, User)
│   ├── routes/                  # API endpoint route definitions
│   ├── .env                     # Environment variables for backend config
│   ├── server.js                # Entry point for backend server
│   └── config/                  # DB connection and Clerk middleware config
│
├── frontend/                    # React front-end project
│   ├── public/                  # Static files like models and index.html
│   │   └── models/              # face-api.js model files for facial detection
│   ├── src/                     # Source files for the front-end
│   │   ├── assets/             # Images, icons, and other assets
│   │   ├── components/         # Reusable UI components (Navbar, Footer, Cards, etc.)
│   │   ├── pages/              # Page components like Home, Dashboard, Interview, etc.
│   │   ├── App.jsx             # Root component defining routes
│   │   ├── main.jsx            # React DOM entry point
│   │   ├── api/                # Axios functions for interacting with backend
│   │   └── utils/              # Utility functions (e.g., formatters, helpers)
│
├── .gitignore                   # Specifies files and folders Git should ignore
├── README.md                    # Project description, setup instructions, and docs
├── package.json                 # Project metadata and dependencies for both front-end/back-end
└── LICENSE                      # (Optional) License information




pages/
├── aboutUs.css            # Styles for About Us page
├── aboutUs.jsx            # About Us page content and layout
├── aptitudeAndVerbal.css  # Styles for Aptitude and Verbal page
├── aptitudeAndVerbal.jsx  # Aptitude and Verbal page with practice/syllabus
├── behaviourPage.css      # Styles for behavioral questions
├── behaviourPage.jsx      # Company-wise behavioral questions page
├── dashboard.css          # Styles for user dashboard
├── dashboard.jsx          # Dashboard with scores, feedback, and stats
├── FooterHr.css           # Footer styles
├── FooterHr.jsx           # Footer component with navigation and links
├── HeaderHr.css           # Header styles
├── HeaderHr.jsx           # Navigation bar component
├── howItWorks.css         # Styles for How It Works page
├── howItWorks.jsx         # Workflow explanation page
├── hraboutus.jsx          # About Us for HR
├── hrInterview.css        # HR Interview page styles
├── hrInterview.jsx        # HR Interview interface
├── hrMain.css             # Styles for HR dashboard
├── hrMain.jsx             # HR dashboard for interview/session control
├── hrOruser.css           # Styles for HR/User selector page
├── hrOruser.jsx           # Page routing based on user type
├── interview.css          # Styles for interview session
├── interview.jsx          # Interview component with AI Q&A flow
├── interviewQuestions.css # Styles for interview question listing
├── interviewQuestions.jsx # Component for displaying questions
├── joinInterview.css      # Styles for join interview page
├── joinInterview.jsx      # Component to join ongoing interviews
├── profile.css            # Styles for profile page
├── profile.jsx            # User profile component
├── Questions.css          # General question page styles
├── Questions.jsx          # DSA, aptitude, verbal question practice page
├── Upgrade.css            # Styles for upgrade/premium page
├── Upgrade.jsx            # Subscription upgrade and pricing page

## 🔧 Improvements That Can Be Made

- Expand support to include **HR Integrated tools** with recording
- Provide **resume analysis and feedback**
- Add **Gamified Leaderboard** for DSA and Aptitude practice
- Enable **mobile app** integration
- Support **multi-language interviews**

---

## 👨‍💻 Contributors
**Team - HelloWorld**
- **Abhiram Bikkina**
- **Tharun Kumar Reddy**
- **Dhinesh Veera Bhargav**
- **Pavan Vignesh**

---



