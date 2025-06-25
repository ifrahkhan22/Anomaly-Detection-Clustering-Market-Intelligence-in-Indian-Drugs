# IndiaRx-Insights-EDA-of-250K-Indian-Pharmaceutical-Products
Data Cleaning & Enrichment:
The dataset was first cleaned by removing duplicates and standardizing packaging and composition fields. From this, new fields like price_per_unit, num_active_ingredients, and is_combo (combo drug flag) were derived.

Price Analysis:
We visualized the distribution of medicine prices, using log transformation to address skewness, and performed outlier detection using interquartile range (IQR). The presence of pricing anomalies was flagged and quantified.

Composition Trends:
By analyzing the number of active ingredients, we determined that a significant share of products are combination drugs, and created a metric to track their proportion. This is relevant for both therapeutic effectiveness and regulatory scrutiny.

Market Competition:
The project includes a Top 5 manufacturer analysis, exposing market dominance patterns. We also clustered drugs using K-Means based on price and quantity attributes, revealing meaningful product segmentation (e.g., premium, standard, or bulk-pack segments).

Volatility Detection:
The coefficient of variation (CV) was calculated for each drug-strength combination to identify products with high price variability—a potential sign of supply chain inconsistency or unregulated pricing.

📈 Visualizations
Multiple visualizations were created using Matplotlib, including:

Histogram of price per unit (log scale)

Boxplots by dosage form

Bar charts for combo drug share and anomalies by manufacturer

Scatter plots of cluster segments

These visuals provide a rich, interpretable layer to the analysis, and can be recreated interactively in Power BI.
