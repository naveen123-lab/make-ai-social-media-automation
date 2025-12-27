## 🔁 Workflow Breakdown

### 1️⃣ Google Sheets Trigger
- Watches new rows added in a Google Sheet
- Reads content links or text from column **A**
- Supports structured input with headers enabled

### 2️⃣ AI Content Generation
- Uses **Google Gemini 2.5 Flash**
- Summarizes the content dynamically using AI
- Prompt Example:

Summarize the following article: {{Content Link}}


### 3️⃣ Extensibility
- Output can be routed to:
- LinkedIn posts
- Facebook posts
- Telegram messages
- Scheduling logic can be applied for:
- One-time posting
- Scheduled posting
- Recurring/daily posting

---

## 🛠 Tools & Technologies Used

- **Make.com (Integromat)**
- **Google Sheets**
- **Google Gemini 2.5 Flash**
- Routers (for future multi-platform distribution)
- API-based integrations (extendable)

---
