# Business Analytics Portfolio Project

## Overview

This repository showcases a business analytics project designed to demonstrate your analytical capabilities for roles such as Business Analyst, Program Manager, and Data Analyst. It includes a synthetic dataset along with a Jupyter notebook that performs comprehensive exploratory data analysis and builds predictive models.

## Files

- `synthetic_business_data.csv`: A synthetic dataset simulating daily sales and marketing performance for four products across four geographic regions over the course of two years.
- `analysis_notebook.ipynb`: A Jupyter notebook that walks through loading the dataset, performing exploratory data analysis (EDA), visualizing relationships, and constructing predictive models for units sold and customer satisfaction.
- `requirements.txt`: Lists the Python packages required to run the notebook.

## Dataset Description

The dataset contains the following columns:

| Column | Description |
| --- | --- |
| `date` | Date of observation |
| `region` | Geographic region (North, South, East, West) |
| `product` | Product category (Alpha, Beta, Gamma, Delta) |
| `price_per_unit` | Selling price per unit in USD |
| `marketing_spend` | Daily marketing expenditure in USD |
| `units_sold` | Number of units sold |
| `customer_satisfaction` | Customer satisfaction score on a scale of 1 to 5 |

## Getting Started

1. **Clone the repository** (once created) to your local machine using Git:
   ```bash
   git clone https://github.com/<your-username>/business-analytics-portfolio.git
   cd business-analytics-portfolio
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the notebook**:
   You can use Jupyter Notebook or any Jupyter-compatible environment to open `analysis_notebook.ipynb`. Run through the cells to reproduce the analysis and model building process.

## Usage

- Use the dataset and notebook as a template for your own analyses. You can modify the data generation script to simulate different scenarios or add new features.
- The predictive modeling section currently uses linear regression as a baseline. Feel free to experiment with other algorithms like random forests, gradient boosting, or neural networks.
- Add more visualizations or statistical tests to deepen your exploratory analysis.

## Contributing

This project is intended as a personal portfolio example. If you have ideas for improvements or additional analysis, feel free to fork the repository and submit a pull request.

## License

This project is released under the MIT License. Feel free to use, modify, and distribute the contents.


## Contact

For questions or feedback regarding this project, feel free to reach out via GitHub Issues.
