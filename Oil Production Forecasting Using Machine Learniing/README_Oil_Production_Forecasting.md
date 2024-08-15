
# Oil Production Forecasting Using Machine Learning

## Overview
This project focuses on forecasting oil production in the Volve oil field using advanced machine learning techniques. By analyzing historical data from well operations, the project builds predictive models that can assist oil field managers in making data-driven decisions to optimize production efficiency and reduce downtime.

The project utilizes historical production data, including oil, gas, and water volumes, downhole pressures, choke sizes, and other key operational parameters. The goal is to provide actionable insights and improve production forecasting accuracy.

## Key Features
- **Data-Driven Insights**: Uses real-world production data from the Volve oil field to forecast oil production with high accuracy.
- **Comprehensive Data Handling**: Preprocessing techniques to manage missing data, explore correlations, and engineer features from time-series data.
- **Machine Learning Models**: Applied regression models (such as Random Forest, Gradient Boosting, etc.) for time-series forecasting.
- **Visualizations**: Data visualizations to highlight trends, production anomalies, and model performance.

## Motivation
Effective oil production forecasting is critical for optimizing resource management and reducing operational risks. This project aims to help oil companies accurately predict production rates, thereby improving operational planning and reducing costs.

## Tech Stack
- **Python**: Data manipulation and machine learning using libraries like `pandas`, `numpy`, `scikit-learn`, and `matplotlib`.
- **Machine Learning**: Regression techniques for continuous data forecasting.
- **Data Visualization**: Visualized production trends and model results using `matplotlib`.

## Data
The dataset contains daily and monthly production data for various wells in the Volve field, including:
- Production volumes for oil, gas, and water
- Well characteristics (e.g., bore code, well type)
- Operational parameters (e.g., downhole pressure, choke size, on-stream hours)

## Results
The model successfully forecasts oil production with a high degree of accuracy, providing valuable insights for production planning. These forecasts can help in scheduling maintenance, optimizing well operations, and enhancing resource allocation.

## How to Run the Project
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/oil-production-forecasting.git
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook and run the cells to see the data analysis and modeling steps:
   ```
   jupyter notebook Oil_Production_Forecasting.ipynb
   ```

## Future Work
- **Model Refinement**: Experiment with more sophisticated models like LSTM or ARIMA for better time-series forecasting.
- **Deployment**: Deploy the forecasting model as a web app to allow users to input parameters and get real-time predictions.

## Contributors
- Mahammad Salman Shaik
- Akram Mohammad
- Imtiyaz Ali Syed
- Faisal Malik Mohammed

## Contact
For any questions or feedback, please contact [Mahammad Salman Shaik](mailto:youremail@example.com).
