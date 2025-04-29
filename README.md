
# CourierCast – Interactive Forecasting Dashboard

CourierCast is a data-driven, interactive dashboard designed to forecast the number of courier partners likely to be online on a given day. Using powerful ensemble machine learning models, the system predicts future trends while providing upper and lower confidence bounds for each forecast, helping users gauge the possible range of fluctuations.

## Features

- 📈 **Forecast Visualization**: View daily predictions with upper and lower confidence intervals.
- 📊 **Multiple Chart Types**: Line charts, area plots, and interactive visualizations for better insights.
- 🧠 **Advanced Modeling**: Powered by ensemble machine learning models with low MAE and RMSE.
- 💡 **Intuitive Interface**: User-friendly UI developed using Streamlit for easy navigation and data exploration.

## Model Performance

- **Main Task**:  
  - MAE: 18.16  
  - RMSE: 48.74  

- **Growth Task**:  
  - MAE: 0.23  
  - RMSE: 1.15  

## Sample Forecast Output

| Date       | Predicted Online | Upper Bound | Lower Bound |
|------------|------------------|-------------|-------------|
| 2023-06-01 | 58.61            | 64.48       | 52.75       |
| 2023-06-02 | 58.45            | 64.30       | 52.60       |
| ...        | ...              | ...         | ...         |

## Installation

```bash
pip install -r requirements.txt
streamlit run app.py
```

## License

This project is licensed under the MIT License.
