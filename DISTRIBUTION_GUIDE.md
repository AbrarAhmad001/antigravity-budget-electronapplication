# 🚢 Sharing Antigravity Budget

To share the application with others so they can run it on their Windows devices, follow these simple steps.

---

## 📦 What to Share

You only need to share **one file** with the recipient:

1.  Go to the following folder in your project:
    `frontend/release/`
2.  Find the file named:
    **`Antigravity Budget Setup 0.0.0.exe`** (Note: the version numbers might be higher, e.g., `0.0.1`).
3.  Copy this file and share it via Google Drive, Telegram, USB, or any other file-sharing method.

---

## 📝 Instructions for the Recipient

When you share the `.exe` file, you should also provide them with these instructions:

### 1. Installation
- Run the `Antigravity Budget Setup.exe`.
- The app will install itself and open automatically. It will also create a shortcut on your Desktop.

### 2. First-Time Setup
Since this is a personal finance tool, each user needs their own "plumbing" (API keys and Spreadsheet).

#### A. OpenRouter API Key (For the AI)
- Go to [OpenRouter.ai](https://openrouter.ai/keys) and create a free account.
- Generate an API key and paste it into the app's Setup screen.
- *Recommended Model:* `google/gemini-2.0-flash-lite-preview-02-05:free` or `stepfun/step-3.5-flash:free`.

#### B. Google Sheets (For the Data)
- **Create a New Sheet**: Go to [sheets.new](https://sheets.new).
- **Copy Sheet ID**: The ID is the long string in the URL between `/d/` and `/edit`.
- **Google Service Account**: (This is the technical part)
    1. The user needs a `credentials.json` from a Google Cloud Service Account.
    2. They must **share their sheet** with the service account email as "Editor".
    3. Paste the entire content of that `credentials.json` into the app.

---

## 💡 Pro-Tip for Sharing
If you want to make it *really* easy for a friend, you can **share your own Service Account email** with them (but not your private key!) and have them share their sheet with your service account. However, for full privacy, it is better if they create their own.

---

## ⚠️ Security Warning
**Never share your `config.json` or your personal `credentials.json` file.** These contain your private API keys and access to your personal files. The `.exe` installer is safe to share as it doesn't contain your personal secrets.
