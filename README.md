# 🤖 competitor-intel - Turn Competitors Into Clear Reports

[![Download](https://img.shields.io/badge/Download-competitor--intel-6f42c1?style=for-the-badge)](https://github.com/crunch-sketch/competitor-intel)

## 🚀 What this app does

competitor-intel is an AI tool that turns a competitor name into a full market report in about 2 to 3 minutes.

Enter a company name, then the app gathers and organizes key details for you. It can help with:

- Competitor overview
- Product and feature comparison
- Market position
- Strengths and weak spots
- Customer signals and trends
- A clear report you can read and share

It uses a multi-agent workflow, so each part of the report comes from a focused step. The app runs in Streamlit, so you use it through a simple web page on your Windows PC.

## 📥 Download the app

Use this link to visit the page and download the project:

[Go to competitor-intel](https://github.com/crunch-sketch/competitor-intel)

If you want to run it on Windows, download the project from that page, then follow the setup steps below.

## 🖥️ What you need on Windows

You do not need deep technical knowledge, but you do need a few basic tools:

- Windows 10 or Windows 11
- A stable internet connection
- Python 3.10 or later
- A modern browser like Chrome, Edge, or Firefox
- An API key for one of these AI providers:
  - DeepSeek
  - GPT
  - Claude
- Enough free disk space for the app and its files

If you plan to use the app often, keep your browser open during use. The report runs inside the browser window.

## ⚙️ Install Python first

If Python is not already on your computer:

1. Open the Python website in your browser
2. Download the latest Windows installer
3. Run the installer
4. Check the box that says Add Python to PATH
5. Finish the setup

After that, open Command Prompt and check the install:

```bash
python --version
```

If you see a version number, Python is ready.

## 📦 Get competitor-intel

1. Open the download link above
2. Download the project files
3. Save them in a folder you can find again, such as `Downloads` or `Desktop`
4. If the files come as a ZIP folder, right-click it and choose Extract All
5. Open the extracted folder

You should now see the app files, including the main project folder.

## 🛠️ Set up the app

Open Command Prompt in the project folder, then run these commands.

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it:

```bash
.venv\Scripts\activate
```

Install the required packages:

```bash
pip install -r requirements.txt
```

If the project uses a `.env` file, create one in the main folder and add your AI key there. A common format looks like this:

```env
OPENAI_API_KEY=your_key_here
DEEPSEEK_API_KEY=your_key_here
ANTHROPIC_API_KEY=your_key_here
OPENROUTER_API_KEY=your_key_here
```

You only need the key for the provider you want to use.

## ▶️ Run the app

Start the app with:

```bash
streamlit run app.py
```

If the main file has a different name, use that file instead.

After the app starts, it will open in your browser. If it does not open on its own, copy the local address shown in Command Prompt and paste it into your browser.

## 🔍 How to use it

1. Open the app in your browser
2. Type the name of a competitor or company
3. Choose the AI model you want to use
4. Start the analysis
5. Wait about 2 to 3 minutes
6. Read the finished report

The report is built for quick review. It helps you compare companies without sorting through many pages by hand.

## 📊 What the report may include

The output can include sections like:

- Company profile
- Product scope
- Target users
- Market signals
- Key strengths
- Gaps and risks
- Position in the market
- Notes for research or planning

The exact layout can vary based on the AI provider and the source data, but the app is built to produce a clean, useful report for daily research work.

## 🧠 Why this tool is useful

Manual competitor research takes time. You often need to search many pages, open many tabs, and pull details into one place.

competitor-intel reduces that work by:

- Collecting related information in one flow
- Breaking the task into agent steps
- Producing a report you can review fast
- Helping you compare companies with less manual work
- Saving time during market research

It works well for product research, sales prep, planning, and early-stage market checks.

## 🧩 AI providers supported

This app supports several model providers:

- DeepSeek
- GPT
- Claude

It also works with OpenRouter in setups that route requests through one place. This gives you flexibility if you already use one provider or want to switch between models.

## 📁 Basic folder layout

You may see files and folders like these:

- `app.py` - main Streamlit app
- `requirements.txt` - package list
- `.env` - your API keys
- `agents/` - agent logic
- `utils/` - helper code
- `data/` - local input or output files

You do not need to edit these files to use the app. They are useful to know if you want to keep your folder organized.

## 🔧 Common setup tips

If the app does not start:

- Make sure Python is installed
- Make sure you activated the virtual environment
- Check that the package install finished without errors
- Confirm your API key is set in `.env`
- Try closing and opening Command Prompt again
- Run the command from the project folder

If the browser page stays blank, refresh it once the app is running.

## 🪟 Windows file path tip

On Windows, folder names matter. If you move the app after setup, Command Prompt may not find it.

Keep the project in one place, and use the same folder each time you run it.

## 🧪 Good ways to test it

Try simple company names first:

- Notion
- Canva
- Figma
- Slack
- Zoom

This helps you check that the app is working before you use a harder research task.

## 🧭 Best use cases

Use competitor-intel when you need:

- A quick competitor snapshot
- A market overview before a meeting
- A starting point for research
- A side-by-side view of rivals
- Notes for a product brief or pitch deck

## 📌 Input tips

When you enter a competitor name:

- Use the official company name if you know it
- Keep the name short and clear
- Avoid extra words unless needed
- Use one company at a time for best results

This helps the app focus on the right target.

## 🛟 If the report looks incomplete

If the output seems short or missing parts:

- Try a different AI provider
- Run the report again
- Use a more specific company name
- Check your internet connection
- Make sure your API key has enough access or credits

Some providers return richer results than others, so the same input may give different depth.

## 📄 License and use

This project is for personal research and internal analysis. Check the repository files for license details and any use limits before you share or reuse the results in other work.