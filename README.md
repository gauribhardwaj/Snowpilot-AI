# ❄️ Snowpilot AI — Autonomous Change Management Co-Pilot

> Why am I wasting developer time on SNOW approvals?

**Snowpilot AI** is an AI-powered agent that automates and augments the ServiceNow (SNOW) change management lifecycle using LLMs. It reads your pull requests, creates compliant SNOW tickets, attaches release artifacts, and intelligently follows up for approvals — so you can focus on building, not babysitting workflows.

---

## 🚀 Features

- ✍️ **Auto-Create SNOWs** from Bitbucket/GitHub PR titles and descriptions
- 📎 **Attach logs, release evidence, and business approval emails**
- 🔁 **Follow up for approvals** via Slack/Email
- 🔔 **Notify on rejections** with summarized reasons and next steps
- 📊 **Streamlit Dashboard** for SNOW lifecycle visibility
- ⚙️ **YAML-based per-team config** for custom rules
- 🔁 **Fallback logic + escalation pathways** for incomplete PRs or missing context

---

## ⚙️ Tech Stack

- 🧠 OpenAI GPT (fine-tuned prompts)
- 🧾 Bitbucket/GitHub API for PR data
- 🌐 ServiceNow API for ticket creation/promotion
- 📈 Streamlit for live dashboard
- 🔗 Slack & Email integration for notifications
- 🔐 YAML for team-specific rule configuration

---

## 📦 Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/gauribhardwaj/Snowpilot-AI.git
cd Snowpilot-AI
