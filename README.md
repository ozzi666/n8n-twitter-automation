# n8n WhatsApp AI Assistant + Google Sheets Integration

This project powers our WhatsApp AI Assistant service for turf clients using [n8n](https://n8n.io) automation. It connects the WhatsApp AI assistant to Google Sheets, enabling seamless data storage and retrieval for each turf’s users.

## 🌐 What This Project Does

- Each turf (client) gets a dedicated Google Sheet
- The WhatsApp AI Assistant stores user interactions and data into that sheet
- n8n orchestrates the workflow between WhatsApp, Google Sheets, and other services
- Helps turf owners view and manage their customer data efficiently

---

## 🔐 Privacy Policy

We take privacy seriously. Here's how we handle your data:

- **What we access**: This integration uses the Google Sheets API to read and write data to Google Sheets that you authorize.
- **How we use it**: Only the sheets linked to your WhatsApp AI Assistant workflow are accessed. The data stored is typically related to interactions between your users and the assistant.
- **What we don't do**:
  - We do **not** access any other part of your Google account
  - We do **not** share your data with third parties
  - We do **not** store your data outside of your Google Sheets
- **Who has access**: Only authorized automation workflows (built using n8n) and the turf admins (you) have access to the sheets.

If you ever wish to revoke access, you can do so from your [Google Account Permissions](https://myaccount.google.com/permissions).

---

## 📞 Contact

For any questions or concerns, feel free to contact us:

**Email:** musa.khan6636@gmail.com  
**Website:** https://hmhautomation.vercel.app/

---

## 📎 Google API Disclosure

This app uses Google APIs to interact with Google Sheets. This usage is strictly limited to the scopes required for reading and writing spreadsheet data as authorized by the user.

