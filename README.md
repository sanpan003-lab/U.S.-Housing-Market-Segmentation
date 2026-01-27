# U.S.-Housing-Market-Segmentation
U.S. Housing Market: Identifying Affordability & Growth "DNAs"

Project Overview
This project moves beyond simple price tracking by using Unsupervised Machine Learning (K-Means Clustering) to segment 100 major U.S. cities. By analyzing the relationship between Median Household Income and 5-Year Home Value Growth, I identified distinct market personas that help predict where housing is becoming unsustainable.

The Approach
Feature Selection: I focused on the 'Affordability Ratio' (Price-to-Income) and '5-Year Growth' to capture both current cost and market momentum.

Data Scaling: I used StandardScaler to ensure the clustering algorithm treated both variables with equal weight.

Clustering: I implemented K-Means to categorize cities into three actionable groups.

The Results
🚀 The Rocket Ships: High-momentum cities with rapid appreciation (e.g., San Diego).

🔒 The Elite Citadels: High-cost, established markets where prices are decoupled from local incomes (e.g., NYC).

🏠 The Steady Anchors: Balanced markets where growth and affordability remain in sync (e.g., Chicago).

Conclusion
This analysis demonstrates that a city's "Market DNA" is a better indicator of future stability than its price tag alone. It’s a powerful tool for identifying investment opportunities or housing policy needs.

