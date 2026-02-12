# Weather & Time Agent

> An AI agent built using **Google ADK** that can answer questions about **current weather** and **local time** in a city.

---

## Features

- ✅ Retrieve weather details (currently supports **New York**)  
- ✅ Get current local time for a city  
- ✅ Uses `ZoneInfo` for timezone support  
- ✅ Powered by `gemini-2.0-flash` model  
- ✅ Easily extendable with new tools

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Python 3.9+ | Programming language |
| Google ADK | AI agent framework |
| Gemini 2.0 Flash | Language model |
| datetime, zoneinfo | Time and timezone handling |

---

## Project Structure

```text
.
├── .gitignore
├── README.md
├── requirements.txt
└── main.py


---

## Installation

### 1) Clone the Repository

```bash
git clone https://github.com/pavaniravalkol/Agents.git
cd Agents

2) Create a Google account & generate a Gemini API key
Sign in (or create an account) at Google AI Studio.
Go to https://ai.google.dev/gemini-api/docs/api-key → click Get an API key.
Copy the key (treat it like a password).
Recommended environment variable names (either works):
GOOGLE_API_KEY (preferred; takes precedence if both are set)
GEMINI_API_KEY
2.1 Set your API key as an environment variable (temporary in current shell)
macOS/Linux (bash/zsh):

export GOOGLE_API_KEY="paste_your_key_here"
Windows (PowerShell):

$Env:GOOGLE_API_KEY = "paste_your_key_here"
You only need one of GOOGLE_API_KEY or GEMINI_API_KEY. If both are set, GOOGLE_API_KEY wins. To persist across sessions, add the export command to your shell profile or use a .env file.

2.2 Optional: Store your key in a .env file (for local dev)
Create a .env in your project root:
GOOGLE_API_KEY=paste_your_key_here
Security: Never commit .env to version control; add it to .gitignore.

3) Create Virtual Environment
python -m venv .venv

Install ADK
With your environment activated, install the Python ADK package:

# pip path
pip install google-adk

# OR uv path
uv pip install google-adk

pip show google-adk
adk --version
adk --help

4) Activate Virtual Environment
# macOS / Linux
source .venv/bin/activate

# Windows
.venv\Scripts\activate

5)Install Dependencies
pip install -r requirements.txt

