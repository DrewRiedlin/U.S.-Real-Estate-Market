# U.S.-Real-Estate-Market
This project analyzes U.S. real estate listings (2016–2023) to identify market trends, price segmentation, and investment opportunities. Using Python (Pandas, NumPy, Matplotlib) for data cleaning and analysis, and Tableau for visualization, the study provides insights to help investors and realtors optimize their real estate decisions.

# Optimizing Real Estate Investments 🏡📊

Project Overview

This project analyzes U.S. real estate listings (2016–2023) to identify market trends, price segmentation, and investment opportunities. Using Python for data cleaning and analysis, and Tableau for visualization, the study provides insights to help investors and realtors optimize their real estate decisions.

Data Source

The dataset includes 2,226,382 real estate listings across the U.S., initially covering all 50 states, Guam, Puerto Rico, the District of Columbia, and New Brunswick.
Listings outside the 50 U.S. states were removed for a more relevant analysis.
Data Cleaning & Preparation
To ensure high-quality insights, the following cleaning steps were performed:

✅ Removed outliers:

  - 22,070 listings below $50,000 (as these are typically not viable real estate investments).

  - Listings with more than 20 bedrooms/bathrooms (e.g., a listing with 830 bathrooms).

  - Properties with 0 bedrooms and 0 bathrooms (to exclude land sales).

  - Listings over 25,000 sq. ft, as they were either data errors or not relevant for typical investors.

✅ Created a price_range column to categorize listings into three price tiers:

  - Low Range: Below $300,000

  - Mid Range: Between $300,000 - $700,000

  - High Range: Above $700,000

Key Insights

📌 Data Refinement for Accurate Decision-Making

   Filtering out misleading or extreme values ensures reliable insights for investors and homebuyers.

📌 Price Trends and Property Features

   How price correlates with property size, number of bedrooms/bathrooms, and other key factors.

📌 Yearly Market Trends (2016–2023)

   Tracking real estate price changes to uncover market fluctuations and investment opportunities.

📌 Price Segmentation for Investor Accessibility

   Categorizing listings into Low, Mid, and High price tiers to provide insights for investors and buyers at any 
   financial level.

Tools & Technologies Used

  - Python (Pandas, NumPy, Matplotlib, Seaborn) – for data cleaning, processing, and exploratory analysis

  - Tableau – for interactive data visualization and storytelling

  - Jupyter Notebook – for scripting and analysis

Contributions

Contributions are welcome! Feel free to fork this repository, submit pull requests, or suggest improvements.

Contact & Links
📧 Drew Riedlin – drew.riedlin@gmail.com
🔗 [View the interactive Tableau story here](https://public.tableau.com/app/profile/andrew.riedlin/viz/USRealEstateListingResearch/USRealEstateListings?publish=yes)
