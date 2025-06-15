``markdown
---
title: BMI Calculator
emoji: ⚖️
colorFrom: green
colorTo: blue
sdk: streamlit
app_port: 8501
tags:
- health
- streamlit
- calculator
pinned: false
license: mit
---

# ⚖️ Streamlit BMI Calculator

A simple web application that calculates Body Mass Index (BMI) and classifies weight status according to WHO standards.


## ✨ Features

- **Accurate BMI Calculation**:
  - Weight input in kilograms (kg)
  - Height input in centimeters (cm)
  - Automatic conversion to meters for calculation
- **Weight Classification**:
  - Underweight (<18.5)
  - Normal weight (18.5-24.9)
  - Overweight (25-29.9)
  - Obese (≥30)
- **Visual Feedback**:
  - Color-coded alerts for different weight categories
  - Success/warning/error messages based on results
- **User-Friendly**:
  - Minimal input requirements
  - Clear, instant results

## 🛠️ Technologies

- ![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
- ![Streamlit](https://img.shields.io/badge/Streamlit-1.22.0-FF4B4B)
- ![Pandas](https://img.shields.io/badge/Pandas-1.5.3-150458)
- ![Altair](https://img.shields.io/badge/Altair-4.2.0-42A5F5)

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- pip package manager

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bmi-calculator.git
   cd bmi-calculator
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the App
Start the application with:
```bash
streamlit run bmi_app.py
```

Access the app in your browser at `http://localhost:8501`.

## 📂 Project Structure
```
bmi-calculator/
├── bmi_app.py            # Main application logic
├── requirements.txt      # Python dependencies
├── README.md            # This documentation file
└── .streamlit/          # Configuration folder
    └── config.toml      # Streamlit theme config
```

## 🎮 How to Use
1. Enter your weight in kilograms
2. Enter your height in centimeters
3. Click "Calculate BMI"
4. View your:
   - Calculated BMI (to 2 decimal places)
   - Weight classification with color-coded alert

## 🌡️ BMI Categories
| BMI Range       | Classification | Visual Indicator |
|----------------|---------------|------------------|
| Below 18.5     | Underweight   | ⚠️ Yellow warning |
| 18.5 - 24.9    | Normal weight | ✅ Green success  |
| 25.0 - 29.9    | Overweight    | ⚠️ Yellow warning |
| 30.0 and above | Obese         | ❌ Red error      |

## 🛠️ Future Enhancements
- Add BMI chart visualization
- Include weight tracking over time
- Add metric/imperial unit toggle
- Implement user profiles
- Add health recommendations based on BMI

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ❓ About BMI
Body Mass Index is a simple index of weight-for-height commonly used to classify underweight, overweight, and obesity in adults.

---

**Stay healthy!** 💪
```
