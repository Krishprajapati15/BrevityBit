# 🧠 BrevityBot – AI-Powered Website Summarizer Chrome Extension

**BrevityBot** is a lightweight and intelligent Chrome extension that leverages AI to summarize the content of any webpage into concise and digestible paragraphs. This tool is designed to enhance productivity by eliminating the need to read through lengthy articles or reports. With just one click, users receive a clear, human-readable summary of the key content.

---

## 🚀 Features

- 🔍 **One-click summarization** of any webpage using AI
- 🌐 Clean, minimal popup interface
- 📄 Outputs readable, structured paragraphs
- ⚡ Built with Manifest V3 for improved security and performance
- 🧩 No background processes until activated — highly optimized for performance

---

## 📦 Installation (Manual / Local)

To install and use BrevityBot manually (without publishing to the Chrome Web Store):

### 1. **Clone or Download the Repository**

```bash
git clone https://github.com/YOUR-USERNAME/BrevityBot.git
# Or download the ZIP file from the Releases section.
```

2. **Unzip (if downloaded as ZIP)**  
   Extract the contents into a folder named BrevityBot or any name of your choice.

3. **Load the Extension into Chrome**
   - Open Google Chrome.
   - Navigate to: `chrome://extensions`
   - Enable Developer Mode (toggle in the top-right corner).
   - Click “Load unpacked”
   - Select the folder where the extension files are located.
   - The BrevityBot icon should now appear in your Chrome toolbar.

---

## 🛠️ How It Works

1. Navigate to any article or content-heavy webpage.
2. Click the BrevityBot icon from the Chrome toolbar.
3. The popup interface will appear and automatically extract and summarize the page content using AI.
4. The summary is displayed in a readable paragraph format within the extension interface.

**Internally**, the extension:

- Accesses the DOM of the active tab using `activeTab` permission.
- Extracts visible text content dynamically.
- Sends the content to a built-in or third-party AI summarization engine (via API or local logic, depending on implementation).
- Renders the summary back in a minimalistic popup.

---

## 📁 Project Structure

```
├── background.js
├── content.js
├── icon.png
├── LICENCE
├── manifest.json
├── options.html
├── options.js
├── popup.html
├── popup.js
└── README.md
```

---

## 🧪 Requirements

- Google Chrome (latest version recommended)
- Internet connection (if using an external AI API)

---

## 🔐 Permissions Used

- `"activeTab"` – to read the content of the currently open webpage.
- `"scripting"` – to execute scripts in the context of web pages.

---

## 📄 License

This project is licensed under the MIT License. See [LICENCE](./LICENCE) for details.

---

## 🤝 Contributing

Feel free to fork the repo and submit pull requests. Contributions to improve the summarization logic or UI are welcome.

---

## 📬 Contact

For queries or suggestions, contact the maintainer via GitHub Issues or email: your.email@example.com

---

If you'd like, I can also:

- Customize the `popup.html` and `popup.js` for better AI integration visuals.
- Write API usage examples for OpenAI, Gemini, etc.
- Add a `LICENSE` and `CONTRIBUTING.md` file for open source best practices.

Let me know if you'd like the README exported as a downloadable `.md` file or need GitHub repo setup assistance.
