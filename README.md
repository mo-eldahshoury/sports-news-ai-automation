# ⚽ Automated Sports News Summarizer (n8n & Gemini AI)

An automated workflow built with **n8n** that fetches sports news via RSS feeds, processes and summarizes the content using **Google Gemini LLM**, and sends formatted digests directly to Telegram.

## 🚀 Features
- **Scheduled Trigger:** Automatically runs at set intervals (e.g., daily).
- **RSS Parsing:** Fetches latest articles dynamically.
- **AI-Powered Summarization:** Uses Google Gemini to generate concise summaries.
- **Instant Messaging:** Delivers formatted alerts directly to Telegram channels/bots.

## 🛠️ Tech Stack
- **n8n** (Automation Engine)
- **Google Gemini API** (LLM Integration)
- **Telegram Bot API**
- **RSS & JSON Data Formatting**

## 📦 How to Import
1. Download the `sports-news-workflow.json` file from this repository.
2. Open your n8n instance.
3. Click on **Workflows** -> **Import from File** and select the downloaded JSON file.
4. Configure your Telegram Bot Credentials and Google Gemini API Key.
5. Activate the workflow!
