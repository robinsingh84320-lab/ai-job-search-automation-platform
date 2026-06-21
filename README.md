# AI-Powered Job Search & CV Automation Platform

## Overview

An end-to-end automation platform built using n8n to streamline job discovery, ATS analysis, CV optimization, cover letter generation, and application tracking.

## Problem Statement

Job applications are repetitive and time-consuming. This project automates key stages of the recruitment process to improve efficiency and reduce manual effort.

## Key Features

- Automated job discovery
- ATS keyword analysis
- AI-powered CV tailoring
- Automated cover letter generation
- Application tracking
- Workflow orchestration
- API integrations

## Architecture

Job Search APIs
↓
Job Processing
↓
ATS Analysis
↓
CV Tailoring
↓
Cover Letter Generation
↓
Application Tracking

## Technologies

- n8n
- REST APIs
- JSON
- Google Sheets
- AI Services
- Workflow Automation
## Workflow Setup

### Prerequisites

- n8n
- Google Sheets account
- Google Drive account
- OpenRouter/OpenAI API access
- Adzuna API account

### Setup Steps

1. Import the workflow JSON into n8n.
2. Create and configure the required credentials:
   - Google Sheets
   - Google Drive
   - OpenRouter/OpenAI
   - Adzuna API
3. Replace placeholder values:
   - YOUR_APP_ID
   - YOUR_APP_KEY
   - YOUR_APIFY_TOKEN
   - YOUR_GOOGLE_DRIVE_FOLDER_ID
4. Configure the target Google Sheets document.
5. Run the workflow manually or enable scheduled execution.

### Workflow Process

1. Search jobs using external job APIs.
2. Filter and process job listings.
3. Perform ATS keyword analysis.
4. Generate tailored CV content.
5. Generate cover letters.
6. Save results to Google Sheets.
7. Track application status automatically.


## Skills Demonstrated

- Workflow Automation
- Business Process Automation
- API Integration
- Data Integration
- Process Optimization
- AI Automation
- Solution Design
- Technical Documentation

## Outcome

Designed and implemented an AI-powered recruitment automation workflow that automates job discovery, ATS scoring, CV tailoring, cover letter generation, and application tracking through integrated automation pipelines.


## Business Value

This solution automates repetitive recruitment activities, reduces manual effort, improves ATS alignment, and provides centralized application tracking through workflow automation and AI-assisted document generation.


## Future Enhancements

- LinkedIn integration
- Automated application submission
- Interview tracking dashboard
- Power BI reporting
- Microsoft Graph integration
