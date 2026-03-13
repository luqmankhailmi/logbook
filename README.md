# Logbook

A personal work journal for developers and knowledge workers. Log what you build, learn, and accomplish every day — then surface patterns, track goals, and get AI-powered reflections from your own data.

![Stack](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=flat&logo=springboot&logoColor=white)
![Stack](https://img.shields.io/badge/React-18-61DAFB?style=flat&logo=react&logoColor=white)
![Stack](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=flat&logo=postgresql&logoColor=white)
![Stack](https://img.shields.io/badge/Docker-ready-2496ED?style=flat&logo=docker&logoColor=white)

---

## What It Is

Most of what you do at work disappears by the end of the day. Logbook gives it a place to live.

It's a structured daily journal built around five entry types that map to how knowledge work actually happens — notes, skills learned, tasks completed, events attended, and code shipped. Everything lands on a calendar. Over time, patterns emerge.

---

## Features

### 📔 Journal & Calendar
Log entries by type, tag, mood, and time. Navigate by month. Everything is one click away on the day it happened.

### 🎯 Goals & Milestones
Set goals with deadlines and break them down into milestone checklists. A progress ring updates as you check things off. Days where milestones were completed are marked on the calendar.

### 📊 Stats & Heatmap
A GitHub-style activity heatmap, streak counters, entry breakdown by type, and a day-of-week activity chart. See exactly how consistent you've been.

### 🤖 AI Insights
Six reflection presets — weekly summary, learning patterns, productivity check, commit digest, motivation, and goals check. Each one reads your actual journal entries and responds with something specific to you, not generic advice.

### 🔀 GitHub Integration
Connect your GitHub account and watch repositories. Every push automatically creates a Commit entry — your code history becomes part of your journal without any manual logging.

### 📤 Export
Download everything as JSON (full backup) or CSV (entries in spreadsheet format). Your data is always yours to take.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Java 21, Spring Boot 3, Spring Security |
| Database | PostgreSQL 16, Flyway migrations |
| Frontend | React 18, TypeScript, Vite, Tailwind CSS |
| State | Zustand |
| AI | Groq API (Llama 3.1 8B) |
| Infrastructure | Docker, nginx, Railway |

---

## License

MIT
