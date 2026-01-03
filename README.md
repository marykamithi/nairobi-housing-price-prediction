# Housing Price Prediction for Nairobi, Kenya

A data-driven machine learning project to predict fair rental apartment prices in Nairobi based on location and house size.

## 🎯 Project Goal

**Problem**: Buyers in Nairobi cannot estimate fair housing prices, leading to overpaying and uncertainty.

**Solution**: Build a Linear Regression model that predicts apartment rental prices with >70% accuracy.

**Impact**: Save buyers KSh 5M-60M per property through data-driven price estimation.

## 📊 Dataset

- **Source**: Rental apartment listings (rent_apts.csv)
- **Records**: ~1,850 apartments
- **Target**: Monthly rental price (KSh)
- **Features**: Neighborhood location, House size (sqm)
- **Market**: Nairobi, Kenya only

## 📈 Success Criteria

| Metric | Target |
|--------|--------|
| R² Score | > 0.70 |
| Mean Absolute Error | < KSh 15,000 |
| Prediction Accuracy | > 85% within 10% |
| Model Generalization | No overfitting |

## 🏗️ Project Structure

```
├── Kenya_House_Price_Analysis.ipynb    # Main analysis notebook
├── Housing_Price_Prediction_Nairobi.ipynb  # Additional analysis
├── rent_apts.csv                       # Rental data
├── apartments.csv                      # Apartment data
├── Nairobi propertyprices.csv         # Property sale data
├── README.md                           # This file
├── PROJECT_FOUNDATION.md               # Foundation documentation
└── .gitignore                          # Git ignore file
```

## 🚀 Getting Started

### 1. Environment Setup
```bash
# Create conda environment
conda create -n data_analysis python=3.10 pandas numpy matplotlib seaborn scikit-learn jupyter -y

# Activate environment
conda activate data_analysis

# Launch Jupyter
jupyter notebook
```

### 2. View the Notebook
Open `Kenya_House_Price_Analysis.ipynb` in Jupyter and follow the sections:
- **Section 1**: Project Foundation (COMPLETED ✓)
- **Section 2**: Data Exploration
- **Section 3**: Data Preprocessing
- **Section 4**: Model Training
- **Section 5**: Model Evaluation

## 📝 Sections

### ✅ COMPLETED

#### Section 1: Project Foundation
- 1.1 Clear Problem Statement
- 1.2 Business Impact
- 1.3 Target Users & Personas
- 1.4 Success Criteria
- 1.5 Project Scope
- 1.6 Project Hypothesis

### 🔄 IN PROGRESS

#### Section 2: Data Understanding (Next)
- Load and inspect datasets
- Exploratory Data Analysis (EDA)
- Understand distributions

#### Section 3: Data Preprocessing
- Clean data
- Handle missing values
- Feature encoding

#### Section 4: Model Training
- Train Linear Regression
- Extract coefficients

#### Section 5: Model Evaluation
- Calculate metrics (R², MAE, RMSE)
- Create visualizations
- Generate insights

## 🔧 Technologies Used

- **Python 3.10**
- **Pandas**: Data manipulation
- **NumPy**: Numerical computing
- **Scikit-learn**: Machine learning
- **Matplotlib/Seaborn**: Visualization
- **Jupyter**: Interactive notebooks
- **Git**: Version control

## 📌 Key Features

✅ **Data-Driven**: Based on ~1,850 real apartment listings  
✅ **Interpretable**: Linear Regression coefficients explain price drivers  
✅ **Validated**: Proper train-test split with performance metrics  
✅ **Documented**: Complete analysis with explanations  
✅ **Version Controlled**: All changes tracked in Git  

## 💡 Business Value

- **For Buyers**: Instant, objective price estimates (KSh ±15,000 accuracy)
- **For Sellers**: Know competitive market prices
- **For Agents**: 5-minute market analysis vs 2-hour manual research
- **For Investors**: Data-driven property evaluation

## 📊 Expected Outcomes

After completing this project, we will have:
1. ✅ Clean, validated dataset
2. ✅ Trained Linear Regression model
3. ✅ Model evaluation metrics
4. ✅ Location & size price impact analysis
5. ✅ Production-ready predictions
6. ✅ Complete documentation

## 🔗 GitHub Repository

Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/housing-price-prediction.git
cd housing-price-prediction
```

View commit history:
```bash
git log --oneline
```

## 👤 Team

- **Project Lead**: Mary K
- **Email**: maryk@example.com

## 📄 License

This project is open source and available under the MIT License.

## 📞 Questions?

Review the `PROJECT_FOUNDATION.md` for detailed background on:
- Problem statement with examples
- Business impact calculations
- Success criteria explanations
- Target user personas

---

**Status**: 🟡 In Progress (Step 1/5 Complete)
**Last Updated**: January 3, 2026
