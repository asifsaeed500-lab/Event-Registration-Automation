# Event-Registration-Automation
I’ve built a complete Event Registration Confirmation system that captures data from a Google Form, generates a unique Registration ID and QR code for each participant, stores all records in Google Sheets and Drive, and sends a confirmation email. This makes check-in fast and builds attendance data for future marketing.
📌 Fully Automated Event Registration System (Google Form → QR Code → Email)

I have successfully built a complete automation workflow for Any Event Registration Confirmation System using Make.com.
This system eliminates manual work, reduces errors, and gives a smooth experience to participants.

🎯 Purpose of the Automation

To automatically handle the entire registration process:

Collect entries

Generate unique Registration IDs

Create QR codes

Save everything in Google Sheets

Send confirmation emails

Store QR codes in Drive

Keep all data organized for check-in and reporting

No manual copy-paste, no mistakes — 100% automated.

🧩 Modules Used & Their Benefits
1️⃣ Google Form – “Watch Responses”

📌 Purpose: Detects every new registration instantly.
📌 Benefit: No need to manually check the form — every submission triggers the workflow automatically.

2️⃣ Google Sheets – “Add a Row”

📌 Purpose: Stores each participant’s details in a structured sheet.
📌 Benefit:

Builds a master database

Easy filtering, reporting, and exporting

Required for dashboard or check-in system later

3️⃣ Set Variable – “Generate Registration ID”

📌 Purpose: Creates a unique ID for every participant using a static prefix + row number.

Example:
Learn AI-ML Road Show REG-2025-7

📌 Benefit:

Professional tracking

One unique ID per attendee

Used for QR code & check-in

4️⃣ HTTP Module – “Generate QR Code”

📌 Purpose: Automatically creates a QR code based on the Registration ID.
📌 Benefit:

No manual QR creation

QR used for event entry scanning

Secure & fast check-in process

5️⃣ Google Drive – “Upload File”

📌 Purpose: Saves the QR code image in a dedicated Drive folder.
📌 Benefit:

Central place to store all QR codes

Provides a shareable link for emails

Helps in future attendee verification

6️⃣ Google Sheets – “Update a Row”

📌 Purpose: Adds back the Registration ID and QR Code URL into the same row.
📌 Benefit:

Complete and ready-to-use dataset

Sheet becomes a mini-CRM with all details

Perfect for dashboards/attendance systems

7️⃣ Gmail Module – “Send Email Confirmation”

📌 Purpose: Sends personalized confirmation email to each participant with:

Event details

Registration ID

QR Code link

📌 Benefit:

Instantly informs participants

Looks professional

Reduces inquiries and confusion

🚀 Final Output (What This Automation Achieves)

✔ Automatically registers participants
✔ Builds a clean database
✔ Generates unique IDs
✔ Creates QR codes
✔ Stores files professionally
✔ Sends confirmation instantly
✔ Prepares for check-in, dashboard, and reporting

This system can be used for:

Expos

Workshops

Webinars

Training Programs

Conferences

School/College Events

Community Activities
