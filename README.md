# 🤖 AI-Powered Lead Qualification & Follow-Up Automation

This project showcases an end-to-end, intelligent automation workflow built for B2B SaaS companies to streamline lead qualification and follow-up using low-code tools, APIs, and AI.

It integrates Make.com, OpenAI, Clearbit, HubSpot, and Slack to enrich, score, and route leads automatically — reducing manual work, improving response time, and boosting sales conversion rates.

---

## 🚀 Project Overview

### 📌 Goal
Automate the collection, enrichment, scoring, and engagement of inbound leads submitted through a website or landing page.

### 🔍 Key Capabilities
- Real-time data capture via webhook
- Company and contact enrichment via Clearbit
- AI-powered lead qualification scoring using OpenAI GPT-4
- Conditional routing based on lead score
- CRM creation and Slack alert for high-value leads
- Auto follow-up emails for qualified prospects
- Airtable/Google Sheets logging for tracking

---

## ⚙️ Tools & Integrations

| Function               | Tool/Service         |
|------------------------|----------------------|
| Automation Platform    | [Make.com](https://www.make.com) |
| AI & NLP               | [OpenAI GPT-4](https://platform.openai.com) |
| Data Enrichment        | [Clearbit API](https://clearbit.com) |
| CRM                    | HubSpot              |
| Logging & Backup       | Airtable / Google Sheets |
| Team Communication     | Slack                |
| Forms / Intake         | Typeform / Webflow   |

---

## 🧠 Workflow Architecture

1. **Trigger:** New form submission via webhook
2. **Data Enrichment:** Pull additional data via Clearbit API
3. **Lead Scoring:** Use OpenAI to score lead quality and summarize
4. **Conditional Logic:**
    - High-score (≥7): Notify via Slack, create in CRM, send email
    - Low-score: Log only
5. **Follow-Up:** Personalized email to qualified leads
6. **Logging:** Store all interactions for audit/tracking

![Workflow Diagram](docs/architecture-diagram.png)

---

## 🗃️ Project Structure

ai-lead-automation-project/
│
├── README.md
├── /docs
│ ├── process-map.md
│ ├── architecture-diagram.png
│ ├── prompts-used.md
│ └── training-guide.md
│
├── /make-scenarios
│ ├── scenario-overview.md
│ └── screenshots/
│
├── /api-integrations
│ ├── openai-call-example.json
│ ├── clearbit-call-example.json
│ └── webhook-payload-example.json
│
├── /logs-example
│ └── example-log.json
│
└── LICENSE

yaml
Copy
Edit

---

## 🧪 Sample OpenAI Prompt

```txt
You are a B2B SaaS sales assistant. A new lead has submitted a form.
Based on the data provided (company size, industry, job title, use case),
assign a qualification score from 1 to 10 and explain your reasoning.
📈 Metrics & Outcomes
Metric	Target Outcome
Lead response time	< 5 minutes
Manual input eliminated	90%
Conversion improvement	+15% (after 30 days)
Qualification accuracy	Human-reviewed benchmark

📚 How to Use / Demo
Note: You’ll need accounts on Make.com, OpenAI, and Clearbit to recreate or test this setup.

Clone this repo

Import the Make.com scenario (structure provided)

Update API keys in scenario modules

Connect your form, CRM, and email services

Test with a sample lead submission

📘 License
This project is licensed under the MIT License. See LICENSE for details.

👤 Author

Komolafe Temitope

@komolafetemitope14
LinkedIn | Github 

💡 Want to Collaborate?
Feel free to fork this repo, suggest improvements, or open issues. If you're looking to implement AI automation for your team or product, let’s talk!


---

Let me know if you’d like this delivered as a file (`README.md`) or need help generating the diagram (`architecture-diagram.png`)!








