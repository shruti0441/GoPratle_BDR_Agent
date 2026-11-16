# GoPratle – BDR Lead Enrichment & Outreach Agent

## Project Overview
An AI-powered BDR automation workflow built using n8n to identify and enrich potential business leads for GoPratle.

GoPratle connects event hosts with vetted event planners, DJs, and professional event crews.

## Objective
Automate the process of researching companies, identifying relevant decision-makers, generating personalized outreach messages, and maintaining a structured lead database.

## Tech Stack
- n8n – Workflow automation
- Tavily API – Web search and lead research
- Groq – AI-powered lead analysis and enrichment
- Google Sheets – Lead database and tracking
- Gmail – Outreach draft generation

## Workflow
1. Capture company name and city through Google Sheets.
2. Search for relevant decision-makers using Tavily.
3. Analyze search results using an AI Agent.
4. Extract lead name, designation, LinkedIn URL, and publicly available email.
5. Generate a personalized outreach pitch.
6. Save enriched lead details in Google Sheets.
7. Create an outreach email draft using Gmail.
8. Track outreach status and follow-up date.

## Key Features
- Automated lead research
- AI-based decision-maker identification
- Personalized outreach generation
- Google Sheets integration
- Outreach draft creation
- Follow-up tracking

## Setup Instructions
1. Import the workflow JSON into n8n.
2. Configure Google Sheets OAuth credentials.
3. Add your Tavily API key.
4. Configure Groq Chat Model credentials.
5. Configure Gmail credentials.
6. Update the Google Sheet document and sheet name.
7. Execute the workflow.

## Security
API keys and credentials are not included in this repository. Configure your own credentials in n8n.

## Deliverables
- n8n workflow JSON
- AI Agent configuration
- End-to-end demonstration recording

## Author
Shruti Adsul
