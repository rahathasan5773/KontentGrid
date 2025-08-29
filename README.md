# KontentGrid

A modern, responsive blogging platform built with the **MERN stack** (MongoDB, Express.js, Next.js, Node.js), inspired by **Medium** and **Dev.to**.  
Create, discover, and engage with quality content in a clean, intuitive interface.

---

## Project Overview

**KontentGrid** is a practice project designed to replicate the core functionality of modern blogging platforms.  
It will include powerful content creation tools, personalized feeds, and community engagement features — all while maintaining simplicity and performance.

This repository tracks my journey in sharpening full-stack development skills and exploring production-grade software design, starting from a blank-slate MERN setup.

---

## Features (Planned MVP Scope)

> **Note:** The project is currently in the initial setup phase. The features listed below represent the planned scope for the Minimum Viable Product (MVP).

- **User Authentication & Profiles**
  - Email/password & social login (Google, GitHub)
  - Manage personal profiles with bio, avatar, and social links
- **Content Creation & Publishing**
  - Rich text editor with media upload support
  - Drafts, scheduled publishing, and SEO optimization
- **Content Discovery**
  - Personalized home feed, trending tags, and advanced search
- **Engagement**
  - Likes, comments (nested), and sharing
  - Follow system for users and tags
- **Dashboards**
  - Writer dashboard with analytics
  - Reader dashboard with reading history & bookmarks
- **Responsive Design**
  - Optimized for mobile, tablet, and desktop
- **Moderation & Notifications**
  - Reporting system, content filtering, and real-time notifications

---

## Tech Stack

- **Frontend:** **Next.js** / **React** (with TailwindCSS planned)
- **Backend:** **Node.js** + **Express.js**
- **Database:** **MongoDB** (with Mongoose ODM)
- **Authentication (Planned):** JWT + OAuth (Google, GitHub)
- **Deployment (Planned):** Vercel (Frontend) + Render (Backend) + MongoDB Atlas

---

```text
================================================================================
  INSTALLATION, SETUP & PROJECT DETAILS
================================================================================


# === 1. INSTALLATION & SETUP ===

  # Clone the repository
  git clone https://github.com/rahathasan5773/KontentGrid.git
  cd KontentGrid

  # Install backend dependencies
  cd server
  npm install
  cd ..

  # Install frontend dependencies
  cd client
  npm install
  cd ..

  # Create an environment file at "/server/.env" with the following content:
  # MONGO_URI=your_mongo_db_connection_string
  # PORT=5000


# === 2. RUN DEVELOPMENT SERVER ===

  # Run this command from the project root directory
  npm run dev


# === 3. PROJECT STRUCTURE ===

  KontentGrid/
  │
  ├── client/        # Next.js frontend application
  │
  ├── server/        # Express.js & MongoDB backend API
  │
  ├── .gitignore
  └── README.md


# === 4. CONTRIBUTING ===

  This is a personal practice project, but contributions, suggestions, and
  discussions are always welcome.

  - Open an issue to report a bug or discuss a feature.
  - Submit a pull request with improvements.
  - Share your feedback on project design and architecture.


# === 5. LICENSE ===

  This project is open-source under the No License.


# === 6. ACKNOWLEDGEMENTS ===

  Inspired by:
  - Medium (https://medium.com/)
  - Dev.to (https://dev.to/)

================================================================================
