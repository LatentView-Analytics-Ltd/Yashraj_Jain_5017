# 🛡️ Axion Sentinel Elite: Governance Engine

### _Context-Aware Sovereign Content Verification for Enterprise Marketing_

![Azure OpenAI](https://img.shields.io/badge/Azure-OpenAI-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-Vector_DB-E22D30?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

---

## 📖 Overview

Axion Sentinel Elite is a sophisticated **Content Operations Audit Engine** designed to solve the "consistency under constraint" problem in enterprise marketing. It serves as the "last line of defense", ensuring every piece of content adheres to strict brand guidelines, audience-specific tones, and channel-specific formatting rules.

## 🎯 Key Features

- **3x3 Governance Matrix**: Automatically pivots logic based on 6 channels (LinkedIn, Press Release, etc.) and 3 audiences (Executive, Practitioner, Technical).
- **RAG-Backed Compliance**: Retrieves sovereign brand rules from a vector store to flag prohibited jargon like "leverage" or "synergy".
- **Hard-Enforcement Truncation**: Physically prevents content from exceeding channel word limits (e.g., 10 words for headlines, 150 for LinkedIn).
- **Enterprise Business Impact**: Calculates "Governance Savings" and "Efficiency Gains" in real-time to demonstrate ROI.
- **Traceable Change Log**: Provides a line-by-line rationale for every modification made to the original draft.

## ⚙️ Setup

1. Install dependencies: `pip install -r requirements.txt`
2. Create a `.env` file based on `.env.example`.
3. Run the app: `streamlit run app.py`

---

_Developed for the Hackathon Track: AI/AI Agents in Marketing Operations._
