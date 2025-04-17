# 🛡️ System Threat Forecaster

**System Threat Forecaster** is a machine learning-based application designed to predict the type of threat a computer system might be exposed to, based on historical behavior and system parameters. This tool is intended for cybersecurity research, IT system protection, and security analytics.

---

## 📌 Features

- Preprocesses system log data and threat metadata.
- Utilizes classification algorithms to identify potential threat types.
- Provides visual insights into model performance and system behavior.
- Modular, easy-to-extend architecture with a Jupyter Notebook base for experimentation.

---

## 📁 Dataset

You can access the datasets used for training and testing the model from the links below:

- **[Train Dataset](https://drive.google.com/file/d/1r4gXIw_vvr6t5CBrMDkog9TuTCQAHQBc/view?usp=sharing)**
- **[Test Dataset](https://drive.google.com/file/d/1b4pmIfVm9PNt9TOhSn_EmJk2a2FNg75t/view?usp=sharing)**

Make sure to download these and update the notebook paths accordingly when running locally.

---

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/system-threat-forecaster.git
   cd system-threat-forecaster
   ```

2. **Create a virtual environment and activate it:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required libraries:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Open the notebook:**
   ```bash
   jupyter notebook System_Threat_Forecaster.ipynb
   ```

---

## 🚀 How to Use

1. Load the training and test datasets from the provided links.
2. Execute the notebook cells to preprocess data, train models, and evaluate performance.
3. Review classification reports and visualizations to interpret results.

---

## 📊 Model Performance

- Evaluates multiple classification models.
- Uses accuracy, precision, recall, and F1 score for evaluation.
- Displays confusion matrix and prediction distributions.

---

## 📎 Dependencies

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `xgboost` (optional for additional model testing)

You can install them via:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
```

---
