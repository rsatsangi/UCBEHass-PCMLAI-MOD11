# Used Car Price Analysis

This repository contains the work for **Module 11** of the **UC Berkeley Engineering / Berkeley Haas Professional Certificate in Machine Learning and Artificial Intelligence**. The project analyzes used vehicle listing data to identify the factors that influence price and to generate business recommendations for used car dealerships.

## Project Objective

The goal of this analysis is to understand which vehicle features are most strongly associated with higher resale prices. The results can help dealerships make better decisions about:

- which cars to acquire
- how to price inventory
- which vehicle characteristics add value
- what additional data should be collected for future modeling

## Repository Contents

- `CarPriceAnalysis.ipynb` — main notebook containing data cleaning, exploratory analysis, modeling, and conclusions
- `data/` — dataset files used in the analysis
- `images/` — charts and visual assets generated during the project

## Business Understanding

Used car pricing depends on a combination of vehicle condition, technical features, age, mileage, fuel type, and brand perception. A dealership that understands these drivers can improve both acquisition strategy and profit margins.

## Summary of Findings

The analysis suggests that several vehicle characteristics are associated with stronger resale value.

### Higher-value vehicles tend to have:
- **Lower mileage**
- **Newer model year / lower age**
- **More cylinders**
- **Sedan body type**
- **Good condition**
- **Gasoline fuel type**
- **Ford make** within this dataset

### Pricing patterns observed:
- Vehicles with **lower mileage** generally sell for more.
- **Older cars** are expected to have more mileage and usually sell for less.
- Vehicle **condition** plays an important role in preserving resale value.
- Certain makes and configurations appear to hold value better than others.

## Recommendations

Based on the analysis, used car dealers should consider the following actions:

- Focus on acquiring **low-mileage vehicles**, since they typically have higher resale value.
- Adjust pricing expectations for **older vehicles**, which usually have more wear and lower market value.
- Give added attention to cars with features linked to stronger pricing, such as:
  - more cylinders
  - sedan body type
  - good overall condition
  - gasoline fuel type
  - Ford branding in this dataset

## Additional Data to Collect

To improve future analysis and pricing models, it would be useful to collect additional variables such as:

- **Accident history** of the vehicle
- **Dealer acquisition price**, to evaluate profit margins more accurately
- **Reason for sale** from the original owner
- **Buyer income or affordability indicators**, which may affect negotiation behavior

## Tools and Methods

This project was developed using:

- Python
- Jupyter Notebook
- pandas
- NumPy
- matplotlib / visualization tools
- machine learning and regression analysis techniques

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/rsatsangi/UCBEHass-PCMLAI-MOD11.git
   ```
2. Navigate into the project folder:
   ```bash
   cd UCBEHass-PCMLAI-MOD11
   ```
3. Open the notebook:
   ```bash
   jupyter notebook CarPriceAnalysis.ipynb
   ```

## Conclusion

This project shows that used car value is influenced most strongly by mileage, age, condition, and selected vehicle attributes. With better acquisition choices and richer data collection, dealerships can improve pricing accuracy, inventory quality, and overall profitability.
