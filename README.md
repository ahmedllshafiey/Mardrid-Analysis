# Madrid Real Estate Data Analysis

## Project Overview
This project focuses on analyzing real estate data from Madrid to uncover insights about property characteristics, pricing trends, and other relevant metrics. The dataset includes information such as property size, number of rooms, bathrooms, prices, and more.

## Objectives
- Clean and preprocess the dataset to ensure data quality.
- Explore key metrics such as property size, number of rooms, and pricing.
- Handle missing and inconsistent data effectively.
- Provide insights into the Madrid real estate market.

## Dataset
The dataset used in this project is stored in `Database/Madrid.csv`. It contains the following key columns:
- `id`: Unique identifier for each property.
- `subtitle`: Represents the city or area of the property.
- `sq_mt_built`: Total built area in square meters.
- `n_rooms`: Number of rooms in the property.
- `n_bathrooms`: Number of bathrooms in the property.
- `rent_price`: Rental price of the property.
- `buy_price`: Purchase price of the property.
- `buy_price_by_area`: Purchase price per square meter.

## Analysis Steps
1. **Data Loading**: Load the dataset using pandas.
2. **Data Cleaning**:
   - Remove columns with all missing values.
   - Handle duplicate entries.
   - Rename columns for better readability.
   - Drop rows with invalid or missing values for critical fields.
3. **Exploratory Data Analysis (EDA)**:
   - Analyze distributions of key metrics like `n_rooms` and `n_bathrooms`.
   - Handle outliers and replace missing values with appropriate defaults.
4. **Insights Generation**:
   - Summarize trends in property prices and sizes.
   - Identify patterns in the number of rooms and bathrooms.

## Tools and Libraries
- **Python**: Core programming language for analysis.
- **Pandas**: Data manipulation and cleaning.
- **NumPy**: Numerical computations.
- **Matplotlib & Seaborn**: Data visualization.
- **Plotly**: Interactive visualizations.

## How to Run
1. Ensure you have Python installed on your system.
2. Install the required libraries using `pip install pandas numpy matplotlib seaborn plotly`.
3. Open the Jupyter Notebook `Madrid.ipynb` and execute the cells sequentially.

## Future Work
- Perform advanced statistical analysis on property prices.
- Build predictive models for estimating property prices.
- Visualize geographic trends in property data.

## Author
Ahmed