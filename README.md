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
2. Start n8n using Docker
bash
Copy
Edit
docker-compose up -d
🔗 Access the editor at: http://localhost:5678

3. Add Your API Keys
Add the following credentials in the HTTP Request nodes (or use n8n’s credentials system):

🔑 Gemini API Key

🔑 Facebook Graph Access Token

📈 Features
🤖 AI-generated captions

🖼️ Dynamic image generation based on keywords

🔁 Full automation with scheduling support

📤 Posting to Facebook and Instagram

✅ Easily extendable to other platforms

✨ Future Improvements
🔁 Auto hashtag generation

📊 Analytics integration (likes, views, etc.)

🤖 Smarter caption + image pairing

🌐 Multi-platform publishing (LinkedIn, Twitter)

📸 Screenshot
(Add a screenshot of your n8n workflow here)

🧠 Why This Project?
Managing content for multiple platforms is time-consuming. This workflow solves it using:

AI-generated content

No-code automation with n8n

Seamless deployment via Docker

Let AI and automation do the boring work while you focus on strategy.

📫 Contact
Feel free to reach out if you're curious or want to collaborate:

Dhanush V
📍 Bangalore | 🎓 AI/ML Engineer
LinkedIn | GitHub

🏷️ Tags
#Automation #n8n #GeminiAPI #SocialMedia #AI #Workflow #Docker
