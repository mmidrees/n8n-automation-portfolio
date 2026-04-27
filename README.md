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

## Project 2 — Freelance Lead Generation Bot

Automatically fetches remote job listings every morning at 8am, filters for AI and automation roles, and sends matching leads directly to Telegram.

**Tools used:** n8n, We Work Remotely RSS, Telegram
**Trigger:** Daily at 8am
**Filter keywords:** automation, AI, n8n, workflow, zapier
**Output:** Telegram message with job title, link and date



