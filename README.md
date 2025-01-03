## Creating-a-Mutual-Fund-Plan-with-Python

**A data-driven approach to constructing a diversified portfolio of Indian mutual funds optimized for growth and risk mitigation.**

## Project Overview

This project leverages historical stock price data of the Nifty 50 index to identify promising Indian mutual funds for investment. Utilizing Python and popular data science libraries within a Google Colab environment, it performs comprehensive analysis, portfolio construction, and performance evaluation.

**Key Features:**

* **Data Acquisition & Preprocessing:** Imports historical stock data, handles missing values, and prepares the data for analysis.
* **Exploratory Data Analysis (EDA):** Employs interactive Plotly charts to visualize stock price trends and relationships.
* **Portfolio Construction:** Identifies companies with high returns on investment (ROI) and low volatility, calculating optimal investment ratios using inverse volatility weighting.
* **Performance Evaluation & Visualization:**  Compares the risk (volatility) and expected returns of the constructed portfolio against benchmark investment strategies, utilizing intuitive visualizations to highlight performance differences.
* **Investment Projection:** Projects the future value of investments using a compounding interest model, offering insights into potential long-term growth. 

## Methodology

1. **Data Collection:** Historical stock price data for the Nifty 50 index is imported into the Google Colab notebook.
2. **Data Cleaning and Preparation:** Missing values are handled, and the data is transformed into a suitable format for analysis.
3. **Exploratory Data Analysis:** Interactive Plotly charts are used to visualize stock price trends and identify potential investment opportunities.
4. **Portfolio Construction:**
    * Companies with high ROI and low volatility are selected based on predefined criteria.
    * Optimal investment ratios are calculated using inverse volatility weighting to minimize risk.
5. **Performance Evaluation:**
    * The portfolio's risk and expected returns are compared against benchmark investment strategies.
    * Visualizations are generated to highlight performance differences and key insights.
6. **Investment Projection:**
    * A compounding interest model is employed to project the future value of investments over different time horizons.
    * Results are visualized to offer insights into potential long-term growth.

## Technologies Used

* **Python:** The core programming language for data analysis and visualization.
* **Pandas:** A powerful library for data manipulation and analysis.
* **Plotly:** An interactive visualization library for creating dynamic charts.
* **NumPy:** A fundamental library for numerical computations.
* **Google Colab:** A cloud-based platform for running Jupyter notebooks and sharing code.

## Data Source

The project utilizes historical stock price data for the Nifty 50 index, sourced from a publicly available CSV file (`nifty50_closing_prices.csv`).

## Disclaimer

This project is intended for educational and informational purposes only and should not be considered as financial advice. Investment decisions should be made in consultation with a qualified financial advisor and based on individual financial goals and risk tolerance.

## Contributing

Contributions to this project are welcomed! If you have any suggestions, bug fixes, or enhancements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
