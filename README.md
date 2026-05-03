# Automation Projects Repository

A collection of workflow automation projects built using **n8n**, **AI integrations**, and **Telegram automation**.

This repository contains practical automation use cases focused on productivity, business workflows, and AI-powered processing.

---

# Projects Included

## 1. AI Email Classification & Labeling

An automation workflow that classifies incoming emails using **Gemini AI** and automatically assigns labels based on content.

### Features

* Reads incoming emails automatically
* Uses Gemini AI for intelligent email analysis
* Detects email category and intent
* Automatically applies labels such as:

  * Work
  * Personal
  * Finance
  * Support
  * Spam
  * Important
* Reduces manual inbox management

### Workflow

```text
Email Trigger
     ↓
Fetch Email Content
     ↓
Gemini AI Classification
     ↓
Determine Label
     ↓
Apply Email Label
```

### Tech Stack

* n8n
* Gemini AI API
* Gmail / Email Integration
* HTTP Request Nodes

---

## 2. Cab Invoice Generator

A Telegram-based cab invoice generation automation that creates stylish PDF invoices from ride details.

### Features

* Telegram bot interaction
* Accepts ride details from user
* Generates professional invoice HTML
* Converts HTML to PDF
* Sends invoice PDF directly back to Telegram
* Dynamic invoice variables

### Supported Fields

* Customer Name
* Pickup Location
* Drop Location
* Cost
* Invoice Number
* Date

### Workflow

```text
Telegram Trigger
     ↓
Parse User Input
     ↓
Generate Invoice HTML
     ↓
Convert HTML to PDF
     ↓
Download PDF
     ↓
Send PDF via Telegram
```

### Tech Stack

* n8n
* Telegram Bot API
* PDFShift API
* HTML + CSS Invoice Template

---

# Repository Structure

```text
Ai-Automation/
│
├── N8n/
│   ├── Cab Invoice.json
│
│   
│
├── SimpleLearn/
│   ├── Email Labeling Agent.json
│   
│   
│
└── README.md
```


# Future Enhancements

* Multi-language support
* Database logging
* Dashboard analytics
* Invoice history tracking
* Advanced AI categorization

---

#
