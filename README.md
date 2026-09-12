# AI Automation Intern Assignment - Aysha Sulthana

## About
This project was completed as part of my AI Automation internship assignment. It includes a student lead form and automation workflows built using n8n.

## Part A - Lead Capture Form
Created a responsive form using HTML, CSS and JavaScript with:
- Form validation
- 300-character message counter
- Thank-you message
- JSON output in the browser console

## Part B1 - Lead Notification
Created an n8n workflow using a webhook to receive student leads. PG and PhD leads are sent to Slack, while other leads follow a separate branch.

**Workflow:** Webhook → Edit Fields → IF → Slack / No Operation

## Part B2 - Scheduled Data Fetch
Created a scheduled n8n workflow that fetches data from the JSONPlaceholder API and processes it using JavaScript.

**Workflow:** Schedule Trigger → HTTP Request → Code → Edit Fields

## Technologies
HTML, CSS, JavaScript, n8n, Webhooks, Slack, REST API and GitHub.

## Challenge
I initially faced an issue while accessing nested API data. I fixed it using JavaScript optional chaining.

## Repository Structure
```text
ai-intern-assignment-aysha/
├── part-a/
│   └── index.html
├── part-b/
│   ├── workflow-b1-lead-notification.json
│   ├── workflow-b2-scheduled-fetch.json
│   ├── screenshot-b1.png
│   └── screenshot-b2.png
├── part-c/
│   └── index.html
└── README.md
