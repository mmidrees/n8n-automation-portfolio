# n8n Automation Portfolio

A collection of automation workflows built with n8n, Claude AI API, Pexels API and Telegram Bot API.

---

## Project 1 — AI Content Pipeline

**What it does:**
Automatically generates 3 daily TikTok posts using Claude AI, fetches relevant images from Pexels, creates a styled cover image using htmlcsstoimage and delivers everything to Telegram every morning at 9am.

**Tech stack:**
- n8n — workflow automation
- Claude API (Anthropic) — AI content generation
- Pexels API — image fetching
- htmlcsstoimage API — image text overlay
- Telegram Bot API — content delivery
- Railway — cloud hosting

**Features:**
- Topic rotation system using n8n static data
- Dynamic Pexels image search based on AI generated search terms
- Styled cover image with Bebas Neue font and gold text overlay
- Fully automated — zero manual effort required

---

## Project 2 — Lead Generation Bot

**What it does:**
Fetches fresh remote job listings every morning at 8am, parses the RSS feed, filters relevant results and delivers a formatted list of opportunities directly to Telegram.

**Tech stack:**
- n8n — workflow automation
- HTTP Request node — RSS feed fetching
- XML node — RSS parsing
- Telegram Bot API — job delivery

**Features:**
- Scheduled daily delivery at 8am
- Parses and cleans RSS data
- Formatted Telegram message with job titles, categories and links

---

## Setup Instructions

1. Import the JSON workflow file into your n8n instance
2. Replace all placeholder values:
   - YOUR_CLAUDE_API_KEY — get from console.anthropic.com
   - YOUR_PEXELS_API_KEY — get from pexels.com/api
   - YOUR_TELEGRAM_CHAT_ID — get from @userinfobot on Telegram
3. Add your Telegram bot token as a credential in n8n
4. Activate the workflow

---

## Contact

Open to automation projects and freelance builds.
Connect on LinkedIn: linkedin.com/in/enoch-tshimbombo-8b03753b8
