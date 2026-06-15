

https://github.com/user-attachments/assets/ab61fe6c-71ec-4d23-a149-9edceda54b1b


# AI Gmail Assistant using n8n & Google Gemini

## Overview

AI Gmail Assistant is an intelligent email automation system built using n8n, Google Gemini, and Gmail API. The workflow automatically generates professional emails based on user input and sends them through Gmail, reducing manual effort and improving communication efficiency.

## Features

* AI-powered email generation using Google Gemini
* Automated Gmail integration
* Dynamic email content creation
* Registration confirmation emails
* Event reminder emails
* Welcome emails
* Interview invitation emails
* Internship selection notifications
* Professional email formatting
* Fallback sample data generation when fields are missing

## Tech Stack

* n8n (Workflow Automation)
* Google Gemini API
* Gmail API
* JSON
* Web Forms

## Workflow Architecture

1. User submits data through a form.
2. n8n captures the submitted information.
3. Data is sent to Google Gemini.
4. Gemini generates a professional email.
5. n8n receives the generated content.
6. Gmail node sends the email automatically.
7. Delivery status is logged for monitoring.

## Project Flow

User Form → n8n Trigger → Gemini AI → Email Generation → Gmail API → Recipient Inbox

## Sample Use Cases

### Registration Confirmation

Automatically confirms user registrations for events and workshops.

### Event Reminders

Sends reminder emails before scheduled events.

### Interview Invitations

Generates personalized interview invitation emails.

### Internship Notifications

Notifies applicants regarding internship selections.

### Welcome Emails

Sends onboarding and welcome messages to new users.

## Key Benefits

* Saves time
* Reduces manual work
* Improves email quality
* Supports scalable communication
* Provides personalized responses
* Easy to customize

## Future Enhancements

* Email categorization
* AI email summarization
* Multi-language support
* Attachment handling
* Sentiment analysis
* Email scheduling
* CRM integration

## Installation

1. Install n8n.
2. Configure Google Gemini API credentials.
3. Configure Gmail OAuth credentials.
4. Import the workflow into n8n.
5. Update API keys and email settings.
6. Execute the workflow.

## Author

Neela Bhavyasri

## License

This project is developed for educational and automation purposes.
