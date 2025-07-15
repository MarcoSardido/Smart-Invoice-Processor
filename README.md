
# 📥 Smart Invoice Processor – Email to Airtable + Drive Automation

## 📄 Description
This n8n workflow automates the end-to-end process of handling invoice emails. It connects Gmail, Airtable, Google Drive, and AI extraction tools to seamlessly classify, extract, store, and respond to invoice data—without any manual steps.



---

## 🚀 Features
- ✅ Auto-detect and classify incoming Gmail emails
- 📎 Supports invoice attachments in **PDF**, **HTML**, and **plain text**
- 🧠 Uses AI to extract structured invoice data (e.g., seller, buyer, items, amounts)
- 📄 Adds extracted data to **Airtable**
- ☁️ Uploads original invoice files to **Google Drive**
- 📧 Sends a confirmation reply to the sender once processed
- 🔁 Fully automated with zero manual input

---
## 📦 Usage

### Prerequisites
- n8n instance (self-hosted or cloud)
- Connected accounts:
  - Gmail (Gmail node access)
  - Google Drive
  - Airtable API access
- Optional: OpenAI, DeepSeek, Claude, or any AI model integrated for extraction

### Steps
1. Clone this repository or import the `.json` workflow into your n8n instance.
2. Set up OAuth credentials for Gmail, Airtable, and Google Drive.
3. Update Airtable base/table fields to match your data structure.
4. Add your email address for reply notifications (if needed).
5. Activate the workflow and test it with sample invoice emails.

---

## 💡 Example Use Case

**Scenario:**  
A small business receives invoices from suppliers in different formats. With this workflow:

- The email is detected and classified as an invoice.
- The attached PDF or HTML file is parsed using AI.
- Key data (supplier name, total, line items) is extracted and saved to Airtable.
- The original invoice is uploaded to Google Drive for archiving.
- A confirmation email is automatically sent to the supplier.

Result: No manual entry, faster processing, and organized records.

---
## 📸 Screenshots

![App Screenshot](https://res.cloudinary.com/deiymcwio/image/upload/v1752566777/snapshot_ubbq5t.png)

---
## Tags
`n8n` `automation` `invoice-processing` `email-bot` `gmail` `airtable` `google-drive` `ai-extraction` `pdf` `html` `workflow` `inbox-automation`

