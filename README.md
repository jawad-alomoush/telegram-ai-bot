# Telegram AI Bot

A Telegram bot that answers any question using 
Groq AI (Llama 3.3) via n8n automation.

## What It Does
- Receives any message sent to the Telegram bot
- Sends message to Groq AI for processing
- AI generates a smart reply
- Reply sent back to user on Telegram
- Supports both Arabic and English

## Tools Used
- n8n automation
- Telegram Bot API
- Groq AI (llama-3.3-70b-versatile)
- Basic LLM Chain node

## How It Works
1. User sends message to Telegram bot
2. Telegram Trigger receives the message
3. Groq AI processes and generates reply
4. Reply sent back to user instantly

## Workflow Structure
Telegram Trigger → Basic LLM Chain → Telegram Send

## Screenshot
<img width="1086" height="420" alt="Screenshot 2026-04-07 065257" src="https://github.com/user-attachments/assets/41f409bd-0d31-4863-8749-b2da2f1f71f7" />
