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

## 📂 Project Structure

```text
.
├── .gitignore
├── README.md
├── requirements.txt
└── main.py


---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/pavaniravalkol/Agents.git
cd Agents


2️⃣ Create Virtual Environment
python -m venv .venv

3️⃣ Activate Virtual Environment
# macOS / Linux
source .venv/bin/activate

# Windows
.venv\Scripts\activate

4️⃣ Install Dependencies
pip install -r requirements.txt

