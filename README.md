# 🔍 Log Classifier Web App

A log classification tool built using **FastAPI** (backend) and **Streamlit** (frontend) that allows users to upload a CSV file of logs or input logs manually, classify them using ML/NLP techniques, and visualize the results interactively.

---

## 🚀 Features

- ✅ Upload logs via CSV or enter them manually
- 🧠 Classify logs using ML models (Regex, BERT, or LLM-based)
- 📧 Option to receive classification results via email
- 📊 Rich visual analytics:
  - Label distribution histograms
  - Source vs Label heatmaps
  - Classification method usage pie charts
  - Confidence score box plots
  - Top frequent log messages per label
- 📥 Download the classified logs as CSV

---

## 📁 CSV Format

Your CSV should contain the following columns:

| timestamp | source | log_message | target_label | complexity |
|-----------|--------|-------------|---------------|------------|

At minimum, `source` and `log_message` columns are required for classification.

---



## Clone the repo
git clone https://github.com/Tushar7890/Log_Classifier.git
cd Log_Classifier

## Install Dependencies
pip install -r requirements.txt


## Run FastAPI Backend
`uvicorn server:app --reload`


## Run Streamlit Frontend
- streamlit run app.py
- Ensure backend is running on http://localhost:8000
