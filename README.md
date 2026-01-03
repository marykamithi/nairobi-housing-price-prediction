# Nairobi Housing Price Prediction

A machine learning project to predict rental apartment prices in Nairobi using Linear Regression.

## 📊 Project Overview

This project builds a predictive model to estimate monthly rental prices for apartments in Nairobi based on:
- **Location** (Neighborhood)
- **Size** (Square meters)

**Target Users:** Homebuyers, Real Estate Agents, Property Developers

## 🎯 Success Criteria

- **R² Score:** > 0.70
- **Mean Absolute Error (MAE):** < KSh 15,000
- **Accuracy:** 85% of predictions within ±10% of actual price

## 📁 Dataset

- **Primary Data:** `rent_apts.csv` (~1,850 rental apartments)
- **Features:** Agency, Neighborhood, Price, sq_mtrs, Bedrooms, Bathrooms, Link
- **Source:** Nairobi rental market data

## 🛠️ Technologies

- Python 3.10
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/marykamithi/nairobi-housing-price-prediction.git
   cd nairobi-housing-price-prediction
   ```

2. **Create environment:**
   ```bash
   conda create -n data_analysis python=3.10
   conda activate data_analysis
   ```

3. **Install dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

4. **Run the notebook:**
   ```bash
   jupyter notebook Project_Housing_Price_Prediction.ipynb
   ```

## 📈 Project Structure

```
├── Project_Housing_Price_Prediction.ipynb  # Main analysis notebook
├── rent_apts.csv                           # Primary dataset
├── apartments.csv                          # Secondary dataset
├── Nairobi propertyprices - Sheet1.csv     # Secondary dataset
└── README.md                               # Project documentation
```

## 👤 Author

**Mary Kamithi**
- GitHub: [@marykamithi](https://github.com/marykamithi)
- Email: marykamithi3@gmail.com

## 📝 License

This project is open source and available for educational purposes.
