# Architecture — Vantix

## Overview
Vantix is a Zero-Cost AI automation system built on n8n + Gemini 1.5 Flash.

## Stack
- **Automation**: n8n (cloud)
- **AI Model**: Google Gemini 1.5 Flash (Free Tier)
- **Storage**: TBD (Airtable / Google Sheets)
- **Notifications**: Slack / Email

## Flow Diagram
[Trigger] → [HTTP Request: Gemini API] → [Process Response] → [Output]
