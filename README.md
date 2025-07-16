

<div align="center">
  <img src="https://n8n.io/images/n8n-logo.png" alt="n8n logo" width="120"/>
  <h1>🚀 Zero Recruitment Anxiety: Automated Job Alerts via Telegram & n8n 🤖</h1>
  <img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" alt="Telegram icon" width="38"/>
  <br/>
  <img src="https://github.com/pandeypooja21/N8n-workflow/blob/main/Screenshot%20%2878%29.png?raw=true" alt="n8n Workflow Screenshot" width="720"/>
</div>


🦄 Why?
Do you ever wish your future just DMed you with internship offers instead of you refreshing job boards?
Well, now it does.

No code. No spam. No recruiter voicemails. Just your phone buzzing with fresh openings wherever you chill on Telegram.

Built this because, let’s face it, if no one else is going to shoot their shot for me—I will (using bots).

🎯 Features
Auto-fetches 🔎 SDE, Frontend/Backend/Fullstack Intern jobs every day

Sends them directly to your Telegram DMs via your very own bot 🤖

Built with n8n’s visual workflow automation (drag, drop, done!)

Customizable for your job title, frequency, and delivery time

Zero coding skills needed. Just vibes. ✨

🧩 Workflow Overview
text
graph TD
  A[Schedule Trigger ⏰] --> B{HTTP Request 🎯}
  B --> C[Format/Edit message 📝]
  C --> D[HTTP POST to Telegram 🤖]
Schedule Trigger:
Tells my bot when to work (because I refuse to).

HTTP Request:
Grabs internships using the Remotive API.

Edit Fields:
Rewrites boring data into ✨ motivational DMs ✨ – because job hunting should at least make you smile.

HTTP Request (POST to Telegram):
Pops those jobs right into my Telegram, where I can ignore them just like I ignore my alarm.

📸 Screenshot
<img src="https://pplx-res.cloudinary.com/image/private/user_uploads/56295773/7484e149-a7da-4906-8cfb-4eaf8a1adc95/Screenshot-78.jpg" alt="n8n Workflow Screenshot" width="800"/>
🛠️ How It Works
Trigger: Every morning (or whenever), the workflow starts.

Fetch: Pulls internships from Remotive for your specified search terms (e.g., "sde intern", "frontend intern", etc.).

Format: Gathers the job titles, companies, and links into a neat, encouraging message.

Deliver: Sends that daily hope injection straight to my Telegram via a custom bot.

✨ Customization
Change Job Titles:
Edit the search parameter to send yourself any kind of job (from "AI Overlord" to "Coffee Intern").

Change Frequency:
Want an hourly boost (or self-roast)? Change the cron schedule.

Add Recipients:
DM your friends (or your enemies) with the juiciest offers.

⚡ How to Run This Yourself
Clone this workflow on your n8n instance (cloud or self-hosted).

Create a Telegram bot with @BotFather and get the API token.

Get your Telegram chat ID (ask @userinfobot).

Paste the bot token and chat ID

Customize your search queries and run!

🎀 Sample n8n Workflow Steps
text
[Schedule Trigger] --> [HTTP GET: remotive.com/api/remote-jobs?search=your-query]
        ↓
[Edit Fields - Format message with expressions]
        ↓
[HTTP POST: api.telegram.org/bot<TOKEN>/sendMessage]
✍️ Real-World Output
Every morning I get:

text
🚀 DAILY DREAM JOB DROPS 🚀

1. Frontend Developer Intern @ FutureTech
   https://remotive.com/remote-jobs/software-dev/12345

2. SDE Intern @ StartupNinjas
   https://remotive.com/remote-jobs/software-dev/67890

3. Backend Intern @ CloudMasters
   https://remotive.com/remote-jobs/software-dev/54321
💫 Why bother recruiters when you can automate your own career anxiety?
Pro tip:
Add a dad joke to every message. Makes rejection less painful.

Hire me, or my bot.

**#n8n #TelegramBots #Automation #JobSearch #NoCode #InternLife #NotAnotherCoverLetter #cruiterWho?


