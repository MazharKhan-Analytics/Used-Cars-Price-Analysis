# 🚗 Used Cars Price Analysis

**Quick Snapshot**
- **Scope:** Scraped used-car listings across major Indian cities  
- **Key finding:** Maruti Suzuki and Hyundai dominate the budget segment  
- **Visuals:** Available in `/dashboard`

---

## 📌 Project Overview

This project analyzes the Indian used-car market as part of my internship project at **Analyticspace**.  
It demonstrates an end-to-end analytics workflow: **web scraping → data cleaning → exploratory data analysis (EDA) → visualization → business recommendations**.

**Objective:**  
Identify price patterns, brand performance, fuel preferences, and provide actionable recommendations for buyers, sellers, and dealerships.

---

## 🛠️ Tech Stack & Skills

- **Web Scraping:** Python (Requests, BeautifulSoup)  
- **Data Cleaning & Analysis:** Python (Pandas, Regex), OpenPyXL  
- **Visualization:** Matplotlib, Seaborn, Power BI  
- **Reproducibility:** Jupyter Notebook, GitHub

- Used-Cars-Price-Analysis/
│── README.md


---

---

## 🔎 Methodology (Thought Process)

1. **Scrape** car listings from Quikr across major cities capturing: `Name`, `Price`, `Kilometers`, `Fuel Type`, `Ownership`, `Location`.  
2. **Clean** prices & kilometers: remove symbols, commas, and normalize text fields like `Fuel Type` and `Ownership`.  
3. **Feature Engineering**:  
   - Extract `Year` and `Brand` from the `Name` field  
   - Compute `Price_Lakhs`  
   - Normalize `Ownership Count`  
4. **EDA**: explore price distributions, depreciation trends, brand-level averages, and regional fuel preferences.  
5. **Translate to business value**: convert raw insights into recommendations for buyers, dealers, and sellers.  

---

## 📊 Visualizations & Key Figures

### Price by Brand
![Price by Brand](dashboard/price_by_brand.jpg)  
_Average price by brand — helps in competitor benchmarking and pricing strategy._

### Fuel Type Distribution by City
![Fuel Type Distribution](dashboard/fuel_type_city.jpg)  
_Shows regional fuel preference, guiding inventory strategy._

### Price Trends by Year
![Price by Year](dashboard/price_by_year.jpg)  
_Depreciation patterns help buyers and sellers understand age–price relationships._

### Affordable Options (≤ ₹3,00,000)
![Cheap Cars](dashboard/cheap_cars.jpg)  
_Highlights inventory for budget-conscious buyers._

---

## 💡 Key Insights & Recommendations

**Insights**
- Budget segment is dominated by **Maruti Suzuki, Hyundai, Tata** with the highest listings under ₹3 Lakhs.  
- **Fuel preferences are city-specific**: Diesel is popular in Delhi & Punjab, while Bangalore & Hyderabad prefer petrol.  
- **Depreciation is steep after 8–10 years**, lowering resale value.  
- **First-owner cars** consistently fetch higher resale prices compared to 2nd/3rd owners.  

**Recommendations**
- **For Buyers:** focus on first-owner cars under 7 years old for best value.  
- **For Dealers:** stock petrol hatchbacks in Bangalore/Hyderabad, diesel SUVs for northern states.  
- **For Sellers:** highlight ownership count & maintenance history to achieve better price.  

---

## ⚙️ How to Reproduce / Run

1. Clone the repo:
```bash
git clone https://github.com/your-username/Used-Cars-Price-Analysis.git
cd Used-Cars-Price-Analysis
Create virtual environment & install:
💡 Use the cleaned dataset Cleaned_Used_Car_Data.xlsx if scraping is blocked.

📈 Business Impact & Next Steps

Impact

Reduced manual analysis by automating collection & cleaning of raw listings.

Dashboards provide fast, data-driven decisions for dealers and buyers.

Recommendations improve inventory allocation and pricing strategy.


Author & Contact
Mazhar Khan 
LinkedIn: www.linkedin.com/in/mazhar-khan-7a52a620a

Email: iammazhar619@gmail.com


