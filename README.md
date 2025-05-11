# 🚀 Social Media Auto-Poster with Gemini AI + n8n

Automate content generation and publishing to Facebook and Instagram using AI and workflow automation.

![Workflow Diagram](./screenshots/automation-workflow.png)

## ✨ Features

- **AI-Powered Content**  
  � Generate engaging captions with Gemini AI  
  🖼️ Fetch AI-generated images based on keywords

- **Cross-Platform Posting**  
  📤 Automatic publishing to Facebook & Instagram  
  🔄 Supports both scheduled and manual triggers

- **Easy Automation**  
  ⚡ Powered by n8n workflows  
  🐳 Docker container for easy deployment

## 🛠️ Technologies

| Component          | Technology Used         |
|--------------------|-------------------------|
| Workflow Engine    | n8n                     |
| AI Text Generation | Gemini API              |
| Social Integration | Facebook Graph API      |
| Deployment         | Docker                  |
| Triggers           | Webhook/Cron            |

## ⚙️ Workflow Overview

1. **Trigger**  
   - Scheduled job or manual webhook activation
2. **Content Generation**  
   - Gemini AI creates captions based on prompts  
   - AI generates relevant images
3. **Publishing**  
   - Posts content to Facebook Page  
   - Creates and publishes Instagram media

## 🚀 Getting Started

### Prerequisites
- Docker installed
- API keys for Gemini and Facebook Graph API

### Installation
```bash
git clone https://github.com/yourusername/n8n-social-post-automation.git
cd n8n-social-post-automation
docker-compose up -d
