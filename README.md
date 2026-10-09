# Air Quality Index (AQI) Prediction using Multiple Linear Regression

## Project Overview
An environmental machine learning regression project designed to predict Delhi's Air Quality Index based on atmospheric feature samples. The objective is to forecast continuous pollution levels and detect significant environmental drivers using statistical regression modeling.

## Key Highlights & Results
- **Model Goodness-of-Fit (R² Score)**: **0.9661 (~96.6% variance explained)** on continuous validation data.
- **Root Mean Squared Error (RMSE)**: ~20.91.
- **Key Driver Identification**: Feature analysis revealed that feature_2 holds the strongest positive correlation with pollution levels.
- **Automated Inference**: Successfully processed 400 unseen testing instances and exported batch predictions to Test_Predictions.csv.

## Technical Stack
- **Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Algorithm**: Multiple Linear Regression (Ordinary Least Squares)
- **Environment**: Jupyter Notebook

## Dataset Description
- Train.csv: 1,600 historical observations containing 5 continuous environmental features and 1 continuous target (AQI).
- Test.csv: 400 unseen sample observations with features only.
- Test_Predictions.csv: Final batch prediction output on unseen test data.

## Project Structure

```text
Air-Quality-Prediction/
├── air_quality_prediction.ipynb
├── Train.csv
├── Test.csv
├── Test_Predictions.csv
├── requirements.txt
├── .gitignore
└── README.md
```
## How to Run Locally

1. Clone this repository:
git clone https://github.com/rutuja-gulme/Air-Quality-Prediction.git
cd Air-Quality-Prediction

2. Install dependencies:
pip install -r requirements.txt

3. Launch Jupyter Notebook and run all cells:
jupyter notebook air_quality_prediction.ipynb

## Business & Environmental Impact
This predictive model can serve as an early warning system for public health authorities, allowing urban planners to forecast dangerous air pollution spikes and implement timely traffic or industrial emissions curbs.