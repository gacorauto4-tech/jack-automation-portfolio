# Jack — Automation Portfolio (Selected)

No-code / low-code automation builder using n8n. I connect WhatsApp, Telegram,
Google Sheets, and AI (Groq, Gemini, OpenAI, Claude) into automated workflows that
run real business processes. Self-taught.

---

## Purpose of this portfolio
This portfolio shows real automation workflows I built: turning manual processes
(report logging, messaging, finance recap) into self-running workflows that operate
without daily manual intervention.

---

## Selected projects

### 1. LAPBULK3 — Multi-location HSE Reporting System
**Flow:** WhatsApp group → Fonnte webhook → n8n → AI parsing (Gemini) → Google Sheets.
5 locations across Sumatra, with auto-confirmation replies. Routing: #LOG #JSA #KEGIATAN #SAFETYTALK.

- **Function:** Centralizes field K3 (workplace safety) reports from 5 sites into one sheet.
- **Goal:** Capture safety reports without manual forms.
- **Benefit:** Reports land automatically in a single sheet, monitorable from anywhere.
- **Problem solved:** Lost reports, scattered data, slow input.
- **Business gain:** Easier K3 audit, lower accident risk because findings are recorded fast.
- Status: built & running

### 2. Daily Facility Management Reminder → WhatsApp Group
**Flow:** Daily K3 message + news + infographic, auto-sent 1x/day via Fonnte.

- **Function:** Sends a daily workplace-safety reminder to a WhatsApp group.
- **Goal:** Build a daily safety culture via automated reminder.
- **Benefit:** Staff get a daily educational message with no manual admin sending.
- **Problem solved:** Forgotten / inconsistent reminders.
- **Business gain:** Higher K3 awareness, admin time saved.
- Status: active & running

### 3. COG — Daily Report Intake via Telegram
**Flow:** Daily reports received via Telegram → stored to Google Sheets.

- **Function:** Collects team daily reports from one chat channel.
- **Goal:** Gather daily reports without manual email/WA recap.
- **Benefit:** Reports go straight to a sheet row, no manual consolidation.
- **Problem solved:** Reports lost in chat, hard to pull later.
- **Business gain:** Management gets an instant daily summary.
- Status: built & tested

### 4. Cash Flow Daily Dashboard / CASHFLOW V5
**Flow:** Daily finance dashboard from Google Sheets: recap, summary, budget alerts.

- **Function:** Shows the daily cash position from a finance sheet.
- **Goal:** Let the owner see cash position daily without manual books.
- **Benefit:** Auto recap & budget alerts, low input error.
- **Problem solved:** Slow and typo-prone finance recap.
- **Business gain:** Faster and more accurate finance decisions.
- Status: built & tested (not yet in production)

---

## Tools
n8n · WhatsApp (Fonnte) · Telegram · Google Sheets · Groq · Gemini · OpenAI · Claude · OCR · JavaScript Code
