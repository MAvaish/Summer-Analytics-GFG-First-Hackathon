# Summer Analytics 2024 Hackathon: Land Cover Classification

🏆 **Best Score:** 0.41375 (Public LB) | Logistic Regression with NDVI Feature Engineering

## 🔍 Problem Statement
Classify land cover types from noisy NDVI time-series data using **only Logistic Regression**.

## 🛠️ Technical Approach
1. **Data Preprocessing**
   - Wavelet denoising for NDVI signals
   - Class-aware missing value imputation
2. **Feature Engineering**
   - Temporal trends (slope, amplitude)
   - Phenological peak detection
3. **Modeling**
   - ElasticNet-regularized Logistic Regression
   - Time-series cross-validation
