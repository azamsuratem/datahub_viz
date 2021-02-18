# Visualizing data from DataHub.io using Matplotlib and Seaborn
A Jupyter Notebook using Python 3 environment on visualizing selected data that are published in the open data repository DataHub.io

<b>REMINDER:</b> If this notebook cannot be loaded via this GitHub platform, download it and view from your local machine via Anaconda's Jupyter Notebook or Jupyter Lab.
<br><i>Alternatively, you can view this notebook online by copying the URL/link to this notebook from this GitHub platform and paste it in this online viewer: https://nbviewer.jupyter.org/</i>

## Table of Contents
1. Data Extraction from DataHub.io
<br><i>Note: No data files required to be downloaded to run this notebook in your local machine since this notebook extract data directly using the DataHub.io URL/link</i>
2. Showing missing values in the extracted data using `msno.matrix()`
3. Overview of the data structure using Pandas `.head()`, `.tail()`, and `.info()`
4. Dataframes of Statistics Summary
5. Seaborn `pairplot` - overview of the data distributions
6. Seaborn `lineplot` - time series plots
7. Seaborn `heatmap` - showing patterns of the data, and correlation heatmap
8. Seaborn `boxplot` - illustrating outliers in the extracted data
9. Enhanced `lineplot` - time series plots with horizontal lines of descriptive statistics
10. Decomposition plots - EDA for time series forecasting

## Data Source
Data are obtained and extracted from the data reposiotry DataHub.io
- `Price_Gold` : [Gold Prices dataset](https://datahub.io/core/gold-prices)
- `Price_NaturalGas` : [Natural Gas Prices dataset](https://datahub.io/core/natural-gas)
- `CO2_Level` : [CO2 PPM - Trends in Atmospheric Carbon Dioxide dataset](https://datahub.io/core/co2-ppm-daily)
- `Mean_TempAnomalies` : [Global Temperature Time Series dataset](https://datahub.io/core/global-temp)

## Notebook References
This notebook is made possible thanks to them for source codes and visualization ideas:
- <b>Data Visualization Analysis</b> by `@kshitijmohan` in Kaggle.com | [Link to the notebook entry](https://www.kaggle.com/kshitijmohan/data-visualization-analysis)
- <b>Basic of Statistical Viz: Plotly & Seaborn</b> by `@subinium` in Kaggle.com | [Link to the notebook entry](https://www.kaggle.com/subinium/basic-of-statistical-viz-plotly-seaborn)
- <b>Intro to Time Series Forecasting</b> by `@iamleonie` in Kaggle.com | [Link to the notebook entry](https://www.kaggle.com/iamleonie/intro-to-time-series-forecasting)
