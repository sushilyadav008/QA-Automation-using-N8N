# QA-Automation-using-N8N
Project Overview

This project demonstrates how QA and recruitment workflows can be automated using n8n to reduce repetitive manual work and improve process efficiency. The automation integrates tools such as Google Sheets, Gmail, Telegram, and AI APIs to streamline activities like resume processing, bug tracking, automated reporting, and developer notifications.

The goal of this project was to convert manual QA and HR tasks into automated workflows, ensuring faster communication, better tracking, and improved process reliability.

Problem Statement

In many teams, QA and HR processes involve several repetitive manual tasks such as:

Manually tracking bugs in spreadsheets

Informing developers about new issues

Following up on unresolved defects

Collecting and reviewing resumes

Updating candidate status

Sending interview reminders and status updates

These tasks require constant manual effort, communication delays, and risk of missing updates.

To solve this, I designed automated workflows using n8n that handle these repetitive activities.

Solution

Using n8n workflow automation, I created pipelines that automate multiple QA and recruitment processes.

The workflows perform the following tasks:

1. Bug Tracking & QA Monitoring

QA testers log bugs and testing updates in Google Sheets.

n8n automatically monitors the sheet for new entries.

When a new bug is logged:

A notification is automatically sent to developers or QA leads via Gmail or Telegram.

The workflow updates the bug status and maintains tracking records.

If a bug remains unresolved, automatic reminders are sent to developers.

This ensures transparent bug tracking and faster issue resolution.

2. Automated Test Workflow Support

The automation supports QA processes by handling:

Test data preparation

Environment reset notifications

Automated reporting of testing results

Team alerts when issues are detected

These workflows help reduce manual coordination between testers and developers.

3. Resume Screening & Recruitment Automation

The project also automates parts of the HR recruitment process.

Workflow steps include:

Resume is uploaded or received.

The system extracts candidate details.

Candidate profiles are evaluated against job requirements.

Data is stored in Google Sheets for tracking.

Automated emails and notifications are sent to candidates or HR teams.

This reduces the manual work involved in resume filtering and candidate management.

How Manual Processes Were Automated

Before automation, tasks were handled manually:

Manual Task	Automated Workflow
Bug entry tracking	Google Sheets monitoring using n8n
Developer notifications	Automated Gmail/Telegram alerts
Bug follow-ups	Scheduled reminder automation
Test reporting	Automated workflow reports
Resume screening	Automated parsing and evaluation
Candidate communication	Automated email workflows

This automation helped create a seamless workflow between QA, developers, and HR teams.

Tools & Technologies

n8n – Workflow automation platform

Google Sheets – Bug tracking & candidate data storage

Gmail API – Automated email notifications

Telegram Bot API – Real-time alerts

AI APIs – Resume evaluation and candidate analysis

Key Benefits

Reduced manual QA and HR effort

Faster bug reporting and developer notification

Improved tracking and workflow transparency

Automated candidate evaluation and communication

Created a scalable automation pipeline

Learning Outcomes

Through this project, I learned how to:

Design logic-based automation workflows

Integrate APIs with n8n nodes

Automate QA operations and HR processes

Improve communication between QA, developers, and HR teams

Convert manual operational tasks into automated pipelines
