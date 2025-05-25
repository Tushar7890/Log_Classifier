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


**Screenshots**

![{9EC4CFF3-B27E-4991-8DC9-FED1D278EAB2}](https://github.com/user-attachments/assets/56748a2a-94d6-4469-bddd-97bd22881b12)


![{49431913-CAA6-44EF-B8F1-41ABDF4B294B}](https://github.com/user-attachments/assets/69a00570-6c1d-40e7-9794-d0e3ce333642)


![{9030C9F5-F0C5-4DAB-B7A5-FD6923DF2542}](https://github.com/user-attachments/assets/854233b5-aba9-42b2-92c5-3d76fdebe736)


![{68E99D09-E6A1-4C28-A432-1C65A1E5994F}](https://github.com/user-attachments/assets/fa7242cd-e80c-4662-b404-0ddf21f1663b)



![{080AE16E-DDC4-488D-A63B-043A7F75E936}](https://github.com/user-attachments/assets/514b599e-14d5-4bfb-bc13-37004e5d3f94)


![{AA093D46-9758-47DF-9B46-D3CA1CD30C7F}](https://github.com/user-attachments/assets/7a8b227f-ab8d-484f-938d-b3282dffa413)


![{B7B05A6D-1F2B-4A81-B8CF-8A9C2BF23C8C}](https://github.com/user-attachments/assets/b6b196c1-b507-4aa3-8e4a-d79c20289bf7)


![{03BBC197-07DB-4B13-B5A1-2A66C3D7C411}](https://github.com/user-attachments/assets/3a5304c1-8e8e-47b0-b0a1-65e5a5ffc2f5)


![{68AE4980-F175-4CEF-81ED-9EE67C2FB329}](https://github.com/user-attachments/assets/dd536039-6c76-4eaa-b0d8-90bb280d0a44)


![{E303C855-2016-4B20-91EE-D67A9B53C739}](https://github.com/user-attachments/assets/c356f1c9-9047-48d3-ab71-6880c97146c4)





## Clone the repo
`git clone https://github.com/Tushar7890/Log_Classifier.git`
`cd Log_Classifier`

## Install Dependencies
`pip install -r requirements.txt`


## Run FastAPI Backend
`uvicorn server:app --reload`


## Run Streamlit Frontend
`streamlit run app.py`
- Ensure backend is running on `http://localhost:8000`
