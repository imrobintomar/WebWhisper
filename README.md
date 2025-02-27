# 🌐 **WebWhisper**

Welcome to **WebWhisper** – an AI-powered web scraping and content parsing solution with a sleek, modern interface. This project uses **Streamlit** for a responsive UI, **Selenium** for robust web scraping, and advanced AI models for intelligent content parsing.

---

## 🗂️ **Table of Contents**
- [🚀 Introduction](#-introduction)
- [✨ Features](#-features)
- [⚙️ Installation](#️-installation)
- [💻 Usage](#-usage)
- [🛠️ Troubleshooting](#️-troubleshooting)
- [🌐 Setting Up ChromeDriver](#-setting-up-chromedriver)
- [📄 License](#-license)

---

## 🚀 **Introduction**
**WebWhisper** provides an intuitive way to scrape and process web content using AI. Developed with a focus on user experience, it leverages **OpenRouter’s DeepSeek API** to transform raw web data into structured insights.

---

## ✨ **Features**
✅ **Web Scraping:** Efficiently scrape websites using Selenium.  
✅ **HTML Parsing:** Clean and structure content with BeautifulSoup.  
✅ **AI-Powered Parsing:** Extract key information using DeepSeek’s NLP capabilities.  
✅ **Modern UI:** Interactive and responsive design built with Streamlit.  
✅ **Custom Parsing Instructions:** Tailor outputs to your data needs.  

---

## ⚙️ **Installation**
> 💡 *Get started in minutes with these steps:*

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/imrobintomar/webwhisper
   cd webwhisper
   ```

2. **Set Up Virtual Environment:**
   ```bash
   python -m venv venv
   # Activate:
   # Windows:
   .\venv\Scripts\activate
   # macOS/Linux:
   source venv/bin/activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Add Environment Variables:**
   Create a `.env` file with your API key:
   ```env
   OPENROUTER_API_KEY=your_openrouter_api_key
   ```

---

## 💻 **Usage**
1. **Launch the App:**
   ```bash
   streamlit run main.py
   ```

2. **Input & Scrape:**  
   - Enter the target website URL.  
   - Click **Scrape Website** to extract content.

3. **View & Parse:**  
   - Explore the DOM content in the **View DOM Content** section.  
   - Enter instructions and click **Parse with DeepSeek** to extract insights.

---

## 🛠️ **Troubleshooting**
🔑 **API Key Errors:** Verify `.env` setup.  
🌐 **Network Issues:** Check connection & DeepSeek service status.  
📏 **Content Limits:** Ensure content meets DeepSeek’s size constraints.  
📄 **Logs:** Review Streamlit logs for detailed error messages.  

---

## 🌐 **Setting Up ChromeDriver**
1. **Download:** Visit [ChromeDriver Downloads](https://chromedriver.chromium.org/downloads) and select the version matching your Chrome browser.
2. **Add to PATH:**
   - **Windows:**
     ```bash
     setx PATH "%PATH%;C:\path\to\chromedriver"
     ```
   - **macOS/Linux:**
     ```bash
     export PATH=$PATH:/path/to/chromedriver
     ```

---

## 📄 **License**
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

🚀 **Start transforming web data into valuable insights with WebWhisper!**

