# ai-lead-capture-follow-up
AI-powered lead capture, qualification, routing, and automated follow-up system built with make.com
# AI Lead Capture & Follow-up System

An AI-powered lead management automation built with Make.com. This project captures lead data, uses Google Gemini AI to generate a response, processes structured data with JSON, stores lead information in Google Sheets, and routes leads for email follow-up.

## Workflow

![AI Lead Capture and Follow-up Workflow](./Screenshot%202026-08-31%20115310.png)

## How It Works

1. **Webhook:** Receives incoming lead data.
2. **Google Gemini AI:** Generates an AI response based on the lead information.
3. **JSON:** Parses the structured response.
4. **Google Sheets:** Adds the lead data to a spreadsheet.
5. **Router:** Routes leads into Hot, Warm, and Cold categories according to the scenario's configured filters.
6. **Gmail:** Sends follow-up emails through the corresponding routes.

## Tools & Technologies

- Make.com — workflow automation
- Google Gemini AI — AI-powered response generation
- Webhooks — lead data intake
- JSON — structured data processing
- Google Sheets — lead data storage
- Gmail — automated email follow-ups

## Key Features

- Automated lead capture
- AI-assisted lead processing
- Structured data handling
- Lead routing through separate categories
- Automated email follow-ups

## Project Purpose

This project demonstrates how AI and workflow automation can help organize incoming leads and reduce repetitive manual follow-up tasks.

## Setup

This workflow was built in Make.com. To reuse it, import the provided blueprint into Make.com and configure your own app connections, webhook, Google Sheets, Gmail, and any required settings. Test the scenario before using it.

## Security Note

The blueprint may require your own connections and configuration. Never share API keys, passwords, access tokens, or private lead data.

## Author

Mehreen Ashraf

BSc Artificial Intelligence Student | AI Automation & Workflow Automation
