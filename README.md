
# n8n AI Agent for Gmail – Unread Email Summariser

## Assignment
Week 4 – Day 1 | Social Eagle – GenAI Program

## Project Overview
An AI-powered email automation workflow built using n8n.
It fetches the latest five unread Gmail messages, generates
individual email summaries using an OpenAI Chat Model, and
delivers all five summaries in a single email.

## Tools and Technologies
- n8n (Self-hosted on Hostinger VPS)
- Gmail API
- Google OAuth 2.0
- OpenAI Chat Model
- AI Agent
- Aggregate Node

## Workflow Architecture

Manual Trigger → Gmail (Get Many) → AI Agent →
Aggregate → Gmail (Send)

## Key Features
- Fetches five unread Gmail messages.
- Generates one-line summaries of up to 20 words.
- Combines five summaries into a single email.
- Omits OTP codes and passwords from generated summaries.
- Uses secure n8n credential management.
- Requires no standalone programming file.

## How to Run
1. Import the workflow JSON file into n8n.
2. Configure your Gmail OAuth2 credential.
3. Configure your OpenAI API credential.
4. Enter your email address in the Gmail Send node.
5. Click Execute Workflow.
6. Check your Gmail inbox for the summary email.

## Expected Output
Subject: Your 5 unread emails

A single email containing five AI-generated summaries.

## Learning Outcomes
- Gmail API integration with n8n.
- AI Agent and Chat Model configuration.
- Dynamic expressions and prompt engineering.
- Data aggregation and email automation.
- Secure credential management.

## Project Status
Successfully implemented and tested.

## Author
Rajesh B
