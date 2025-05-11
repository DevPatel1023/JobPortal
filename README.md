# 🧑‍💼 Hired - Job Portal

![Hired Job Portal Banner](./f44721c6-b160-4499-8b1e-ee655a52f651.png)

Welcome to **Hired**, a modern job portal where candidates can find their dream jobs and recruiters can post jobs to discover top talent. Built with a powerful and sleek tech stack to deliver a smooth and secure experience for all users.

## 🌐 Live Demo

> Coming soon...

---

## 🛠 Tech Stack

- **Frontend**: [React.js](https://reactjs.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/), [shadcn/ui](https://ui.shadcn.com/)
- **Authentication**: [Clerk.dev](https://clerk.dev/)
- **Database & Backend**: [Supabase](https://supabase.com/)

---

## 👥 User Roles

### 🔍 Candidate

- Register and log in via Clerk
- Browse and search job listings
- View job details
- Apply to jobs

### 🧑‍💼 Recruiter

- Register and log in via Clerk
- Post new job listings
- Manage and edit existing listings
- View applications

---

## 📸 Preview

![Screenshot](./f44721c6-b160-4499-8b1e-ee655a52f651.png)

---

## 🚀 Features

- 🔐 Secure Auth with Clerk
- 📄 Dynamic job posting & application system
- 🎨 Clean UI using Tailwind and shadcn
- ⚡ Instant database updates via Supabase
- 🎯 Role-based access for Recruiters and Candidates

---

## 📁 Folder Structure (Frontend)

src/
├── components/
│ ├── JobCard.jsx
│ ├── Navbar.jsx
│ └── ...
├── pages/
│ ├── Home.jsx
│ ├── Dashboard.jsx
│ ├── JobDetails.jsx
│ └── ...
├── utils/
├── hooks/
├── App.jsx
└── main.jsx


---

## 📦 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/job-portal.git
   cd job-portal

2. **Install Dependencies**
   ```bash
   npm install
   
3. **Setup Clerk**
   - Create a Clerk project
   - Add your frontend API in .env
   ```bash
   VITE_CLERK_PUBLISHABLE_KEY=your_key_here
   
4. **Configure Supabase**
   - Create a Supabase project
   - Add your project URL and anon key in .env:
   ```bash
     VITE_SUPABASE_URL=https://xyzcompany.supabase.co
     VITE_SUPABASE_ANON_KEY=your_key_here

5. **Run the App**
   ```bash
   npm run dev
