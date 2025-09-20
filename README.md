# Used Car Pricing Analysis

This project analyzes a Kaggle dataset of used car listings to answer a simple but important question:  
**What drives the resale price of a car?**

The work follows the **CRISP-DM process**: business understanding, data preparation, visualization, modeling, and deployment of insights.

---

## Key Highlights
- **Condition is king:** cars in *fair* condition sell for ~80% less than *excellent* cars; *like new* vehicles command ~30% more.  
- **Titles matter:** *salvage* titles reduce value by ~40%.  
- **Year & mileage:** newer models add ~30% more value; every extra 10k miles cuts price modestly.  
- **Brand & fuel:** premium brands (Audi, BMW, Silverado) and diesels resell for more; economy brands trail behind.  
- **Region:** Boston, Knoxville, and Grand Rapids fetch higher resale prices, while LA and South Florida trend lower.  

---

## Recommendations for Dealers
- **Buy smart:** focus on clean titles, newer models, premium brands, and diesels.  
- **Be cautious:** only purchase salvage/fair vehicles if the discount covers the value drop.  
- **Recondition wisely:** upgrading from *good* → *excellent* often pays off.  
- **Pricing strategy:** start with model predictions, then adjust for condition, title, fuel, and location.  

---

## Deliverables
- 📓 [Full Jupyter Notebook with code, models, and dealer-focused recommendations](used_car_pricing_analysis.ipynb)  
- 📊 Visualizations showing trends in condition, brand, year, mileage, and region.  
- 📝 Deployment section written in plain English for dealership decision-makers.  

---

## Tech Stack
- Python (pandas, numpy, scikit-learn, matplotlib, seaborn)  
- Jupyter Notebook  
- CRISP-DM workflow
