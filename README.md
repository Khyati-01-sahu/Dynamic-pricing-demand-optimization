# Dynamic-pricing-demand-optimization

# Dynamic Pricing & Demand Optimization for E-Commerce

This project builds a data-driven dynamic pricing engine that predicts demand at different price levels and optimizes product prices to maximize revenue. The system uses historical sales data, price sensitivity, and demand forecasting models to support intelligent pricing decisions.

---

## 📌 Business Problem
E-commerce platforms must constantly adjust prices to balance demand, competition, and profitability. Static pricing leads to lost revenue and poor inventory utilization. This project uses machine learning to model price elasticity and forecast demand, enabling dynamic, revenue-optimized pricing.

---

## 📊 Dataset
The dataset contains product-level historical data including:
- Date  
- Product ID  
- Price  
- Units Sold  
- Promotions  
- Seasonality indicators  

---

## ⚙️ Approach
1. Data preprocessing and cleaning  
2. Feature engineering (price, discounts, seasonality, trends)  
3. Demand modeling using regression  
4. Price elasticity estimation  
5. Revenue simulation across price points  
6. Optimal price selection for revenue maximization  

---

## 📈 Results
The model estimates how demand changes with price and identifies the optimal price point that maximizes revenue while maintaining healthy demand.

---

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 🚀 How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
python dynamic_pricing.py
