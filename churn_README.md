# 📊 Customer Churn Analysis
### Big Data · PySpark · Decision Tree Classifier

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python)
![PySpark](https://img.shields.io/badge/PySpark-3.4.1-orange?style=flat-square&logo=apache-spark)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Google_Colab-yellow?style=flat-square)

> **Coursera Project** · Niloofar Mastali · 2024

---

## 📌 Overview

This project analyzes **customer churn behavior** using Big Data tools. A **Decision Tree Classifier** is trained on customer data to predict which customers are likely to leave, helping businesses take proactive retention actions.

---

## 🎯 Key Features

- ⚡ **PySpark** for scalable big data processing
- 🌳 **Decision Tree Classifier** with hyperparameter tuning
- 🔍 **Feature Importance** analysis
- 📊 Interactive visualizations with Plotly & Matplotlib
- 🔧 Full ML pipeline: preprocessing → training → evaluation

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| PySpark 3.4.1 | Big data processing & ML |
| Pandas | Data manipulation |
| Matplotlib | Visualization |
| Plotly | Interactive charts |
| Google Colab | Cloud execution |

---

## 📁 Project Structure

```
customer-churn-analysis/
│
├── Colab_Customer_Churn.ipynb    # Main Jupyter Notebook
├── README.md                      # This file
└── LICENSE                        # MIT License
```

---

## 🚀 Quick Start

### Run in Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)

Upload the notebook and run all cells.

### Install Dependencies
```bash
pip install pyspark==3.4.1
pip install numpy==1.26.4
pip install plotly
```

---

## 🔄 ML Pipeline

```
Raw Data → Preprocessing → Feature Engineering → Decision Tree → Hyperparameter Tuning → Evaluation → Feature Importance
```

**Steps:**
1. **Data Loading** — Load customer dataset with SparkSession
2. **Preprocessing** — Handle missing values with Imputer, encode categorical features
3. **Feature Engineering** — VectorAssembler + StandardScaler
4. **Model Training** — Decision Tree Classifier
5. **Hyperparameter Tuning** — Find optimal `maxDepth`
6. **Evaluation** — Train vs Test accuracy comparison
7. **Feature Importance** — Identify key churn factors

---

## ⚠️ Disclaimer

This project is for **educational purposes only** as part of a Coursera course.

---

## 👩‍💻 Author

**Niloofar Mastali**
M.Sc. Computer Software Engineering (ML & AI)

📧 niloofar2020@gmail.com
🌍 Wien, Austria
🌐 [niloomastali.github.io](https://niloomastali.github.io)

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

*⭐ If you found this helpful, please give it a star!*
