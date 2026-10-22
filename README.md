# ⏱️ Daily Routine & Study Command Center

An interactive, customizable **Daily Task & Study Dashboard** built for high-output study days (**06:30 AM – 11:30 PM**). It balances **4 deep study sessions (2–3 hours each)** with a morning gym session, nutritious meal breaks, an evening outdoor walk for fresh air, and 7 hours of recovery sleep.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-indigo.svg)

---

## ✨ Key Features

- **📚 4 Dedicated Study Sessions (2–3 Hours Each)**: Pre-configured with four focused study blocks totaling **9.5 hours/day**, with automatic validation to ensure each session stays within the optimal 2–3 hour window.
- **✏️ Fully Editable & Interactive Timeline**:
  - Add, edit, or delete schedule blocks (custom start/end times, categories, focus tags, and notes).
  - Expandable task checklists inside every time slot—add, check off, or remove subtasks on the fly.
  - Category filters (`All`, `Study`, `Gym & Air`, `Meals & Breaks`, `Routine`).
- **⏲️ Built-In Study Focus Timer**:
  - Linked directly to your 4 study sessions.
  - Supports **Pomodoro (25m)**, **Deep Work (50m)**, or **Full Session (2.5h)** countdown modes with Web Audio completion chimes.
- **📊 Real-Time Analytics & Visual Day Scrubber**:
  - Live clock & active block banner with a **Time Preview Scrubber** to inspect your schedule at any time of day.
  - Proportional 17-hour active timeline bar and an interactive **24-Hour Time Allocation Doughnut Chart** powered by Chart.js.
- **💾 Persistent Local Storage & Dark Mode**:
  - All schedule edits, task completions, theme preferences, and daily scratchpad notes auto-save to `localStorage`.
  - One-click **Copy Plan** button exports your formatted daily checklist to your clipboard.

---

## 📅 Default Daily Schedule Blueprint (06:30 AM – 11:30 PM)

| Time Slot | Duration | Activity Block | Category |
| :--- | :--- | :--- | :--- |
| **06:30 AM – 08:30 AM** | 2.0 hrs | Morning Wake Up & Gym Session | 🏋️ Gym & Outdoors |
| **08:30 AM – 10:00 AM** | 1.5 hrs | Shower, Breakfast & Desk Setup | 🌙 Routine & Prep |
| **10:00 AM – 12:30 PM** | 2.5 hrs | **Study Session 1**: Core Concepts & Deep Work | 📚 Study Session |
| **12:30 PM – 01:30 PM** | 1.0 hr | Lunch & Midday Recharge | 🍽️ Meals & Break |
| **01:30 PM – 04:00 PM** | 2.5 hrs | **Study Session 2**: Problem Solving & Practice | 📚 Study Session |
| **04:00 PM – 04:30 PM** | 0.5 hr | Afternoon Refreshment & Stretch Break | 🍽️ Meals & Break |
| **04:30 PM – 07:00 PM** | 2.5 hrs | **Study Session 3**: Projects, Mock Tests & Review | 📚 Study Session |
| **07:00 PM – 08:00 PM** | 1.0 hr | Outside for Fresh Air & Evening Walk | 🏋️ Gym & Outdoors |
| **08:00 PM – 09:00 PM** | 1.0 hr | Dinner & Evening Unwind | 🍽️ Meals & Break |
| **09:00 PM – 11:00 PM** | 2.0 hrs | **Study Session 4**: Active Recall, Flashcards & Revision | 📚 Study Session |
| **11:00 PM – 11:30 PM** | 0.5 hr | Night Wind-Down & Sleep by 11:30 PM | 🌙 Routine & Prep |
| **11:30 PM – 06:30 AM** | 7.0 hrs | Overnight Recovery Sleep | 💤 Rest Window |

---

## 📂 Repository Structure

```text
daily-study-dashboard/
├── index.html        # Main application entry point (GitHub Pages ready)
├── css/
│   └── styles.css    # Custom scrollbar and animation styles
├── js/
│   └── app.js        # Application state, timeline renderer, timer & Chart.js logic
├── .gitignore        # Standard Git ignore rules
├── LICENSE           # MIT License
└── README.md         # Project documentation
```

---

## 🚀 How to Upload to GitHub & Host on GitHub Pages

### Option 1: Upload via GitHub Web Interface (No CLI Needed)
1. Go to [github.com/new](https://github.com/new) and create a new repository (e.g., `daily-study-dashboard`).
2. Click **uploading an existing file** on the quick-setup page (or **Add file → Upload files**).
3. Unzip `daily-study-dashboard.zip` and drag-and-drop `index.html`, `css/`, `js/`, `README.md`, `LICENSE`, and `.gitignore` into the browser.
4. Click **Commit changes**.
5. To make it live on the web: go to **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, and click **Save**. Your dashboard will be live at `https://<your-username>.github.io/daily-study-dashboard/`!

### Option 2: Push via Git Command Line
```bash
unzip daily-study-dashboard.zip -d daily-study-dashboard
cd daily-study-dashboard

git init
git add .
git commit -m "Initial commit: Interactive Daily Task & Study Dashboard"
git branch -M main
git remote add origin https://github.com/<your-username>/daily-study-dashboard.git
git push -u origin main
```

---

## 🛠️ Running Locally

No build tools or `npm install` required. Simply open `index.html` in any modern web browser, or serve the folder locally:

```bash
# Using Python 3
python3 -m http.server 8000
# Then open http://localhost:8000 in your browser
```

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for details.
