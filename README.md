# 🐅 GoalSyncTiger – Smart Progress Tracker

GoalSyncTiger (**Tiger**) is a **goal-oriented personal progress tracking platform** designed to keep users consistent, motivated, and publicly accountable for their growth.  
It’s an automated career growth assistant that integrates with platforms you already use, monitors your progress, motivates you daily, and shares your achievements with the world.

---

## Technologies Used

**Backend**
- **Java (Spring Boot)** — Robust backend framework for scalable APIs.  
- **MySQL** — Relational database for structured data storage.  
- **Stripe Payment Gateway** — Secure payment processing for premium subscriptions.  
- **Firebase Cloud Messaging** — Push notifications for reminders and motivation.  
- **LinkedIn API** — Automated achievement posting.  
- **LeetCode API & GitHub API** — Real-time progress data fetching.

**Frontend**
- **Angular** — Frontend framework for dynamic UI.  
- **PrimeNG** — Angular UI component library.  
- **HTML5, CSS3, TypeScript** — Core web technologies for responsive design.

---

## Implemented Functionalities

### 💳 Premium Subscription
- Integrated **Stripe** to handle secure premium plan purchases.

### 🎯 Goal Setting & Tracking
- Connect **GitHub** and **LeetCode** accounts to set:
  - Target commits on GitHub
  - Target submissions on LeetCode  
- Progress is tracked automatically with **real-time API updates**.

### 🔔 Notifications & Motivation
- **Daily reminders** and motivational prompts via **Firebase Cloud Messaging**.

### 📢 Automated LinkedIn Posting
- On goal completion, Tiger **auto-posts achievement updates** to the user’s LinkedIn profile (toggleable per-user).

### 📊 Real-Time Dashboard
- Live progress charts, streak counters and progress widgets.

### 🖥️ Modern UI
- Responsive design built with **Angular + PrimeNG** for a mobile-friendly experience.

### 🧑‍💼 Profile Roasting & Feedback
- Peer-review system where users can submit LinkedIn/GitHub profiles for **constructive feedback**.

### 👥 Active Community
- Serving **20+ active users** and growing.

---

## Screenshots

**Dashboard**  
![Dashboard](https://github.com/user-attachments/assets/713ad8b6-4a76-4edd-927f-3d88e70b271e)

**Profile Roastings**  
![Roastings](https://github.com/user-attachments/assets/a0801c94-066f-41d8-b0e9-f1407be83d59)

**Target Setting**  
![Target Setting](https://github.com/user-attachments/assets/f1565f11-17bc-49e4-95a3-3a8b16e489f6)

**Monthly Streak**  
![Monthly Streak](https://github.com/user-attachments/assets/d8b04489-5658-451c-ac75-e19197ea5d3a)

**LinkedIn Posting Toggler**  
![LinkedIn Toggler](https://github.com/user-attachments/assets/00fef4fa-8cdd-41d1-a9bf-098bd5e608d1)

---

## Planned Enhancements
- **Gamification** — Badges, levels, and rewards for consistency.  
- **Team Challenges** — Group goals and competitions.  
- **Advanced Analytics** — Deeper insights and productivity trends.  
- **Mobile Apps** — Native Android & iOS apps for on-the-go tracking.  
- **More Integrations** — Additional platforms and calendar sync.

---

## Run Locally

```bash
# Frontend
cd frontend
ng serve --open

# Backend (example)
cd backend
./mvnw spring-boot:run
