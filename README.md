# CSFL_project
Here's a detailed and polished `README.md` file for your CSFL project on **Heart Disease Risk Prediction using Fuzzy Logic**:

---

# 🫀 Heart Disease Risk Prediction using Fuzzy Logic

This project is built using **Computational Soft Fuzzy Logic (CSFL)** to estimate the risk of heart disease based on various health parameters. The system takes inputs like age, blood pressure, cholesterol levels, and more, then uses fuzzy logic rules to determine a risk score.

## 🧠 Project Overview

The project uses **Mamdani-type Fuzzy Inference System** to model complex decision-making through linguistic rules. The risk is calculated based on the following input variables:

- Age
- Blood Pressure
- Cholesterol
- Blood Sugar
- LDL (Bad Cholesterol)
- HDL (Good Cholesterol)

## 🧮 Features

- 24 fuzzy logic rules modeled on medical interpretations.
- Graphical representation of input membership functions and output decisions.
- Aggregation of fuzzy rule outputs.
- Final decision using **Centroid Defuzzification** method.

## 📥 Inputs

The user is prompted to enter:
- `Age` (0–100)
- `Blood Pressure` (0–220 mmHg)
- `Cholesterol` (100–250 mg/dL)
- `Blood Sugar` (0–120 mg/dL)
- `LDL` (Bad cholesterol, 0–190 mg/dL)
- `HDL` (Good cholesterol, 0–70 mg/dL)

## 📤 Output

- A **numerical risk score** between 0 and 45.
- **Risk Level** graph using fuzzy membership functions.
- Graphs showing the contribution of each rule and the aggregated output.

## 🧰 Technologies Used

- Python
- [scikit-fuzzy (`skfuzzy`)](https://github.com/scikit-fuzzy/scikit-fuzzy)
- NumPy
- Matplotlib

## 📊 Visuals

The project generates:
- Fuzzy membership graphs for all input variables.
- Rule-wise output contribution plots.
- Aggregated fuzzified risk output.
- Defuzzified result visual using the centroid method.

## 🚀 How to Run

1. **Install dependencies**  
   Run this in your terminal or command prompt:
   ```bash
   pip install numpy matplotlib scikit-fuzzy
   ```

2. **Run the script**
   ```bash
   python heart_disease_fuzzy.py
   ```

3. **Enter input values** when prompted.

4. **View the results** via terminal and pop-up graphs.

## 📈 Example Output

```text
Enter your health data to Calculate the Risk of Heart Disease :-

Age: 60
Blood pressure: 150
Cholesterol: 220
Blood sugar: 90
LDL (Good cholesterol): 140
HDL (Bad cholesterol): 35

Coroner Heart Diagnosis: 32.67
```

## 📄 License

This project is part of a CSFL coursework and is open for academic reference.  
Feel free to use or modify it for non-commercial, educational purposes.

---
