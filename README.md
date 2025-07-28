# 📄 Gemini-Powered Project

## Current Features

- 📤 Upload any scanned or digital PDF
- 🤖 Extract
- 💾 Generate Excel Report with Laytime Calaculations


---

## 🛠️ Setup Instructions (for All Users)

### ✅ Prerequisites

- Python 3.9 or higher  
- A **Google Cloud API key** with Gemini access  
- Vertex AI API enabled on your GCP project  

---

### 1. Clone This Repository

```bash
git clone "insert-repo-link"
cd "Repo-Name"
```

### 2. Create and Activate a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```

### 3. Install All Required Dependencies

```bash
pip install -r requirements.txt
```

### 4. Set Up Your Google Gemini API Key

Export in bash

```bash
#For Mac
  export GOOGLE_API_KEY=your-google-api-key-here
```
```bash
#For Windows
  set GOOGLE_API_KEY=your-google-api-key-here
```
(Get API key from project credentials of your GCP)

### 5. Enable Vertex AI API on Your Google Cloud Project

```bash
gcloud auth application-default login
gcloud config set project your-project-id
gcloud services enable aiplatform.googleapis.com
```

## How to Run

### Streamlit Web App

```bash
streamlit run app.py
```
