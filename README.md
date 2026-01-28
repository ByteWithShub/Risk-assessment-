# Risk Assessment for SMEs (Compliance + Risk Scoring)

This project is a risk-assessment workflow designed for **SMEs (Small and Medium-sized Enterprises)**. It focuses on turning uploaded/internal compliance material (e.g., policy text, reports, controls evidence) into **structured signals** that can be compared against **external frameworks/checklists** to generate:

- Risk indicators (gaps, missing controls, inconsistencies)
- A transparent risk score
- Actionable recommendations and summaries

> Goal: help a user understand *what’s risky, why it’s risky, and what to fix first*.

The repository includes:
```
A web application interface (Vite + Ionic)
End-to-end testing via Cypress
Python dependencies for analytical / ML workflows
Configuration for cross-platform deployment (Capacitor)
``` 
---
### What this project does

### Core ideas
- **Ingest** internal documents or structured inputs (reports/policies/checklists)
- **Preprocess** text/data into consistent sections and fields
- **Compare** internal evidence vs expected controls/frameworks
- **Score** risk based on rules/weights and detected gaps
- **Explain** results with readable outputs (tables + short reasoning)

### Typical outputs
- Risk score by category (e.g., documentation, governance, controls)
- Identified missing / weak / inconsistent items
- Priority list of recommended actions

---

### Setup
```
Prerequisites
Node.js + npm
Python

 1) Create and activate a virtual environment (Windows)
python -m venv .venv
.venv\Scripts\activate

2) Install dependencies
pip install -r requirements.txt

3) Frontend
npm install
npm run dev

4) Tests (Cypress)
npm run test

```


### Project Goals
```
The platform focuses on:
Converting qualitative compliance inputs into structured representations
Highlighting missing or weak controls
Producing interpretable risk indicators
Supporting SME decision-making through transparent scoring logic

High-level workflow:
User provides internal compliance or operational data
Data is processed and normalized
Risk factors are identified
Results are surfaced through the frontend interface
Python tooling supports scoring / analysis logic
The design emphasizes explainability over black-box prediction.
```

### Future Enhancements
```
Planned or possible extensions:
Streamlit or dashboard integration for analytics visualization
Expanded risk scoring models
NLP-based document ingestion
External framework comparison
Role-based UI flows
Deployment to cloud environments
``` 
