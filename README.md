📧 Automated Email Outreach Workflow (n8n + Google Sheets)

Scale your cold email campaigns with automation, personalization, and tracking — all managed from Google Sheets, powered by n8n
.

🚨 Problem

Traditional outreach is:

⏳ Time-consuming → Manual copy-paste for every lead

😓 Error-prone → Risk of duplicates & wrong emails

📉 Unscalable → Hard to manage hundreds of contacts

❌ No tracking → No clear log of who was emailed and when

✅ Our Solution

This workflow turns outreach into a hands-free automated system:

📂 Fetch Leads – Pulls contacts directly from Google Sheets

🚦 Filter – Skips leads already contacted (Status = SENT)

🎲 Pick Template – Randomly chooses an email template from Sheet2

✍️ Personalize – Replaces [Name] with each lead’s name

📤 Send Email – Delivers via your domain SMTP (e.g. info@yourdomain.com)

📝 Log Status – Updates SENT/Failed + timestamp in Google Sheets

⏱ Delay & Retry – Adds safe gaps between emails to avoid spam filters

🎯 Benefits

✨ Save Time – Outreach that runs while you work on bigger tasks
✨ Higher Replies – Personalization makes emails stand out
✨ Always Tracked – Status & timestamps logged in Sheets automatically
✨ Professional – Uses your domain email for better trust & delivery
✨ Scalable – Safely handle 100s of leads without burning out

📂 Google Sheets Setup

Sheet1 → Leads

Name	Email	Status	Time
John Doe	john@example.com
		
Jane Doe	jane@example.com
	SENT	14:25:00

Sheet2 → Templates

Subject	Body
Grow Your Business 🚀	Hi [Name], I wanted to share…
Quick Question	Hello [Name], I noticed your…
🛠 Requirements

n8n
 (self-hosted or cloud)

Google Sheets API credentials

SMTP credentials (Gmail, Zoho, or custom domain email)

Leads & templates stored in Google Sheets

🚀 Getting Started

Clone this repo

Import the workflow JSON into n8n

Add Google Sheets + SMTP credentials

Update the sender email (info@yourdomain.com)

Run the workflow → Emails are sent & logged automatically 🎉

💡 Best Use Cases

📩 Sales lead generation

👔 Recruiter outreach

🤝 Client follow-ups

📢 Startup launch campaigns

⚡ Plug in your leads, templates, and SMTP — and let automation do the heavy lifting.
