# LinkedIn Job Automation using n8n

## What this does
Automates job discovery, filtering, and outreach using n8n workflows and LLMs.

## Why I built this
Manual job applications are inefficient. This workflow automates repetitive steps while keeping control with the user.
## Design Decisions
- n8n chosen for rapid iteration and visual observability
- LLM used only for personalization to avoid over-automation
- Stateless workflow to keep retries safe

## Limitations
- LinkedIn rate limits
- Manual CAPTCHA handling

## Workflow Overview
- Job search trigger
- Filtering logic
- LLM-based personalization
- Email / LinkedIn outreach

## Tech Stack
- n8n
- LinkedIn / Job boards
- LLM (OpenAI/Gemini)
- Email APIs

## How to run
1. Import the workflow JSON into n8n
2. Configure environment variables
3. Run manually or schedule

## Notes
- No credentials are committed
- This is for educational purposes
