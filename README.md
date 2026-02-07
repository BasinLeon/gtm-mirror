# 🦅 BASIN::GTM-STACK
## The Plug-and-Play Revenue Acceleration Engine

This is a lightweight, Python-driven GTM engine designed to turn inbound noise or company names into high-intent signals and suggested outreach copy.

### 🚀 Quick Start (Deployment)

1. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "initial gtm stack"
   git remote add origin https://github.com/YOUR_USER/gtm-stack.git
   git push -u origin main
   ```

2. **Connect to Vercel:**
   - Import the repo.
   - Vercel will detect the `api/` folder and serve the FastAPI backend as Serverless Functions.

3. **Set Environment Variables:**
   - `SLACK_WEBHOOK_URL`: Your Slack channel webhook.
   - `TELEGRAM_BOT_TOKEN`: (Optional) Your bot token.
   - `TELEGRAM_CHAT_ID`: (Optional) Your chat ID.

### 🛠 How it Works

1. **Trigger:** Send a POST request to `/api/signal` with a `company_name`.
2. **Scout:** The engine researches (or mocks for 0.1) the company for "Trigger Events" (Funding, Hiring, Product Launches).
3. **Refine:** It generates a personalized "Hook" using Leon's GTM methodology.
4. **Notify:** Sends the formatted Signal Card to Slack or Telegram instantly.

### 💰 Monetization Model

- **Tier 1 ($299):** Access to this repository + Setup Guide.
- **Tier 2 ($799):** Pre-configured environment + 1hr Setup Call.
- **Tier 3 ($2,500+):** Custom Connectors (Salesforce/HubSpot) + Custom Signal Logic.

---
*Built by Leon Basin | GTM Engineer*
