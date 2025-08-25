# Air Quality Analysis: Exploring Atmospheric Pollutants and Weather Factors - TimeSeries Dataset using LSTM

## 📊 Dataset Description
The dataset (`AP003.csv`) contains **50,400 rows and 23 columns**, representing hourly air quality measurements.  
It includes pollutant concentrations and meteorological parameters:

- **Air Pollutants**: PM2.5, PM10, NO, NO2, NOx, NH3, SO2, CO, Ozone, Benzene, Toluene, Xylene  
- **Weather Factors**: Temperature, Relative Humidity (RH), Wind Speed (WS), Wind Direction (WD), VWS (wind speed) Solar Radiation (SR), Barometric Pressure (BP), Rainfall (RF), Apparent Temperature (AT), etc.  
- **Date Columns**: `From Date`, `To Date`  
- **Target** : Apparent Temperature (AT)
---

## 📒 Jupyter Notebook
The notebook (`notebook.ipynb`) walks through several steps:

1. **Importing Libraries**  
   Uses `pandas`, `matplotlib`, `seaborn`, and `scikit-learn` for data analysis and modelling.

2. **Data Loading & Cleaning**  
   - Reads the dataset `AP003.csv`  
   - Handles missing values  
   - Performs feature selection and data preprocessing  

3. **Exploratory Data Analysis (EDA)**  
   - Statistical summary of pollutants  
   - Trend visualization over time  
   - Correlation heatmaps between pollutants and weather parameters  

4. **Visualization**  
   - Time series plots  
   - Histograms and boxplots  
   - Correlation heatmaps  

5. **Modelling & Evaluation**  
   - Applied **Machine Learning models** (LSTM)  
   - Train-test split and model training  
   - Performance metrics: R², MAE, RMSE  
   - Comparison of different models to evaluate predictive power
   
