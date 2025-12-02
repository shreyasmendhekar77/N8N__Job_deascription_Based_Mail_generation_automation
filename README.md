# Job_deascription_Based_Mail_generation_automation

ItJob Description–Based Mail Generation Automation (n8n Workflow)

This project is an end-to-end n8n automation workflow designed to generate highly relevant, personalized emails to recruiters based on any Job Description (JD) you provide. Simply send a JD file to your Telegram bot, and the workflow handles everything else.

🚀 How It Works
1. Trigger via Telegram

Upload or forward a JD file to your Telegram bot.

The workflow is instantly triggered.

2. JD Text Extraction

n8n automatically extracts all the text from the JD file (PDF, text, or doc formats).

3. Resume Retrieval from Drive

n8n fetches your latest resume directly from Google Drive (or your connected storage).

4. Smart Email Generation using LLM

Both the JD text and your resume are passed to the LLM.

The system generates a professionally tailored, job-specific email ready to send to the recruiter.

🔄 Feedback Loop for Refinement

If you want changes in the generated email, just reply with suggestions on Telegram.

The workflow refines the mail until you are completely satisfied.

✅ Approval & Finalization

Once the mail is perfect, simply approve it in the Telegram bot.

n8n will:

Send the final email back to you for verification, or

Automatically send it to the recruiter/HR on your behalf.

🎯 Key Features

Fully automated JD → Recruiter Email workflow

Telegram-triggered automation

Automatic JD text extraction

Linked resume fetching from Drive

LLM-powered personalized mail writing

Feedback loop for improvements

One-click approval and sending



