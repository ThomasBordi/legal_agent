# 💬 LLM-Legal-ChatBot

A simple Streamlit application demonstrating how to build a chatbot using OpenAI's GPT-3.5.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://chatbot-bw4vgsoyviyz5era9exlfn.streamlit.app/)

## How to Run Locally

1. Install dependencies

   ```sh
   pip install -r requirements.txt
   ```

2. Run the application

   ```sh
   streamlit run streamlit_app.py
   ```

## Features

- 📜 **Legal Consultation** - Get quick legal advice.
- 📝 **Document Drafting** - Generate legal documents quickly.
- 🔍 **Case & Law Search** - Find relevant legal cases and laws.
- ⚖️ **Legal Process Guidance** - Understand legal procedures.

## File Descriptions

- `streamlit_app.py` - Main application file containing Streamlit page configuration and functionality.
- `rag_utils.py` - Utility functions for text extraction, chunking, and retrieval.
- `requirements.txt` - List of project dependencies.
- `.devcontainer/devcontainer.json` - DevContainer configuration file.
- `.github/CODEOWNERS` - GitHub code owners configuration file.
- `LICENSE` - Project license file.
- `.gitignore` - Git ignore file configuration.

## Developer Information

Developed by Thomas Bordino and Wenbo Liu.

## Notes

- **API Key Required** - An API key from OpenAI or DeepSeek is required to use this app.
- **Billing Setup** - Charges apply once the free credit runs out. Set up billing to avoid authentication errors.
- **Monitor Your Usage** - Keep track of your account to prevent unexpected charges.

