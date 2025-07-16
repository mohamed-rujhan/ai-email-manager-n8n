# 📬 AI-Powered Email Manager (n8n + Gemini + ChatGPT + Google Sheets + Gmail)

A smart, automated email classification and response system built with n8n, Gemini, ChatGPT, Google Sheets, and Gmail.

---

## 🔧 Features

- Email Classification (via Gemini AI):
  - Categories: Promotion, Social Media, Personal, Recruitment, Miscellaneous
- Dynamic Actions per Category:
  - Promotion: Labeled and marked as read
  - Social Media: Summarized using ChatGPT → Logged in Google Sheets
  - Recruitment: Name and Position extracted via ChatGPT → Logged in Google Sheets
  - Personal: Auto-reply generated using ChatGPT and sent via Gmail
  - Miscellaneous: GPT generates purpose → Logged for future training

---

## 💻 Tech Stack

- n8n (open-source automation tool)
- Gemini (Google AI) for classification
- OpenAI ChatGPT for extraction, summarization, replies
- Gmail API for reading, labeling, and replying
- Google Sheets API for logging structured data

---

## 🧠 How It Works

1. Email is fetched from Gmail
2. Gemini classifies the email content
3. Based on the category:
   - ChatGPT processes data
   - Sheets are updated or Gmail is used to reply
   - Misc cases generate GPT suggestions

---

## 🧾 Sample Sheet Logs

### Social Media Emails

| ID           | Date       | Subject | Summary                         | Snippet             |
|--------------|------------|---------|----------------------------------|----------------------|
| 1980f1...    | 2025-07-15 | test    | The email is a social message.  | this is social mail  |

### Recruitment Emails

| ID           | Date       | Name  | Position        |
|--------------|------------|-------|------------------|
| 1980f1...    | 2025-07-16 | Sarah | AI Engineer Role |

### Miscellaneous Emails

| ID           | Subject | Sender                     | Date       | GPT Suggestion                                       |
|--------------|---------|----------------------------|------------|------------------------------------------------------|
| 1980f1...    | test    | abcd@gmail.com  | 2025-07-16 | The purpose of this email is to test the system.     |

---

## 🎯 Use Case

Designed for recruiters, professionals, or anyone overwhelmed by emails. This intelligent system streamlines email processing using AI-based decision trees.

---

## 📸 Screenshots
<img width="1078" height="616" alt="Screenshot 2025-07-16 at 17 04 02" src="https://github.com/user-attachments/assets/578cbf0a-41d7-4fee-86de-a413d9d57ad4" />



---

## 📎 Author
I.Mohamed Rujhan,
Automation and AI Enthusiast.
