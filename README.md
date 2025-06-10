# 📬 Email Cleanup Agent – AI-Powered Inbox Declutter

Welcome to the repository for the **Email Cleanup Agent**, an AI-driven workflow that helps you automate and declutter your email inbox. This project uses [n8n](https://n8n.io) for workflow automation and OpenAI’s GPT-4o mini model to intelligently classify and clean up emails.

## 🚀 What This Workflow Does

This n8n workflow:

1. Connects to your email inbox (e.g., Gmail or IMAP-based account).
2. Fetches unread or all recent emails.
3. Uses an AI model to classify each email as:
   - **Useful** (e.g., personal, job-related, documents, security alerts)
   - **Not Useful** (e.g., promotions, social media, app notifications)
4. Archives or deletes not useful emails automatically.
5. Leaves important emails untouched for your attention.

All classification logic is defined and handled via GPT-4o-mini (or any other language model you connect it with).

## 🛠 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/email-cleanup-agent.git
cd email-cleanup-agent
```

### 2. Setup n8n locally 
