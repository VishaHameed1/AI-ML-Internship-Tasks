
# AI/ML Engineering Internship Tasks - DevelopersHub Corporation

## 📋 Overview
Completed **all 6 tasks** for the AI/ML Engineering Internship at DevelopersHub Corporation.

---

## ✅ Completed Tasks

### Task 1: Iris Dataset - Exploratory Data Analysis
- **Objective**: Load, inspect, and visualize Iris dataset
- **Dataset**: Iris Dataset (seaborn built-in)
- **Skills Used**: Data loading, pandas inspection, matplotlib/seaborn visualization
- **Key Visualizations**: Scatter plots, histograms, box plots
- **Files**: `task1_iris_analysis.ipynb`, `iris_dataset.csv`

### Task 2: Stock Price Prediction (Tesla)
- **Objective**: Predict next day's closing price
- **Dataset**: Yahoo Finance (TSLA - 2024-2026)
- **Models Used**: Linear Regression, Random Forest
- **Best Model**: Linear Regression
- **Results**: R² = 0.90, MAE = $8.87
- **Files**: `task2_stock_prediction.ipynb`, `tesla_stock_data.csv`

### Task 3: Heart Disease Prediction
- **Objective**: Predict heart disease risk from health parameters
- **Dataset**: UCI Heart Disease Dataset
- **Models Used**: Logistic Regression, Decision Tree
- **Best Model**: Logistic Regression
- **Results**: Accuracy = 85.7%, ROC-AUC = 0.89
- **Files**: `task3_heart_disease_prediction.ipynb`, `heart_disease_uci.csv`

### Task 4: General Health Query Chatbot (Prompt Engineering)
- **Objective**: Create chatbot for general health questions using LLM
- **Tools**: Hugging Face Free API, Prompt Engineering
- **Features**: Safety filters, medical advice blocker, emergency detection
- **Example Queries**: Sore throat, paracetamol safety, fever information
- **Files**: `task4_health_chatbot.ipynb`

### Task 5: Mental Health Support Chatbot (Fine-Tuned)
- **Objective**: Empathetic chatbot for stress, anxiety, emotional wellness
- **Model Base**: DistilGPT2 (with empathetic prompt engineering)
- **Features**: Emotion detection, self-care tips, crisis resources
- **Safety**: Emergency keyword detection, crisis helpline integration
- **Files**: `task5_mental_health_chatbot.ipynb`

### Task 6: House Price Prediction
- **Objective**: Predict house prices using property features
- **Dataset**: Housing Prices Dataset (Kaggle)
- **Models Used**: Linear Regression, Ridge, Lasso, Random Forest, Gradient Boosting
- **Best Model**: Gradient Boosting
- **Results**: R² = 0.86, MAE = $28,471
- **Files**: `task6_house_price_prediction.ipynb`, `housing_prices.csv`

---

## 🛠️ Technologies Used

| Category | Libraries |
|----------|-----------|
| Data Processing | pandas, numpy |
| Machine Learning | scikit-learn |
| Visualization | matplotlib, seaborn |
| Stock Data | yfinance |
| Deep Learning | transformers, torch |
| Web/API | requests |

---

## 📁 Project Structure

```
AI-ML-Internship-Tasks/
├── README.md
├── requirements_all.txt
│
├── task1_iris_dataset/
│   ├── task1_iris_analysis.ipynb
│   ├── iris_dataset.csv
│   └── requirements.txt
│
├── task2_stock_prediction/
│   ├── task2_stock_prediction.ipynb
│   ├── tesla_stock_data.csv
│   └── requirements.txt
│
├── task3_heart_disease/
│   ├── task3_heart_disease_prediction.ipynb
│   ├── heart_disease_uci.csv
│   └── requirements.txt
│
├── task4_health_chatbot/
│   ├── task4_health_chatbot.ipynb
│   └── requirements.txt
│
├── task5_mental_health_chatbot/
│   ├── task5_mental_health_chatbot.ipynb
│   └── requirements.txt
│
├── task6_house_price/
│   ├── task6_house_price_prediction.ipynb
│   ├── housing_prices.csv
│   └── requirements.txt
│
└── visualizations/
    ├── iris_visualizations.png
    ├── stock_prediction_results.png
    ├── heart_disease_results.png
    └── house_price_results.png
```

---

## 🚀 How to Run

### 1. Clone Repository
```bash
git clone https://github.com/VishaHameed1/AI-ML-Internship-Tasks.git
cd AI-ML-Internship-Tasks
```

### 2. Create Virtual Environment
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Mac/Linux
python -m venv venv
source venv/bin/activate
```

### 3. Install Requirements
```bash
pip install -r requirements_all.txt
```

### 4. Run Jupyter Notebooks
```bash
jupyter notebook
# Open any task folder and run .ipynb file
```

---

## 📊 Results Summary

| Task | Best Model | Key Metric | Score |
|------|------------|------------|-------|
| Task 2 | Linear Regression | R² Score | 0.90 |
| Task 3 | Logistic Regression | Accuracy | 85.7% |
| Task 6 | Gradient Boosting | R² Score | 0.86 |
| Task 4 | Prompt Engineering | Safety Filters | ✅ |
| Task 5 | Empathetic Responses | Crisis Support | ✅ |
| Task 1 | EDA | Visualizations | ✅ |

---

## 💡 Key Learnings

### Technical Skills
- ✅ Time series forecasting with stock data
- ✅ Binary classification for medical diagnosis
- ✅ Regression modeling for real estate prices
- ✅ Feature importance analysis
- ✅ Model evaluation (MAE, RMSE, R², ROC-AUC)
- ✅ Prompt engineering for LLMs
- ✅ Chatbot development with safety filters
- ✅ Data visualization with matplotlib/seaborn

### Soft Skills
- ✅ Problem-solving with real-world datasets
- ✅ Code documentation and commenting
- ✅ GitHub repository management
- ✅ Project structure organization

---

## ⚠️ Important Notes

1. **Task 4 & 5**: Use free Hugging Face API - no API key required
2. **Task 2**: First run downloads stock data (needs internet)
3. **All tasks**: Run cells sequentially for best results

---

## 👨‍💻 Intern Information

```
Name: Visha Hameed
Position: AI/ML Engineering Intern
Organization: DevelopersHub Corporation
Submission Date: 15th May, 2026
```

---

## 🔗 Links

- **GitHub Repository**: https://github.com/VishaHameed1/AI-ML-Internship-Tasks
- **LinkedIn**: [[Your LinkedIn Profile](https://www.linkedin.com/in/visha-hameed-a23202373)]
- **Portfolio**: [\[Your Portfolio Website\]](https://github.com/VishaHameed1)

---

## 📧 Contact

For any queries regarding this submission:
- Email: [vishahameed111@gmail.com]
- GitHub: @VishaHameed1

---

## 🙏 Acknowledgments

- DevelopersHub Corporation for this internship opportunity
- UCI Machine Learning Repository for Heart Disease dataset
- Yahoo Finance for stock data API
- Hugging Face for free LLM inference

