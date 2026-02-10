# 🌌 Antigravity Budget

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react)](https://reactjs.org/)
[![Electron](https://img.shields.io/badge/Electron-47848F?style=flat&logo=electron)](https://www.electronjs.org/)

**Antigravity Budget** is a premium, multi-modal expense tracker that leverages AI to automate your personal finance management. Stop manually entering every coffee and grocery trip—just speak it, text it, or snap a photo.

---

## ✨ Key Features

- 🎙️ **Text Capture**: "On february 9th Bought coffee for 5 taka and Salary received 3000 taka and on 10th snacks 200tk". AI understands and parses the rest.
- 📸 **Smart Receipt Scanning (If model supports) **: Upload images of receipts; the AI extracts items, prices, and dates with high accuracy.
- 🤖 **Custom Reasoning Model Insersion Option (Openrouter.ai)**: Users can use their own available reasoning models they have API for.
- 📊 **Dynamic Dashboard**: Real-time analytics, monthly summaries, and visual distribution of spending.
- 📅 **Google Sheets Backend User Links**: Your data stays in *your* hands. All transactions are synced directly to a private Google Sheet.
- 🎯 **Budget Management Settint Option**: Set monthly targets per category and track progress with visual alerts.
- 📁 **Savings Tracking**: Track spending from specific savings funds or "Vaults" to see the impact on your net worth.
---

## 🚀 Desktop Application Setup 

The easiest way to use Antigravity Budget is by running the standalone Windows application.

### 1. Installation
- Download the `Antigravity Budget Setup.exe` from the latest release.
- Run the installer. The app will install and open automatically.

### 2. Initial Configuration
When you first launch the app, you'll be greeted with a **Setup Screen**. You will need three things:

#### A. Reasoning Model Name (OpenRouter.ai)
1. Look for reasoning models (Text and/or Image)
2. Copy the name for example: stepfun/step-3.5-flash:free
3. Paste the name in the box
   
#### B. OpenRouter API Key
1. Go to [OpenRouter.ai](https://openrouter.ai/keys).
2. Create a free account and generate an API key.
3. Paste the key into the app.

#### C. Google Sheet ID
1. Create a new Google Sheet.
2. Copy the ID from the URL: `docs.google.com/spreadsheets/d/`**`YOUR_SHEET_ID_HERE`**`/edit`.
3. Paste it into the app.

#### D. Google Service Account credentials
1. Go to [Google Cloud Console](https://console.cloud.google.com/).
2. Create a project and enable the **Google Sheets API** and **Google Drive API**.
3. Create a **Service Account** and generate a **JSON Key**.
4. **Share your Google Sheet** with the service account's email address (e.g., `app-tracker@your-project.iam.gserviceaccount.com`) as an "Editor".
5. Copy the entire contents of the JSON file you downloaded and paste it into the "Google Service Account JSON" field in the app.

---

## 🛠️ Developer Guide

### Prerequisites
- **Node.js** (v18+)
- **Python** (v3.11+)
- **OpenSSL** (for backend dependencies)

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🤝 Contact

**Abrar Ahmad** - [@AbrarAhmad001](https://github.com/AbrarAhmad001)

Project Link: [https://github.com/AbrarAhmad001/antigravity-budget](https://github.com/AbrarAhmad001/antigravity-budget)

