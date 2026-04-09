# DayDraft 🌿

Aesthetic daily task planner with progress tracking, streaks, and Azure automation.

## Overview
DayDraft is a simple, visually soothing task planner that helps users organize their daily tasks. It tracks progress, maintains a streak for task completion, and integrates with Azure Logic Apps for daily reminders.

## Live Demo
- Web App (Azure): [Link coming soon]
- GitHub Pages: [Link coming soon]

## Key Features
- Add tasks for **today** or **tomorrow**
- Quick-add buttons (e.g., Work, Study, Lunch, etc.)
- Custom tasks with user-defined buttons
- Progress bar tracking daily task completion
- Streak system: increase streak when all tasks are completed
- Automated daily email reminders via Azure Logic Apps
- Persistent task storage with `localStorage`
- Cloud deployment via GitHub Actions to Azure

## Tech Stack
- Front-end: HTML, CSS, Vanilla JavaScript
- Cloud: Azure App Service, Logic Apps
- CI/CD: GitHub Actions
- Data: localStorage (future plans for cloud persistence)

## How It Works
1. Open `planner.html` to add tasks for tomorrow.
2. Quick buttons let you add tasks easily; custom buttons allow flexibility.
3. Open `index.html` to see today’s tasks.
4. Check off tasks and watch your progress bar grow.
5. Complete all tasks? Your streak increases!
6. At midnight, Azure Logic Apps sends you a reminder email to help you plan for the next day.

## CI/CD with GitHub Actions
- Every push to `main` triggers deployment to Azure App Service.
- Workflow defined in `.github/workflows/main_projectwebdemo.yml`.

## Screenshots
(Add screenshots from your demo here)

## What I Learned
- Deploying static sites to Azure App Service
- Scheduling workflows with Logic Apps
- Building a streak-based productivity UX
- CI/CD integration with GitHub Actions
- Using localStorage for persistent data

## Future Enhancements
- Store tasks in Azure Table Storage or Cosmos DB
- Add multi-device sync
- User authentication
- Dark mode
- Custom reminders

---

Made with ☕, code, and a sprinkle of Azure magic.
