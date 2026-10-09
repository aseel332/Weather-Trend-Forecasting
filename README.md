# Weather Trend Forecasting

A data cleaning, outlier analysis and machine learning project on the **Global Weather Repository** dataset, which has daily weather readings for cities around the world. Built with the Beginner Projects team at the AI Student Collective, UC Davis.

## What's inside

1. **Data cleaning:** fixed country names that appeared in other languages or were misspelled (for example Arabic, Russian and Portuguese spellings of the same country), corrected bad location names, and grouped similar weather conditions into fewer classes.
2. **Outlier detection:** Z-score analysis across temperature, wind, pressure, precipitation, humidity, cloud cover, visibility and UV index, with scatter plots that highlight outliers.
3. **Exploratory analysis:** feature relationships and comparisons across the 10 most-represented countries.
4. **Modeling:**
   - **Logistic Regression** to classify the weather condition from numeric readings, evaluated with accuracy and a confusion matrix.
   - **Lasso Regression** for continuous weather prediction.

## Tech stack

Python, pandas, NumPy, SciPy, scikit-learn, matplotlib, seaborn, Jupyter

## Run it

1. Download `GlobalWeatherRepository.csv` from the [Global Weather Repository](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository) dataset on Kaggle.
2. Put it next to `Libraries.ipynb` and run the notebook top to bottom.
