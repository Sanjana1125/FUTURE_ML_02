# FUTURE_ML_02 — AI-Powered Sales Forecasting Dashboard

## 🎯 Project Overview
This repository contains **Task 2** of my **Machine Learning Internship** with *Future Interns*.  
I developed an **Customer Churn Prediction Model** to predict which costumers are likely to leave a service.


### 1. **Documentation** 📄
- `FINAL_SUMMARY.md` - Complete project overview
- `PROJECT_REVIEW.md` - Detailed code review
- `IMPLEMENTATION_GUIDE.md` - Step-by-step guide
- `README.md` - This file


### 2. **Code Files** 💻
- `churn_prediction_complete.py` - Full analysis script (Python)
- `Churn_Prediction_Complete.ipynb` - Jupyter Notebook version
- `streamlit_app.py` - Interactive web application
- `requirements.txt` - Python dependencies

### 3. **Visualizations** 📊
- `eda_comprehensive.png` - 12-panel data exploration
- `model_comparison.png` - Model performance charts
- `feature_importance.png` - Top churn drivers
- `risk_segmentation.png` - Customer risk analysis

### 4. **Model Files** 🤖
- `best_churn_model_random_forest.pkl` - Trained model (47 MB)
- `model_feature_info.pkl` - Feature metadata

### 5. **Presentation Materials** 🎤
- `Churn_Prediction_Report.pdf` - 20-page comprehensive report
- `Churn_Prediction_Presentation.pptx` - 16-slide PowerPoint deck

## 🚀 Quick Start Guide

### Option 1: Run the Complete Analysis

```bash
# Install dependencies
pip install pandas numpy scikit-learn xgboost matplotlib seaborn joblib

# Run the analysis
python churn_prediction_complete.py
```

**What it does:**
- Loads and explores the data
- Trains 3 ML models (Logistic Regression, Random Forest, XGBoost)
- Generates all visualizations
- Saves the best model
- Outputs business insights

**Time:** 2-5 minutes  
**Output:** 4 PNG files + 2 model files

---

### Option 2: Run the Jupyter Notebook

```bash
# Install Jupyter
pip install jupyter

# Launch notebook
jupyter notebook Churn_Prediction_Complete.ipynb
```

**What it does:**
- Interactive cell-by-cell execution
- See outputs and visualizations inline
- Modify and experiment with code
- Perfect for exploration and learning

---

### Option 3: Launch the Streamlit Web App 🌐

```bash
# Install Streamlit and dependencies
pip install -r requirements.txt

# Launch the app
streamlit run streamlit_app.py
```

**What it does:**
- Opens interactive dashboard in your browser
- Explore data with interactive charts
- Make real-time churn predictions
- View business insights and recommendations
- Professional UI for demonstrations

**Access:** Opens at `http://localhost:8501`

**Features:**
- 📊 **Home Page:** Project overview and key metrics
- 📈 **Data Exploration:** Interactive visualizations
- 🤖 **Model Performance:** Compare all 3 models
- 🎯 **Risk Segmentation:** Analyze customer risk tiers
- 🔮 **Make Prediction:** Predict churn for new customers
- 💡 **Business Insights:** Strategic recommendations

---

### Option 4: View the Presentation

**PowerPoint (Recommended):**
1. Open `Churn_Prediction_Presentation.pptx` in PowerPoint
2. 16 slides covering the complete project
3. Ready for presentation

**PDF Report:**
1. Open `Churn_Prediction_Report.pdf`
2. 20-page comprehensive report
3. All visualizations embedded
4. Business insights and recommendations

