# AI Automation Intern Assignment - Aysha Sulthana

**Email:** ayshasulthana9037@gmail.com  
**Date:** 12 September 2026

## About
This project was completed as part of my AI Automation internship assignment. It includes a student lead capture form and automation workflows built using n8n.

## Part A - Lead Capture Form
Created a responsive form using HTML, CSS and JavaScript with validation, a 300-character counter, thank-you message and JSON output.

**Run/Test:** Open `part-a/index.html` in a browser and submit the form.

## Part B1 - Lead Notification
Created an n8n workflow that receives student leads through a webhook. PG and PhD leads are sent to Slack, while other leads follow a separate branch.

**Workflow:** Webhook → Edit Fields → IF → Slack / No Operation

## Part B2 - Scheduled Data Fetch
Created a scheduled n8n workflow that fetches and processes data from the JSONPlaceholder API.

**Workflow:** Schedule Trigger → HTTP Request → Code → Edit Fields

**API:** JSONPlaceholder was used as a simple public API for testing scheduled data fetching.

## Part C - Form Integration
Connected the Part A form to the B1 n8n webhook using JavaScript `fetch()`.

**Demo:** [Part C Screen Recording](./part-c/n8n-and-form-integrated .mp4)

## Technologies
HTML, CSS, JavaScript, n8n, Webhooks, Slack, REST API and GitHub.

## Credentials
No credentials or secret keys are included in the repository. Any required n8n credentials should be configured separately.

## Challenges
I initially faced an issue while accessing nested API data. I fixed it using JavaScript optional chaining. I also learned how to connect n8n nodes and route data using conditions.
