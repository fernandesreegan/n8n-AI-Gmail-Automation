# 📧 Gmail AI Automation Using n8n

An AI-powered email automation workflow using **n8n, Gmail API, and OpenAI** for intelligent email content generation and automated email processing.

## 🚀 Project Overview

This project demonstrates how to integrate Gmail with OpenAI through n8n to generate structured email content and automate email-related tasks.

## ✨ Key Features

- Gmail API integration
- AI-generated email subjects and content
- Structured JSON output
- Dynamic recipient handling
- Automated email workflow execution
- JavaScript-based JSON processing, where required

## 🔄 Workflow Architecture

User Input → OpenAI Model → JSON Processing → Gmail API → Email Delivery

## 🛠️ Tech Stack

- n8n
- Gmail API
- OpenAI API
- JavaScript
- JSON

## 📦 Sample AI Output

```json
{
  "to": "recipient@example.com",
  "subject": "Project Update",
  "body": "Hello, here is the latest project update."
}
```

## ⚙️ Setup Instructions

1. Import the n8n workflow JSON.
2. Configure Gmail OAuth2 credentials.
3. Configure OpenAI API credentials.
4. Set up email input and processing nodes.
5. Test the workflow with a sample email request.
6. Verify the generated email content and delivery.

## 🎯 Learning Outcomes

- Gmail API authentication
- AI-powered email generation
- JSON response handling
- Email workflow automation
- Integration of LLMs with external services

## 🔐 Security

Do not expose Gmail OAuth tokens, client secrets, or API credentials in the repository.
