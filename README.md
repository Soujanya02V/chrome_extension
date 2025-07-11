# 🧠 AI Summary for Articles - Chrome Extension

**AI Summary for Articles** is a Chrome Extension that allows users to quickly summarize any article using Google Gemini AI. It offers brief, detailed, or bullet-point summaries and supports copying the result to your clipboard.



|| 🚀 Features

- 🔍 Extracts article text from any webpage.
- 🤖 Generates summaries using Gemini API:
   -- Brief (2–3 lines)
   -- Detailed
   -- Bullet Points (5–7 key takeaways)
- 📝 Copy summary to clipboard
- 🔐 API key stored securely using Chrome Storage
- ⚙️ Options page to save your Gemini API key

|| 📁 File Structure
$$ background.js > Handles extension installation behavior
$$ content.js > Extracts article text from the page
$$ icon.png > Extension icon
$$ manifest.json > Extension metadata and permissions
$$ options.html > Options page to save Gemini API key
$$ options.js > Logic for saving and retrieving API key
$$ popup.html > UI for summarizing content
$$ popup.js > Handles UI actions and API communication


## 🧪 How It Works

1. On installation, the user is prompted to enter a Gemini API key.
2. When a user clicks the extension icon, they can choose the type of summary and generate it.
3. The `content.js` script fetches visible article content from the page.
4. The `popup.js` sends it to Gemini API and displays the response in the popup.

## 🔑 How to Get a Gemini API Key

1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Sign in with your Google account.
3. Copy your API key and paste it in the **Options** page of the extension.

## 🛠️ Installation

1. Clone or download this repository.
2. Go to `chrome://extensions` in your browser.
3. Enable **Developer Mode** (top right).
4. Click **Load Unpacked** and select the folder containing these files.
5. Click the extension icon → set your API key → start summarizing!

## 📌 Permissions Required

- `activeTab` – to access the current page content.
- `storage` – to save the API key.
- `scripting` and `host_permissions` – for content script execution on pages.

## 💡 Example Use Cases

- Summarize long blog articles
- Quickly review research papers or reports
- Get key takeaways from news articles


**Created with  using Gemini AI and Chrome Extension APIs**



