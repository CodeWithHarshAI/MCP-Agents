# 🌐 MCP Agents

MCP Agents is an AI-powered interactive browser assistant built with **Streamlit**, **OpenAI**, and **Puppeteer** using the **Model Context Protocol (MCP)**. Type natural language commands like *"Go to Wikipedia and search for Mars"* and the app will navigate, click, scroll, and even extract content — all hands-free.

---

## 🚀 Features

🔹 **Talk to the Web** — Interact with websites using simple English commands
🔹 **Visual Automation** — Take screenshots, click elements, and scroll pages effortlessly
🔹 **Flexible Agent System** — Powered by the modular MCP Agent framework
🔹 **Secure Integration** — API keys stored safely with optional secrets config
🔹 **Fully Interactive UI** — See command results directly in the app interface

---

## 🎯 Use Cases

💼 Product scraping, news summarization, automated browsing workflows
🧪 Educational bots that walk through websites
📰 Daily content extraction from dynamic pages

---

## ⚙️ Requirements

* Python 3.8 or newer
* Node.js + npm (for Puppeteer server)
* OpenAI API key

---

## ⚡ Quick Start

```bash
# Clone and enter the project
$ git clone https://github.com/your-username/mcp-agents.git
$ cd mcp-agents

# Install Python dependencies
$ pip install -r requirements.txt

# Verify Node.js setup
$ node --version && npm --version

# Optional: Start Puppeteer agent
$ npx -y @modelcontextprotocol/server-puppeteer

# Run the app
$ streamlit run main.py
```

Visit [http://localhost:8501](http://localhost:8501) in your browser.

---

## 🔐 Configure Secrets

Create a file named `mcp_agent.secrets.yaml`:

```yaml
openai:
  api_key: "your-openai-api-key"
```

➡️ Make sure this file is listed in `.gitignore` to avoid leaking credentials.

---

## 💬 Example Commands You Can Try

* "Go to [www.wikipedia.org](http://www.wikipedia.org)"
* "Search for black holes and summarize the page"
* "Click on the first heading"
* "Take a screenshot of the hero section"
* "Scroll down and extract all h2 titles"

---

## 📁 Project Overview

```
mcp-agents/
├── main.py                     # Streamlit application
├── requirements.txt           # Python dependencies
├── README.md                  # This file
├── mcp_agent.config.yaml      # Config for Puppeteer + agent setup
├── mcp_agent.secrets.yaml     # API secrets (ignored from Git)
├── .gitignore                 # File exclusions
```

---

## 📄 License

Licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ Created By

Built with ❤️ by [Harsh](https://github.com/your-username).
Powered by the open agent framework from MCP and inspired by LastMileAI tooling.

---

👨‍💻 Want to build your own AI-powered automation agent? **Fork this repo and start customizing!**
