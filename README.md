# Anomaly Detection, Clustering & Market Intelligence in Indian Drugs

DESCRIPTION:


A comprehensive exploratory data analysis (EDA) and clustering project on over 250,000 pharmaceutical products marketed in India. This project xomines Python-based analysis with a Power BI dashboard to deliver insights into medicine pricing, formulation trends, market concentration, and product segmentation.


✅ Cleaned and enhanced for analysis: derived fields like `price_per_unit`, `is_combo`, `log_price`, `CV`, `clusters`, and 'anomaly flags'.


 
🔍IMPORTANT TAKEAWAYS:

-📈Price Normalization: regardless of pack size, price-per-unit column generated enables equitable comparisons between products.

-💊The Combo Drug Flag is used to identify complicated formulations that contain more than one active component.

-🧰The price variation by dose form is confirmed to be significant by the ANOVA + Tukey test.

-⚠️Volatility Detection: Inconsistent medicine prices are flagged by the Coefficient of Variation (CV).

-🚨Extreme outliers within drug-strength groups are flagged by the Z-score.

-🏭Clustering: K-Means classifies products according on formulation count, pack size, and price.

-🏭Top Manufacturers: Pie and bar charts show market dominance trends.



📌TOOLS USED:

- Python Libraries: pandas, numpy, matplotlib, scikit-learn, statsmodels, matplotlib
  
- Statistical Techniques: ANOVA, Tukey HSD, Coefficient of Variation (CV), Z-Score
  
- Machine Learning: K-Means Clustering
  
- 📊Visualization: Power BI

*After running the script you will find three main output files in your working directory :
                                                                                                                          
'pharma_enriched_clean.xlsx' -  Cleaned and enriched dataset with additional fields like `price_per_unit`, `is_combo`, `logprice`, `z_price`, `cluster` 

`high_cv_drugs.xlsx`         -  List of drug-strength combinations with high Coefficient of Variation (CV), signaling price volatility  

`price_anomalies.xlsx`       -  Products flagged as price outliers using Z-score filtering within their ingredient-strength group                       



This project provides stakeholders with:

- 🧾Pricing intelligence for product benchmarking.
  
- 📊 Supplier analysis to identify key manufacturers
  
- ✅ Market segmentation to inform business strategy
  
- 🏢 Data-driven decisions for compliance and procurement teams

 

  Feel free to share your views.

  Let's get connected : https://www.linkedin.com/in/ifrah-khan-8873072b5/
