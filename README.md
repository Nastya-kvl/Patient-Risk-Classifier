# Patient Risk Classifier

A concise medical data analysis project using Python and pandas to identify potential health risks based on patient data.

## 📊 Overview

This project analyzes patient records (age and temperature) and applies custom logic to classify individual risk levels. It's a practical example of conditional logic and row-wise processing using `.apply()` in pandas.

## 🧠 Technologies Used

- Python 3
- pandas
- Google Colab

## 🔍 Features

- Risk classification based on:
  - Age > 60 → `senior`
  - Temperature > 37.5°C → `fever`
- Clean and readable logic
- Functional programming via custom `assess_risk(row)` function
- Tabular processing with `.apply()` for each row

## 🛠 Example Output

| Name   | Age | Temp | Risk         |
|--------|-----|------|--------------|
| Margo  | 30  | 37.8 | fever        |
| Borys  | 62  | 36.7 | senior       |
| Lilit  | 23  | 38.0 | fever        |

## 🚀 Future Improvements

- Extend logic to include blood pressure and blood sugar
- Build a simple UI to interactively test patient data
- Deploy as a microservice or integrate into larger healthcare systems

## 📂 File

- `PatientRisk_Analysis_Nastya.ipynb` — main Jupyter Notebook with full code and logic.

---

Created by **Nastya Kvl**  
Aspiring AI Engineer | Python Developer | Learning by doing 💡
