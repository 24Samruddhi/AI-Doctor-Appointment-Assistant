 AI Doctor Appointment Booking Assistant

Overview

AI Doctor Appointment Booking Assistant is an intelligent chatbot built using n8n, Telegram, Google Gemini/Groq/OpenAI, Google Calendar, and Gmail. The assistant automates the appointment booking process by interacting with users through Telegram, checking doctor availability, scheduling appointments in Google Calendar, and sending confirmation emails.
This project demonstrates workflow automation, AI integration, calendar management, and email notifications in a no-code/low-code environment.

 Features

 Book doctor appointments through Telegram
 Check doctor availability using Google Calendar
 Create appointment events automatically
 Send confirmation emails via Gmail
 Maintain conversation context using memory
 AI-powered responses using Gemini, Groq, or OpenAI models
 Real-time appointment scheduling

 Workflow

1. User sends a message in Telegram.
2. Telegram Trigger receives the request.
3. AI Agent processes the user's intent.
4. Memory stores conversation context.
5. Google Calendar Search checks appointment availability.
6. Google Calendar Create Event books the appointment.
7. Gmail sends a confirmation email.
8. Telegram sends a confirmation message back to the user.

Technologies Used

 n8n
 Telegram Bot API
 Google Gemini
 Groq
 OpenAI
 Google Calendar API
 Gmail API

Prerequisites

Before running the project, ensure you have:

 n8n account or self-hosted n8n instance
 Telegram Bot Token
 Google Calendar credentials
 Gmail credentials
 Gemini API Key (optional)
 Groq API Key (optional)
 OpenAI API Key (optional)

Setup Instructions

1. Create Telegram Bot

 Open BotFather on Telegram
 Create a new bot
 Copy the bot token

2. Configure n8n

 Import the workflow
 Add Telegram credentials
 Add Google Calendar credentials
 Add Gmail credentials
 Configure AI model credentials

3. Run the Workflow

 Activate the workflow
 Send a message to the Telegram bot
 Follow the appointment booking process

Example Conversation

User:
"I want to book an appointment"

Bot:
"What doctor's name or specialty would you like to book?"

User:
"Dr. Anjali Sharma, 15 June 2026, 11:00 AM"

Bot:
"Please provide your Full Name, Email Address, Phone Number, and Reason for Visit."

User:
"Samruddhi Raut, [example@gmail.com](mailto:example@gmail.com), 9876543210, General Checkup"

Bot:
"Your appointment has been confirmed. A confirmation email has been sent."

Future Improvements

 Appointment cancellation
 Appointment rescheduling
 Multi-doctor support
 Patient database integration
 SMS notifications
 Voice assistant integration

