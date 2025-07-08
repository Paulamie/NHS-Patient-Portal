
# NHS Insight  
*A patient data management and analysis platform built with Flask.*

---

## 🧩 Introduction

**NHS Insight** is a Python-based web application built using Flask. It serves as the backend for a data dashboard system to support healthcare staff in managing, viewing, and analyzing patient-related data. The application reads CSV files and uses Python logic to interpret and visualize the information via a simple web interface.

---

## 🚀 Features

- Upload and process NHS patient data via CSV
- Visualize key metrics using a clean dashboard
- Backend logic for algorithmic analysis (via `algorithm.py`)
- Lightweight, responsive frontend with custom JavaScript and CSS
- Modular codebase for easy extension or integration

---

## 🛠️ Installation

1. Ensure you have **Python 3.x** installed.
2. Clone the repository or download the ZIP and navigate into the project folder:
   ```bash
   cd NHS-App-main
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Running the App

Start the Flask development server with:

```bash
python3 app.py
```

Once running, open your browser and visit:

```
http://localhost:5000
```

---

## 📁 Project Structure

```
├── app.py                     # Main Flask application
├── algorithm.py               # Data processing logic
├── requirements.txt           # Python package dependencies
├── static/                    # Frontend CSS & JS
│   ├── style2.css
│   ├── styles.css
│   └── script.js
├── docs/                      # UML Diagrams (Use Case, Sequence)
│   ├── UseCase Diagram0.jpg
│   └── Sequence Diagram0.jpg
├── *.csv                      # Input data files
├── TODO.md                    # Feature list / development notes
└── README.md                  # This file
```

---

## 📊 Data Files

The application expects structured data input in `.csv` format, including:
- `InputTest.csv`
- `Feeding Dashboard data.csv`
- `Algorithm.csv`

These are processed and displayed through the dashboard.

---

## 🧪 Development Notes

- `testingref.py` was used for testing CSV logic.
- Diagrams can be found in the `docs/` directory.
- You can modify `algorithm.py` to extend processing logic or plug in additional analytics.

---

## 📌 Future Improvements

- Add authentication and session handling
- Export processed data to PDF or Excel
- Integrate database storage for historical data
- Improve visual charts using libraries like Chart.js or Plotly

---


Student project for applied software or system development using Python & Flask.

---
