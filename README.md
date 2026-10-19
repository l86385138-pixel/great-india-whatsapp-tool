# Great India Technology — WhatsApp Message Desk

Starter website for loading Excel/CSV contacts and opening WhatsApp chats one at a time.

## Features
- Reads XLSX, XLS and CSV in the browser using SheetJS CDN.
- Lets you map phone and name columns.
- Supports the {name} message placeholder.
- Opens one WhatsApp chat at a time with a prefilled message.
- Operator reviews the message and presses Send in WhatsApp.
- Basic local progress list; “complete” is manually marked and does not confirm delivery.

## Run
Open index.html in a modern browser with internet access. Upload a spreadsheet with a header row, check the phone column, compose a message, confirm you have permission to contact the recipients, then open chats one by one.

## Notes
- This is a starter prototype, not a production authentication system.
- Contact data is processed in the browser by this demo and is not uploaded to a Great India backend.
- SheetJS is loaded from a CDN, so internet access is required.
- Keep phone numbers formatted as text in Excel to preserve leading digits.
- Use only for recipients who have agreed to receive your messages and comply with WhatsApp's terms and rate limits.
