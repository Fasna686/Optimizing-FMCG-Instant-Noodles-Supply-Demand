# Optimizing-FMCG-Instant-Noodles-Supply-Demand
**Optimizing Supply &amp; Demand Patterns for FMCG Instant Noodles Business**
### Project Overview:
This project focuses on optimizing the supply and demand patterns for an FMCG company's instant noodles business. The company faced significant mismatches between supply and demand across various warehouses, leading to increased inventory costs and inefficiencies. The project aimed to develop a model that optimizes the supply quantity to each warehouse and analyzes demand patterns across different regions to inform targeted advertising campaigns.

### Insights & Analysis:

1. **Data Distribution:**
   - **Warehouse & Manager IDs:** The distribution is relatively uniform, ensuring balanced product distribution and managerial oversight.
   - **Location Type:** 90.76% of product weight is allocated to rural areas, indicating a focus on these regions.
   - **Warehouse Capacity Size:** Large capacity warehouses dominate, but mid-sized warehouses handle slightly more product weight.
   - **Zones:** Zone 6 has the highest warehouse count, while the North Zone handles the most product weight.
   - **Ownership Type:** 54% of warehouses are company-owned, managing slightly more product weight than rented ones.
   - **Temperature & Electric Supply:** Warehouses with temperature regulation and electric supply handle higher product weights.
   - **Government Checks:** More frequent checks correlate with higher product weights.

2. **Correlations & Patterns:**
   - **Storage Issues & Warehouse Breakdowns:** Both increase with higher product weights.
   - **Transport Issues:** No clear correlation with product weight.
   - **Competitors & Refill Requests:** Higher product weights correspond with more competitors and refill requests.
   - **Flood Impact & Establishment Year:** Flood-prone warehouses have higher median weights, and newer warehouses face fewer storage issues.
   - **Distance from Hub & Number of Workers:** No strong correlation with product weight, and an inverse relationship with productivity per worker.

### Recommendations:

1. **Inventory Optimization:**
   - Implement demand forecasting models to align supply with demand.
   - Use historical data for predicting refill requests.

2. **Warehouse Management:**
   - Improve infrastructure in older warehouses.
   - Invest in temperature regulating machines and electric supply.

3. **Transportation & Logistics:**
   - Optimize transportation strategies based on discrete transport issues.

4. **Targeted Marketing:**
   - Focus on zones with higher demand for advertising campaigns.

5. **Government Compliance:**
   - Ensure adherence to regulations to reduce disruptions.

### Model Interpretation:

The Gradient Boosting model was identified as the most optimal model based on its performance metrics, with a Train and Test R² value of 0.994, indicating high accuracy and robustness. The low RMSE and MAE values further emphasize the model's reliability in making precise predictions. 

### Business Implications:

1. **Improved Decision-Making:** Reliable forecasts lead to better inventory management and strategic planning.
2. **Optimized Resource Allocation:** Accurate predictions enable more efficient use of resources, reducing costs.
3. **Enhanced Customer Experience:** Better demand forecasting leads to tailored marketing and improved customer satisfaction.
4. **Competitive Advantage:** The high-performing model provides a competitive edge.
5. **Cost Efficiency:** Reducing overstock and stockouts improves profitability.

### Conclusion:

The Gradient Boosting model is a valuable asset for the FMCG company, supporting data-driven decisions, enhancing operational efficiency, and driving business growth. Its implementation will lead to more precise supply chain management, targeted marketing strategies, and overall improved business performance.
