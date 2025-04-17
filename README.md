# 🎵 Music Learning Platform

A modern, responsive web application built with **Next.js** to showcase featured music courses, webinars, instructors, testimonials, and more for a music school.

---

## 🚀 Features

- 🎹 **Hero Section** – Welcoming and engaging landing banner
- 📚 **Featured Courses** – Highlights top music courses offered
- 🌟 **Why Choose Us** – Showcases the platform's unique strengths
- 🗣️ **Testimonials** – Real student feedback for social proof
- 🎤 **Upcoming Webinars** – Stay updated with live learning sessions
- 🧑‍🏫 **Instructors** – Display skilled instructors from the music school
- 🦶 **Footer** – Clean, minimal footer with essential links

---

## 📁 Project Structure
```
music-learning-platform/
│
├── .next/                  # Next.js build output (auto-generated)
├── node_modules/           # Installed npm packages
├── public/                 # Public assets (images, fonts, etc.)
│
├── src/                    # Main source code folder
│   ├── app/                # App Router directory (Next.js 13+)
│   │   ├── contact/        # Contact page route
│   │   │   └── page.tsx
│   │   ├── courses/        # Courses page route
│   │   │   └── page.tsx
│   │   ├── favicon.ico     # Site icon
│   │   ├── globals.css     # Global styles
│   │   ├── layout.tsx      # Root layout component
│   │   └── page.tsx        # Home page route
│   │
│   ├── components/         # Reusable components
│   │   ├── ui/             # (Currently empty or UI-specific base components)
│   │   ├── FeaturedCourses.tsx
│   │   ├── Footer.tsx
│   │   ├── HeroSection.tsx
│   │   ├── Instructors.tsx
│   │   ├── Navbar.tsx
│   │   ├── TestimonialCards.tsx
│   │   ├── UpcomingWebinars.tsx
│   │   └── WhyChooseUs.tsx
│   │
│   ├── data/               # Static/mock data
│   │   └── music_courses.json
│   │
│   └── utils/              # Utility functions
│       └── cn.ts           # Classname helper (likely tailwind-merge or clsx)
│
├── .eslintrc.json          # Linting configuration
├── .gitignore              # Git ignore rules
├── bun.lock

```          

---

## 🧪 Tech Stack

- **Framework**: Next.js 13+
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: @tabler/icons-react
- **Animation**: Framer Motion

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/music-learning-platform.git
cd music-learning-platform

# Install dependencies
npm install
# or
bun install

npm run dev
# or
bun dev
```
---

## 📸 Screenshots

| Page | Screenshot |
|------|-----------|
| *Home Page* | ![image](https://github.com/user-attachments/assets/f311da4b-0442-4e5e-8b0f-d15a4d67778f) |
| *Courses Page* | ![image](https://github.com/user-attachments/assets/bba2167e-ea55-45a4-a7b1-b8b9290826ff) |
| *Why Choose Us* | ![image](https://github.com/user-attachments/assets/beb7239b-3d9f-4a81-a63d-31c3ccc86277) |
| *Webinar Page* | ![image](https://github.com/user-attachments/assets/0be222e4-e687-49d5-b447-351fd7445344) |
| *Instructors Page* |![image](https://github.com/user-attachments/assets/b6b9ea72-d932-4efd-9f28-38849aece1d9) |
| *All Courses* | ![image](https://github.com/user-attachments/assets/9f1dd0cb-f00c-4fb6-8515-3435310196fc) |
| *Contact Us* | ![image](https://github.com/user-attachments/assets/eaf28061-b11c-428b-a6ab-1dbc4b03ed15) |
| *Footer* | ![image](https://github.com/user-attachments/assets/f0694706-3dd2-4600-bc70-3796aea5bb2d) |
