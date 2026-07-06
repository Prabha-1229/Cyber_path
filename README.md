# 🛡️ CyberPath — Cybersecurity Learning & Career Companion

CyberPath is a responsive, installable **Progressive Web App (PWA)** designed as a comprehensive learning, utility, and career companion for fresher/intern-level cybersecurity students. 

This app is designed to bridge the gap between basic theory and hands-on professional workflows, combining a structure of interactive roadmaps, curated tools, direct command references, automated study planners, real-time news aggregation, and entry-level job feeds into a single unified dashboard.

---

## 🚀 Key Features

### 1. 🛠️ Interactive Tool Hub (Kali & OSINT)
- **Searchable Database**: Quickly search, filter, and discover the most popular cybersecurity tools (Nmap, Wireshark, Burp Suite, Metasploit, Ghidra, and more).
- **Categorization**: Grouped by cybersecurity domains like Reconnaissance, Exploitation, Forensics, Web Security, and Network Auditing.
- **Commands & Copying**: Each tool provides a detailed breakdown of what it is, when to use it, and high-priority terminal command commands with a one-click copy button.

### 2. 🗺️ Guided Learning Tracker
- **Structured Cybersecurity Roadmap**: Organized into distinct milestone phases covering:
  - Phase 1: Networking Basics
  - Phase 2: Linux Fundamentals
  - Phase 3: Web Application Security
  - Phase 4: Network Security
  - Phase 5: Cloud Security
  - Phase 6: Professional Certifications (CompTIA Security+, eJPT, CEH, OSCP)
- **Progress Tracking & Daily Streaks**: A built-in gamified system with an overall progress bar and a daily consistency streak counter to maintain learning momentum.
- **Custom Study Notes**: Save specific comments, notes, or flags per topic directly within the browser local storage.

### 3. 📅 Automated Task Builder
- **Weekly Goal Allocation**: Set a broader core objective (e.g., "Learn OWASP Top 10" or "Master Nmap") and the applet will automatically generate a structured 7-day breakdown of checkable daily tasks.
- **Custom Progress Tracking**: Complete items sequentially to visual updates across your daily stats.

### 4. 📰 Real-Time Intel Feed
- **RSS-Aggregated Threat Intel**: Pulls recent cybersecurity vulnerability disclosures, research, and technical blogs from industry-standard feeds like *The Hacker News*, *BleepingComputer*, and *KrebsOnSecurity* using browser-friendly secure API streams.

### 5. 💼 Curated Jobs Tracker
- **Entry-Level Focus**: Aggregates and displays remote or hybrid entry-level security roles, internships, associate positions, and trainee listings.
- **Bookmarking**: Save or bookmark open opportunities of interest to build your application pipeline.

---

## 🎨 Visual Identity & Theme
Built with a **Sophisticated Dark** aesthetic:
- Solid charcoal-to-black gradient canvas panels matching cyber-operations environments.
- Emerald green accents (#10b981) to signify secure, audited connection layers.
- Responsive design tailored beautifully for desktop sidebars and mobile bottom navigation bars.

---

## 🛠️ Built With

- **Framework**: React 19 + TypeScript
- **Styling**: Tailwind CSS v4
- **Icons**: Lucide React
- **PWA Capabilities**: Service Worker caching engine and static resource cache (`manifest.json` + `sw.js`).
- **Data Persistence**: `localStorage` to preserve progress, study notes, and job bookmarks on-device.

---

## 📦 Local Installation & Setup

If you have downloaded this project and want to run it locally on your computer, follow these simple steps:

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed on your system.

### Steps
1. **Unzip/Clone the Repository** and navigate into the folder:
   ```bash
   cd cyberpath
