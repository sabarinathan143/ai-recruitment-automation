# AI Recruitment Automation

An end-to-end recruitment automation project designed to reduce repetitive administrative work while keeping recruiters in control of hiring decisions.

## What the system does

- Receives CVs by email
- Processes PDF and DOCX attachments
- Extracts structured candidate information
- Prevents duplicate candidate records
- Stores candidate data in a structured database/sheet
- Allows recruiters to control progression with statuses such as REVIEW and PROCEED
- Sends automated candidate follow-up emails
- Provides an interview booking link
- Tracks interview bookings
- Updates interview date and time automatically
- Updates a recruiter dashboard
- Includes error handling and duplicate-send protection

## Workflow Overview

Candidate sends CV  
→ CV is processed  
→ Candidate data is extracted  
→ Duplicate check runs  
→ Candidate record is stored  
→ Recruiter reviews candidate  
→ Recruiter marks candidate as PROCEED  
→ Follow-up email is sent  
→ Candidate books interview  
→ Interview details update automatically  
→ Dashboard reflects the latest status

## Architecture

```text
Candidate
   ↓
HR Email Inbox
   ↓
CV Processing
   ↓
AI Data Extraction
   ↓
Duplicate Check
   ↓
Candidate Record
   ↓
Recruiter Review
   ↓
PROCEED
   ↓
Follow-Up Email
   ↓
Interview Booking
   ↓
Calendar Tracking
   ↓
Dashboard Update

## Key Features

- End-to-end workflow automation
- Human-in-the-loop recruitment process
- Duplicate detection
- Automated follow-up communication
- Interview booking tracking
- Structured data handling
- Error handling
- Dashboard reporting

## Project Goal

The goal of this project was to automate repetitive recruitment administration while ensuring that hiring decisions remain with the recruiter.

## What I Learned

Through this project, I gained practical experience in:

- Workflow design
- Business process automation
- API-based integrations
- Webhooks
- JSON data handling
- JavaScript for workflow logic
- SQL and database concepts
- Error handling
- Debugging multi-step automations
- Docker basics
- End-to-end testing

## Status

Working prototype completed and tested end to end.
