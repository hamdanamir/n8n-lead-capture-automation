# Lead Capture & Notification Automation

A professional lead management automation built with **n8n** that captures website form submissions, validates lead information, stores valid leads in Google Sheets, and sends real-time Gmail notifications.

The workflow is designed to reduce manual lead-management work and provide a structured foundation for business lead processing.

---

## 🚀 Project Overview

Businesses often receive leads through contact forms but still manually:

- Check new submissions
- Copy lead information into spreadsheets
- Verify whether required information is available
- Notify the sales or business team
- Organize lead records

This automation handles these tasks automatically.

### Workflow

```text
Website Form
     ↓
Normalize Lead Data
     ↓
Validate Required Data
     ↓
    ┌───────────────┐
    │               │
  VALID          INVALID
    ↓               ↓
Google Sheets    Error Handling
    ↓
Gmail Notification
