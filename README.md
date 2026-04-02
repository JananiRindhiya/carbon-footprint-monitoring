# 🌿 Carbon Footprint Monitoring System
### IPRC Activities | 

---

## 📁 Project Structure

```
carbon_monitor/
│
├── app.py                  ← Main Flask application (backend)
├── carbon.db               ← SQLite database (auto-created on first run)
├── requirements.txt        ← Python packages needed
│
└── templates/
    ├── base.html           ← Shared layout (sidebar, topbar)
    ├── dashboard.html      ← Main dashboard with charts
    ├── add.html            ← Add new activity form
    └── records.html        ← View all records
```

---

## 🚀 How to Run (Step by Step)

### Step 1 — Install Python
Download Python from: https://www.python.org/downloads/
✅ During install, check "Add Python to PATH"

---

### Step 2 — Open Terminal / Command Prompt
- **Windows**: Press `Win + R` → type `cmd` → press Enter
- **Mac/Linux**: Open Terminal app

---

### Step 3 — Go to the project folder
```bash
cd path\to\carbon_monitor
```
Example: `cd C:\Users\Janani\Downloads\carbon_monitor`

---

### Step 4 — Install Flask
```bash
pip install flask
```

---

### Step 5 — Run the application
```bash
python app.py
```

You will see:
```
✅  Carbon Monitor running at: http://127.0.0.1:5000
```

---

### Step 6 — Open in Browser
Go to: **http://127.0.0.1:5000**

---

## 📊 How to Use

| Page | What to do |
|------|-----------|
| Dashboard | See total CO₂, charts, recent activities |
| Add Activity | Log electricity, fuel, transport or waste |
| All Records | View and delete all recorded entries |

---

## ⚙️ Emission Factors Used

| Activity      | Unit   | Factor        |
|---------------|--------|---------------|
| Electricity   | kWh    | 0.82 kg CO₂  |
| Fuel          | Litres | 2.31 kg CO₂  |
| Transport     | km     | 0.21 kg CO₂  |
| Waste         | kg     | 0.50 kg CO₂  |

Formula: **CO₂ = Activity Value × Emission Factor**

---

## 🛑 To Stop the App
Press `Ctrl + C` in the terminal.
