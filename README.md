
```markdown
# 🔍 Subrogation Recovery Agent

A simple GenAI-powered tool to analyze insurance claim documents and generate subrogation demand letters automatically.

---

## 🚀 Features

- Upload `.pdf` or `.txt` claim documents
- Extract claim details like policy number, insured name, date, etc.
- Analyze subrogation recoverability (recoverable or not)
- Generate demand letter for recovery
- Download the letter as `.txt`

---

## 🧑‍💻 Technologies Used

### 🔹 Frontend
- React (with Vite)
- Axios
- HTML/CSS

### 🔹 Backend
- Flask (Python)
- Flask-CORS
- PyMuPDF (PDF text extraction)
- Regex (for detail parsing)

---

## 📁 Folder Structure

```

project/
├── backend/
│   └── app.py
├── frontend/
│   └── src/
│       ├── App.jsx
│       ├── main.jsx
│       └── styles.css
├── index.html
└── README.md

````

---

## ⚙️ Setup Guide

### Backend (Flask)

```bash
cd backend
pip install flask flask-cors pymupdf
python app.py
````

Runs at: `http://localhost:5000`

### Frontend (React + Vite)

```bash
cd frontend
npm install
npm run dev
```

Runs at: `http://localhost:5173`

---

## ✅ How to Use

1. Upload your insurance claim file
2. Click **Extract** to view the text
3. Click **Analyze** to check if recovery is possible
4. Click **Generate Letter**
5. Click **Download Letter** to save it

---

## 📝 Sample Input

```txt
Insured: Mr. Rahul Mehta
Policy Number: PL-9983-MH
Claim Number: CLM-45789-AZ
Date of Loss: March 3, 2024
Description: Skidded and hit a pole. No third-party involved.
```
## created by Arya Raut

