 Financial Literacy Training App — "FinLit"

### 🧭 Core Concept
You’re developing an **interactive finance literacy app** that does more than just teach—it simulates, tracks, responds, and adjusts based on real-ish market conditions. Think “Bloomberg terminal for students meets Choose Your Own Adventure book written by Wall Street and hosted on Power Pages.”

---

### 💼 User Roles

| Role | Description |
|------|-------------|
| **Student** | Enroll via public signup, receive mock funds, execute trades, track portfolio, participate in webinars |
| **Instructor** | Lead webinars, guide students, simulate market events, review performance |
| **Admin** | Oversee the system, manage accounts, generate reports, run backend tools |
| **Reviewer** | Approves applicants and transitions them into the student system |
| **Chatbot** | GPT-powered assistant to answer questions, simulate news events, and record feedback |

---

### 📊 Tables (Data Backbone)

| Table | Purpose |
|-------|---------|
| `Student` | Central user record (foreign key across apps) |
| `Portfolio` | Tracks value, decisions, visualized performance |
| `InvestmentDecision` | Stores trades, exchange logic |
| `MarketEvent` + `CorpAction` + `MacroEvent` | Drives scenario simulation |
| `Instructor` / `Webinar` | Session orchestration + learning data |
| `Chatbot` / `Interaction` / `StudentFeedback` | NLP interface, sentiment, knowledge tuning |
| `ApplicationSubmission` / `ApprovalCriteria` | Public signup and intelligent screening |
| `AppPerformance` / `Report` | Admin insight and optimization tools |

---

### 📱 Apps and Interfaces

| App | Purpose |
|-----|--------|
| `Investment App` | Students simulate buying/selling assets in daily “open exchange” sessions |
| `Instructor App` | Visualizes student progress, launches webinars, tracks feedback |
| `Admin App` | Controls everything with glorious omnipotence (and Excel reports) |
| `Student Portal (Power Pages)` | Where the learner first lands and launches into their simulation world |

---

### 🔁 Flows (Power Automate)

- **Student Signup Flow**: Public access → Application → Validation → Welcome → Access granted
- **Chatbot Interaction Flow**: Triggered on queries, logs feedback, handles scoring for continuous model improvement

---

### 📈 Key Metrics / Measures

You’ve got calculated fields across students, instructors, and system performance like:
- `Portfolio Net Growth %`
- `Rank vs Peers`
- `Volatility Index`
- `Chatbot Accuracy`
- `Avg Queries per User`

------

