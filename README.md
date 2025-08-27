# 🧹 Data Cleaning and Preprocessing

## 📁 Dataset Description
This project simulates a real-world dataset with common issues such as:
- Missing values
- Duplicates
- Inconsistent formatting (e.g., gender, country names)
- Irregular date formats
- Improper column naming and data types

The dataset is designed for data cleaning and preprocessing practice using **Python (Pandas)**.

---

## 🗂️ Files Included
| File Name                  | Description                                |
|---------------------------|--------------------------------------------|
| `raw_customer_data.csv`   | Raw dataset with issues                    |
| `cleaned_customer_data.csv` | Cleaned and preprocessed version         |
| `data_cleaning.py`        | Python script used to clean the dataset    |
| `README.md`               | Project summary and documentation          |

---

## 🛠 Cleaning Performed
- ✅ Removed duplicate rows using `drop_duplicates()`
- ✅ Standardized column names (lowercase, underscores)
- ✅ Handled missing values using `fillna()` and `mode()`
- ✅ Standardized text fields like `gender` and `country`
- ✅ Converted `DOB` column to `datetime` format
- ✅ Converted `age` and `customer_id` columns to integer type

---

## 🧰 Tools Used
- Python 3.x
- Pandas
- Google Colab

---

## 📈 Outcome
A clean, structured dataset ready for further data analysis or visualization. This task demonstrates hands-on skills in real-world data preprocessing.

---

## 👩‍💻 Author
**Neha J**  
M.Sc. Statistics (2023–25), University of Calicut  
[GitHub Profile](https://github.com/Neha-analyst-prog)
