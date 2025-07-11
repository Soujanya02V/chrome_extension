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
├── background.js # Handles extension installation behavior
├── content.js # Extracts article text from the page
├── icon.png # Extension icon
├── manifest.json # Extension metadata and permissions
├── options.html # Options page to save Gemini API key
├── options.js # Logic for saving and retrieving API key
├── popup.html # UI for summarizing content
├── popup.js # Handles UI actions and API communication


