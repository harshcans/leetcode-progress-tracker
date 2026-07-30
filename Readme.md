# 🚀 LeetCode Progress Explorer

A modern, responsive, glassmorphic web dashboard built with **React** and **Tailwind CSS** to track LeetCode statistics, analyze topic-wise skill distributions, and compare performance head-to-head with rivals in real-time using the `alfa-leetcode-api`.

🔗 **Live Demo:** [https://leetcode-progress-tracker-nine.vercel.app/](https://leetcode-progress-tracker-nine.vercel.app/)

---

## ✨ Features

- 📊 **Comprehensive Overview**: Real-time stats showing total solved problems, difficulty breakdowns (Easy, Medium, Hard), contest rating, global ranking, and reputation points.
- 📈 **Submission & Skill Analytics**: Interactive progress distribution bars visualizing your difficulty ratios and submission activity.
- 🎯 **Topic Diagnostics**: Decoupled skill-tag tracking that categorizes solved problems into *Fundamental*, *Intermediate*, and *Advanced* topics.
- ⚔️ **Rival Battle Matrix**: Side-by-side comparison matrix allowing you to input any second LeetCode handle and compare your progress head-to-head.
- 🔐 **Zero Default User Setup**: Prompts for a manual username input on first load with automatic **7-day `localStorage` expiration**.
- 🎨 **Glassmorphic UI & Dark Mode**: Features a sleek light glassmorphic backdrop (`backdrop-filter: blur(42px)`) alongside a high-contrast dark mode toggle.
- 🔗 **Direct Profile Access**: One-click shortcuts to open the target profile directly on LeetCode (`https://leetcode.com/u/<harshcans>`).
- 🛡️ **Fault-Tolerant Fetching**: Graceful error handling for missing endpoints (such as 404s on user skills) so the main dashboard never crashes.

---

## 🛠️ Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Icons**: Lucide React (`lucide-react`)
- **API**: `alfa-leetcode-api`
- **Deployment**: Vercel

---
