# n8n-workflow2. The workflow:
- Extracts the GitHub username
- Fetches GitHub profile & repositories
- Analyzes activity, stars, and inactive repos
- Builds a festive prompt
- Generates a Santa-style roast using an LLM
3. Santa replies back on WhatsApp 🎄

---

## 🛠 Tech Stack

- **n8n** – Workflow automation
- **WhatsApp Cloud API (Meta)**
- **GitHub Public REST APIs**
- **LLM (via n8n Basic LLM Chain)**
- **JavaScript (Code nodes)**

---

## 🔄 Workflow Overview

- WhatsApp Trigger
- Text parsing & validation
- GitHub Profile API call
- GitHub Repositories API call
- Data aggregation & analysis
- Prompt generation
- LLM response
- WhatsApp reply

---

## 🎯 Key Features

- Friendly, non-offensive Christmas humor
- Simple language output (for normal users)
- Robust handling of multi-node data flow
- Clean prompt engineering for consistent results
- Fully automated end-to-end flow

---

## 📽 Demo

👉 See the working demo video on LinkedIn  
(Attach your LinkedIn post link here)

---

## 🚀 How to Use

1. Import the workflow into n8n
2. Configure:
- WhatsApp Cloud API credentials
- LLM credentials
3. Activate the workflow
4. Send a WhatsApp message to start roasting 🎅

---

## ⚠️ Notes

- This project uses **public GitHub data only**
- The roast is intentionally light-hearted and friendly
- No private or sensitive data is stored

---

## 📌 Future Improvements

- “Nice list / Naughty list” modes
- Hinglish or multilingual Santa
- Quick reply buttons on WhatsApp
- Roast history or leaderboard

---

## 🤝 Contributions

Suggestions and improvements are welcome.
Feel free to fork and customize the workflow.

---

## 📄 License

This project is for learning and demo purposes.
