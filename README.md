# 📅 DateGrab – Web to Google Calendar

> *Clean, Creative Code Crafted by Carl — by **CH5 Labs***

DateGrab is a lightweight browser extension that scans any webpage using AI models hosted by [Groq](https://groq.com), extracts upcoming dates, times, locations, and direct event links, and generates one-click **Google Calendar** links.

## ✨ Features

* **One-Click Date Extraction:** Detects upcoming events from concert schedules, timetables, and tables. Handles long event lists (up to 60 events per scan).
* **Smart Event Links:** Links directly to the specific event subpage when available.
* **Multi-Language:** Outputs event titles and descriptions in the same language as the webpage.
* **Privacy-First:** Uses your own free Groq API key, stored locally in your browser (`chrome.storage.local`). Nothing is read from a page until you click **Scan this page**.

## 📥 Installation

**Microsoft Edge Add-ons:** *link coming soon.*

## 🚀 Getting started

1. Create a free API key in the [Groq Console](https://console.groq.com/keys) (sign in with Google or GitHub).
2. Open DateGrab from the toolbar, paste your key (it starts with `gsk_`) and click **Save key**.
3. Go to any webpage with events, open DateGrab and click **Scan this page**.
4. Click **+ Add to Google Calendar** on the events you want.

## 🛠️ For developers

To run the extension from source:

1. Clone or download this repository.
2. Open `edge://extensions` and enable **Developer mode**.
3. Click **Load unpacked** and select the project folder (the one containing `manifest.json`).

After changing the code, click the reload icon on the extension's card.

## 🔒 Privacy

When you click **Scan this page**, the text and links of the active tab are sent from your browser to Groq's API to find the dates. DateGrab has no servers of its own and collects no analytics.

Read the full [Privacy Policy](PRIVACY.md).

## ⚖️ Disclaimer

DateGrab is an independent project and is not affiliated with or endorsed by Google or Groq. Always double-check dates and times before relying on them, as AI extraction can make mistakes.
