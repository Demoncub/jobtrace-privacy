# Privacy Policy for JobTrace

**Effective Date:** November 21, 2026  
**Application Name:** JobTrace (`com.jobtrace.app`)  
**Version:** 1.1.0

JobTrace ("we", "our", or "the App") is a privacy-first field logging, estimating, and invoice utility designed for independent contractors, technicians, and field service professionals. We are committed to protecting your privacy and ensuring that you retain 100% ownership and control of your business and client records.

---

## 1. Information We Collect and Store (100% On-Device)

JobTrace operates as an **offline-first, local-only** application. All information you enter or generate within JobTrace is stored exclusively on your mobile device (using on-device SQLite / Room database and private app-only internal storage):
- **Contractor & Business Profile:** Business name, technician/owner name, phone number, billing email, license number, sequential invoice prefix/numbering, custom flat-rate service book, tax settings, monthly revenue goal, and payment remittance instructions.
- **Estimates, Job Logs & Invoices:** Client names, site addresses, client phone/email, service descriptions, labor hours, hourly rates, materials costs, extra line items, discounts, deposits, customer authorization signatures, payment statuses, and voice transcripts.
- **Optional Proof-of-Work Site Photos:** Compressed Before & After / parts receipt photos that you explicitly choose to capture or pick for a job.

**We do not operate any backend servers, cloud databases, advertising SDKs, or analytics trackers.** JobTrace does not even request the Android `INTERNET` permission. None of your business information, client lists, photos, or financial data is ever transmitted to, collected by, or shared with JobTrace or any third party.

---

## 2. Microphone & Speech Recognition Permission (`android.permission.RECORD_AUDIO`)

JobTrace requests access to your device's microphone (`RECORD_AUDIO`) **solely** when you actively tap the **"Tap & Speak"** button on the Record screen to dictate field job notes.
- Audio is processed in real time using your device's native speech recognition service (`android.speech.SpeechRecognizer`) to convert spoken words into text.
- **JobTrace never records, saves, stores, or transmits raw audio files.**
- You can use JobTrace in full without granting microphone permission by typing job notes or using the **Manual Entry** form.

---

## 3. Proof-of-Work Photos (No Broad Storage or Camera Permissions)

When you attach optional Before or After site photos to a job:
- **Photo Picker (`PickVisualMedia`):** Uses Android's privacy-preserving system Photo Picker so JobTrace can only access the specific image you select—never your broader photo library.
- **System Camera Intent (`TakePicture`):** Delegates capture to your device's built-in camera app without requesting background camera permission.
- Selected or captured photos are compressed and saved privately in JobTrace's app-only internal storage solely to display on your invoice screen and embed into PDFs you generate.

---

## 4. Data Sharing, PDF Invoices, CSV Exports & JSON Backups

Your data only leaves your device when **you** explicitly initiate an action using your device's native system share sheet, print dialog, document picker, or messaging/email app:
- **Print / Share PDF Invoice or Estimate:** Generates a local multi-page PDF document in temporary cache and opens your device's system print dialog or share chooser (e.g., Email, SMS, or WhatsApp).
- **Email Paid Receipt / SMS Reminder:** Opens your default email (`mailto:`) or SMS (`smsto:`) app pre-populated with receipt or invoice details for you to review and send.
- **CSV Export & JSON Backup / Restore:** Exports a `.csv` spreadsheet or full `.json` backup to temporary cache so you can save it anywhere you choose, and lets you restore a previously exported `.json` backup via Android's system document picker when switching devices.

---

## 5. Data Retention & Deletion

Because all data is stored locally on your device, you have complete control over data retention and deletion at all times:
- **Delete Individual Jobs:** Tap the delete (trash) icon on any job card in the **Job Database** tab.
- **Clear All Jobs:** Open **Settings → Data Backup & Privacy Policy → Clear All Jobs from Device** to permanently erase all job records.
- **Complete Removal:** Uninstalling JobTrace or clearing application storage in your device's system settings permanently removes all local databases, photos, and preferences from your device.

---

## 6. Children's Privacy

JobTrace is a professional business and productivity utility intended for adult trade contractors and business owners. It is not directed at children under the age of 13, and we do not knowingly collect any personal information from children.

---

## 7. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect app updates or legal requirements. Any changes will be updated in the in-app Privacy Policy viewer and on our published Privacy Policy page.

---

## 8. Contact Us

If you have any questions about this Privacy Policy or JobTrace's privacy practices, please contact us at the developer support email listed on the Google Play Store listing.
