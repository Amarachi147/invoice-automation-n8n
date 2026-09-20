# Invoice Automation (n8n)

A recurring invoice automation that generates professional PDF invoices and delivers them to clients automatically — no manual invoicing each month.

## How it works
- **Trigger:** scheduled (runs monthly, not dependent on manual action)
- **PDF generation:** APITemplate.io turns invoice data into a polished PDF
- **Delivery:** finished invoice sent directly to the client via WhatsApp

## Why this matters for clients
Manual invoicing is easy to forget or delay. This workflow removes that risk entirely — invoices go out on schedule, every time, with zero manual steps.

## Stack
n8n · APITemplate.io · WhatsApp Cloud API

## Files
- `workflow.json` — exported n8n workflow (any client-specific IDs replaced with placeholders)
