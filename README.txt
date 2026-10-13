SMART FUSION - DAILY STATUS WEBSITE
Open index.html in Chrome or Edge. Keep logo.png in the same folder.

FEATURES & INSTRUCTIONS:
1. Team-Specific Work Labels:
   - For Developers: "New Website" and "Update".
   - For Testers: "New Website Correction" and "Existing Website Correction".

2. Late for Office Warning:
   - If an employee logs in after 10:00 AM and completes fewer than 9 working hours, a "Late for Office" warning appears.

3. Low Working Hours Reason:
   - When an employee enters their logout time and has completed fewer than 9 working hours, a required reason field appears.
   - The reason is saved and displayed in the Consolidated Report (both table and generated text).

4. Email Functionality:
   - 1-Click Webmail: Use the "Gmail" or "Outlook" buttons to immediately compose the report in your web browser with recipient and report pre-filled.
   - Direct Sending via EmailJS: Click "⚙️ Email Settings" in the Consolidated Report tab to enter your free EmailJS Service ID, Template ID, and Public Key (emailjs.com). Once entered, "Send Report" will send the email directly in the browser.
   - Default Mail Client: Opens your system's mail client, automatically copying the full text to your clipboard so nothing is lost if subject/body length limits are reached.

5. Real-Time Cloud Database & Multi-Location Storage:
   - Live Multi-User Sync: Connect to Firebase Realtime Database so all employees entering status from different laptops/locations are stored centrally and visible live in real time.
   - 2-Minute Setup: Click "Cloud DB" in the top header. Paste your free Firebase Realtime Database URL (e.g. https://your-app-default-rtdb.firebaseio.com).
   - 1-Click Team Link: In the Cloud DB settings modal, click "Copy Team Link". Share this link with your team on Slack, Teams, or WhatsApp. Anyone who opens the link is connected to the exact same database automatically without any manual setup.
   - Offline / Local Backup: Data continues to be backed up locally in browser storage even if offline.
