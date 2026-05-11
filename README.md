# good-morning-automation
Daily 6 AM email automation with weather, quote &amp; calendar using Retool
# 🌅 Good Morning Email Automation

An automated daily email sent every morning at 6:00 AM IST 
built using Retool Workflows.

## 📌 Features
- 🌤️ Live weather for Bengaluru (OpenWeatherMap API)
- 💬 Daily motivational quote (ZenQuotes API)
- 📅 Google Calendar events for the day
- ⏰ Fully automated — runs daily at 6 AM IST
- 📧 Delivered via Gmail SMTP

## 🛠️ Tools & Technologies
- Retool Workflows
- OpenWeatherMap API
- ZenQuotes API
- Google Calendar API
- Gmail SMTP

## 🔧 How It Works
1. Schedule trigger fires at 6:00 AM IST every day
2. Fetches live Bengaluru weather from OpenWeatherMap
3. Fetches a random motivational quote from ZenQuotes
4. Fetches today's events from Google Calendar
5. Builds email body combining all data
6. Sends email via Gmail SMTP

## 📸 Screenshots

### Workflow Canvas
![Workflow](workflow.png)

### Email Received
![Email](email.png)


## 🚀 How to Replicate
1. Create a Retool account
2. Set up resources: SMTP, Google Calendar, REST APIs
3. Create a Workflow with Schedule trigger (6 AM IST)
4. Add blocks: getWeather, getQuote, getCalendar, buildEmail, sendEmail
5. Publish the workflow
