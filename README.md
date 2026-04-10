# Hotel Booking Cancellation Prediction

## Objective
The objective of this project is to predict whether a hotel booking will be canceled or not using machine learning techniques, with a focus on feature engineering and feature selection.

## Dataset
- Hotel Booking Dataset  
- Target Variable: is_canceled  

## Approach

### 1. Baseline Model
- Applied Random Forest on raw features to establish baseline performance.

### 2. Data Preprocessing
- Handled missing values  
- Encoded categorical variables  
- Scaled numerical features where required  

### 3. Feature Engineering
Created new meaningful features such as:
- total_nights  
- price_per_person  
- special_requests_rate  
- interaction features  

### 4. Feature Selection
Used multiple methods:
- Random Forest Feature Importance  
- Mutual Information  
- Permutation Importance  
- Chi-square Test  

Final features were selected based on overlap across methods.

### 5. Final Model
- Trained Random Forest model using selected features  
- Evaluated using Accuracy and ROC-AUC  

## Key Insights
- Features like lead_time and adr are highly important  
- Feature engineering improved model performance  
- Feature selection helped reduce noise and improve model stability  

## How to Run
1. Install dependencies:
   pip install -r requirements.txt  

2. Open and run the notebook:
   FeatureEngineering_Capstone.ipynb  

## Files in Repository
- FeatureEngineering_Capstone.ipynb → Full implementation  
- Report.pdf → Detailed report  
- requirements.txt → Required libraries  

## Conclusion
This project demonstrates the importance of feature engineering and feature selection in improving machine learning model performance, especially for structured datasets.
