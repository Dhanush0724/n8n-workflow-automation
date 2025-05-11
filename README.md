# 🚀 Social Media Auto-Poster with Gemini AI + n8n

This project automates content generation and publishing to **Facebook** and **Instagram** using **n8n** (a powerful open-source workflow automation tool), the **Gemini API** (for AI-generated text), and the **Facebook Graph API**.

## 📸 What It Does

- ⏱️ Automatically triggers by schedule or manually via webhook
- 🧠 Uses Gemini AI to generate engaging captions or post content
- 🖼️ Fetches an AI-generated image based on a keyword
- 📤 Posts content to Facebook and Instagram automatically
- ✅ All automated using n8n and Docker

## 🔧 Technologies Used

- **n8n** (local instance via Docker)
- **Gemini API** (text generation)
- **Facebook Graph API** (Facebook & Instagram posting)
- **Docker**
- **Webhook/Cron triggers**

## ⚙️ Workflow Overview

1. Triggered by **button** or **scheduled job**
2. Sends a prompt to **Gemini** to generate content
3. Parses the response and stores the caption
4. Generates an AI image using keyword
5. Sends content to **Facebook Page**
6. Creates an **Instagram media object** with image URL and caption
7. Publishes the Instagram post

![Workflow Diagram](./screenshots/automation-workflow.png)

> *Screenshot of the full n8n workflow in action.*

## 🔥 Why This Project?

Manually managing content for multiple social platforms is time-consuming. This project automates the process using smart content generation + auto-posting — saving time and enabling consistent publishing.

---

## 🛠️ Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/n8n-social-post-automation.git
cd n8n-social-post-automation
