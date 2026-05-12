# Used Car Price Analysis: What Drives the Price?

## Project Overview
This project explores a dataset of 426K used cars to identify the key factors that influence their market value. The goal is to provide actionable insights for a used car dealership to optimize their inventory acquisition and pricing strategies.

## Key Findings
- **Age & Mileage:** Vehicle age and odometer readings are the primary drivers of depreciation. Cars typically see a significant price drop after 100,000 miles.
- **Brand Equity:** Luxury manufacturers and certain reliable brands (e.g., Toyota, Mercedes-Benz) maintain higher resale values even with higher mileage.
- **Engine & Drivetrain:** Diesel engines and 4WD/AWD configurations command a premium in specific regions.
- **Title Status:** A 'clean' title is the single most important factor for retail readiness; 'salvage' or 'rebuilt' titles reduce value by 30-50%.

## Recommendations for Inventory
1. **Target the "Sweet Spot":** Focus on vehicles 3–6 years old with under 70,000 miles.
2. **Standardize Listings:** Ensure paint color and transmission types are correctly logged, as these influence buyer interest.
3. **Regional Strategy:** Align inventory (e.g., SUVs vs. Sedans) with local demand based on the 'region' and 'state' data points.

## Repository Structure
- `prompt_II.ipynb`: The main Jupyter Notebook containing data cleaning, EDA, and regression modeling.
- `data/`: Contains the `vehicles.csv` (Note: large files should be handled via LFS).
- `images/`: Visualizations and CRISP-DM diagrams.

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install pandas seaborn scikit-learn matplotlib`.
3. Open `prompt_II.ipynb` in Jupyter Lab or VS Code.
