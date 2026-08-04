![AI Sales Agent Workflow](workflow.png)
# AI Sales Agent
## Project Overview

This workflow automates the first stage of the sales outreach process while maintaining human oversight before contacting potential customers.

When a new lead submits their information through a form, the workflow stores the lead in Google Sheets and uses Google Gemini to generate a personalized sales email based on the customer's details.

Instead of sending the email immediately, the generated draft is routed to a human reviewer for approval. If the response is approved, the workflow automatically sends the email through Gmail. If it is rejected, the workflow sends the request back to the AI agent to generate an improved version before continuing.

This approach combines AI automation with human validation to improve efficiency while maintaining communication quality.

## Technologies

- n8n
- Google Gemini
- Google Sheets
- Gmail
- AI Agent
- Human in the Loop

## Key Features

- Automated lead processing
- AI-generated personalized emails
- Human approval before sending
- Automatic email delivery
- Lead management with Google Sheets
