# Rental Market Analysis in Guadalajara Metropolitan Area

## Overview
This project explores the rental housing market dynamics in the Guadalajara Metropolitan Area using web scraping and machine learning techniques. The goal is to analyze rental pricing trends, identify key property attributes, and predict rental prices. You can access the paper [here](https://www.researchgate.net/publication/381189642_Exploring_the_Rental_Market_Dynamics_of_the_Guadalajara_Metropolitan_Area).


## Authors
- Cuauhtemoc Guerrero Ramírez
- Diego Ramos García de Alba
- Javier Cerriteño Magaña

## Objectives
- Collect rental data from real estate websites.
- Perform exploratory data analysis (EDA) to clean and preprocess the data.
- Identify key factors influencing rental prices.
- Develop predictive models for rental price estimation.
- Enhance model performance through feature engineering.

## Data Collection
The dataset was created using web scraping techniques to extract property details from real estate websites.

Original Variables:
- Location
- Price
- No. of rooms
- No. of bathrooms
- Area
- Address
- Colony
- Type

Final Variables (including engineered features):
- Location
- Price
- No. of rooms
- No. of bathrooms
- Area, Neighborhood
- Municipality
- Type
- Price per sq meter
- Bathrooms per room
- Price_Category

## Methodology
1. **Web Scraping**: Extracted rental data from multiple websites.
2. **Data Cleaning**: Handled missing values, removed duplicates, and corrected inconsistencies.
3. **Exploratory Data Analysis (EDA)**: Identified key trends and patterns in rental pricing.
4. **Outlier Removal**: Used the interquartile range (IQR) method to remove extreme values.
5. **Feature Engineering**: Encoded categorical data and derived new features.
6. **Predictive Modeling**:
   - Regression models for rental price prediction.

## Tools & Technologies
- **Python** for data processing and analysis.
- **Pandas** and **NumPy** for data manipulation.
- **Matplotlib** and **Seaborn** for data visualization.
- **Scikit-learn** for machine learning models.
  
## Results
- Identified significant features impacting rental pricing.
- Developed predictive models for rental price estimation with improved accuracy.
- Explored the effect of location and property attributes on rental trends.

## Future Work
- Expand data collection to include more listings over time.
- Improve prediction accuracy by experimenting with deep learning models.
- Integrate geospatial analysis for better location-based insights.

## Repository Structure
```
├── data/                  # Raw and processed data
├── notebooks/             # Jupyter Notebooks for EDA and modeling
├── src/                   # Scripts for data processing and modeling
├── paper/                 # Research paper
├── README.md              # Project documentation
```

## Research Paper
The full research paper detailing the methodology and findings can be found in the `paper/` directory:  
**[Download Paper](paper/rental_market_analysis.pdf)**


## How to Run
1. Clone the repository:
   ```bash
   git clone <https://github.com/Daego9Ramos/RentalMarketGDL.git>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook for EDA:
   ```bash
   jupyter notebook EDA_FPA.ipynb
   ```

## License
This project is licensed under the MIT License.

