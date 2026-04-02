# ⏱ Time Planner for You

> An AI-powered time management tool to help you take control of every day.

🌐 **Live Demo:** https://time-planner-sepia.vercel.app

---

## ✨ Features

### 📋 Daily Planner
- Add tasks with estimated time
- Tag system (important / urgent / easy to procrastinate, etc.)
- Random task picker with slot-machine animation & confirmation
- Task launch flow based on the **"5-Minute Start Effect"** from psychology
- 5-min countdown → auto-switches to count-up timer; draggable floating widget with minimize / fullscreen modes
- Daily time overview pie chart

### ⏰ Focus Timer
- Flip-clock style large digit display
- Three modes: Current Time / Countdown / Count-up
- Quick presets (15 / 30 / 45 / 60 min) or custom duration

### 🕰 Time Perception
- Real-time dot-matrix progress for: this year, this month, today, this hour
- Lifetime progress bar (customizable birth year & life expectancy)
- A visual reminder of how time flows

### 📖 Review
- Calendar view — click any date to see that day's data
- Task completion stats + time deviation analysis (over / under estimates)
- Attribution tags (distracted by phone / task harder than expected / low energy, etc.)
- Daily journal with voice input support
- **AI-powered personalized review**: supports Qwen / OpenAI / DeepSeek; three AI personas (Analytical / Enthusiastic / Strict)
- Export data to XLSX

### ⚙️ Settings
- Custom username & avatar
- Dark / Light theme toggle
- Theme color picker (purple / blue / green / orange)
- AI provider configuration (user-supplied API Key, stored locally only)
- Cumulative focus time & time estimation accuracy stats

---

## 🤖 AI Review Configuration

Supports major AI providers — bring your own API Key:

| Provider | Model | Get API Key |
|----------|-------|-------------|
| Qwen (Alibaba) | qwen-turbo | [Alibaba Cloud Bailian](https://bailian.aliyun.com) |
| OpenAI | gpt-4o-mini | [OpenAI Platform](https://platform.openai.com) |
| DeepSeek | deepseek-chat | [DeepSeek](https://platform.deepseek.com) |

> ⚠️ Your API Key is stored in your browser's localStorage only — it is never uploaded to any server.

---

## 🛠 Tech Stack

- Pure HTML / CSS / JavaScript — no frameworks
- Chart.js for data visualization
- SheetJS for XLSX export
- Lucide Icons
- Google Fonts (Inter + Instrument Serif + LXGW WenKai)
- Local data storage via localStorage

---

## 🚀 Getting Started

Clone the repo and open `index.html` in your browser:

```bash
git clone https://github.com/tansy9725-collab/Time-Planner.git
cd Time-Planner
# Open index.html in your browser
```

> **Note:** The AI review feature requires a server environment (or the live demo) due to browser CORS restrictions when opening local HTML files.

---

## 📸 Screenshots

![Daily Planner](screenshots/today.png)
![Time Perception](screenshots/time.png)
![AI Review](screenshots/review.png)

---

## 👩‍💻 Development

Designed and developed by [Tansy](https://github.com/tansy9725-collab), with **Claude Code** as AI-assisted development partner, driven by iterative prompt engineering.

---

## 📄 License

MIT License
