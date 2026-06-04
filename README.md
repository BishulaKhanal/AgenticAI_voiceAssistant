# AgenticAI_voiceAssistant
AI voice enrollment advisor built with ElevenLabs Conversational AI and Make — books demo class spots directly into Google Sheets.

# Oxford Ava — AI Voice Enrollment Advisor
> A fully automated voice AI assistant that handles inbound enrollment 
> inquiries, books free demo class spots, and logs everything to Google 
> Sheets in real time — no human intervention needed.

## 🔴 Live Demo
**[Talk to Ava →](https://agentic-ai-voice-assistant.vercel.app/)**
**[View Live Google Sheets Backend →](https://docs.google.com/spreadsheets/d/1T48ZseStBAiHrSbDVvqN_x62ov0guUenWVzrdOSce1Y/edit?usp=sharing)**
> Every booking Ava confirms shows up here in real time.

## How It Works
1. Caller visits the landing page and starts a voice conversation with **Ava**
2. Ava collects **name, phone number, preferred date, and program interest**
3. A **Make webhook** fires and logs the booking into Google Sheets instantly
4. Caller receives confirmation — Saturday demo class spot reserved

## Tech Stack
| Layer | Tool |
|---|---|
| Voice AI Agent | ElevenLabs Conversational AI |
| Automation | Make (formerly Integromat) |
| Data Storage | Google Sheets |
| Frontend | HTML / CSS / JS |
| Hosting | Vercel |

## Features
- Natural voice conversation — no forms, no typing
- Collects name, phone number, demo date, and program preference
- Real-time Google Sheets logging via Make webhook
- Free Saturday demo class booking flow
- Call transfer to enrollment team for direct enrollments
- Fully hosted landing page with embedded ElevenLabs widget


## Project Structure
AI_VA/
     └── index.html   

## Built With
- [ElevenLabs Conversational AI](https://elevenlabs.io/conversational-ai)
- [Make](https://make.com)
- [Vercel](https://vercel.com)
