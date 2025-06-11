# Global-Chocolate-Ratings
python exploratory analysis
# World Cocoa Ratings Analysis

I used Python to wrangle and analyze a global chocolate‐bar ratings dataset. Through exploratory visualizations, geospatial mapping, regression, clustering, and time‐series analysis, I uncovered consumer taste patterns and actionable insights for product development and marketing.

## Objective

Discover how cocoa percentage, bean origin, temporal trends, and taste segments influence chocolate bar ratings—and translate those findings into recommendations for chocolate makers and retailers.

## Key Questions

1. **How does cocoa percentage correlate with consumer ratings?**  
2. **What is the trend in average ratings over time (2006–2024)?**  
3. **Which bean origins yield the highest average ratings?**  
4. **Do manufacturer locations affect ratings?**  
5. **Which bean types (e.g., Trinitario, Criollo) deliver the best ratings?**  
6. **Can we segment bars into taste profiles using clustering?**  
7. **Where are the top‐rated chocolate origins located geographically?**

## Data

- **flavors_of_cacao_cleaned.csv** — cleaned chocolate bar reviews from Kaggle  
- **world-countries.json** — GeoJSON outlines for global choropleth mapping  

## Tools

- **Python 3**  
- **Pandas** — data wrangling  
- **NumPy** — numeric operations  
- **Matplotlib & Seaborn** — static visualizations  
- **Folium** — interactive choropleth maps  
- **scikit-learn** — regression and k-means clustering  
- **statsmodels** — time‐series decomposition and stationarity tests  


## Analysis Workflow

1. **Exploratory Visual Analysis** (Achievement 6.2)  
   – Correlation heatmaps, scatterplots, pair plots, boxplots  
2. **Geospatial Mapping** (Achievement 6.3)  
   – Folium choropleth of average ratings by country  
3. **Supervised ML** (Achievement 6.4)  
   – Linear regression of Rating vs. CocoaPercent  
4. **Unsupervised ML** (Achievement 6.5)  
   – k-means clustering to segment taste profiles  
5. **Time Series Analysis** (Achievement 6.6)  
   – Decomposition, stationarity tests, differencing, autocorrelation  

## Key Findings & Recommendations

- **Sweet Spot**: Bars with 60–75% cocoa earn the highest ratings—focus new product lines here.  
- **Origin Matters**: Highlight beans from Madagascar, Ecuador, Ghana in marketing & sourcing.  
- **Stable Ratings**: Average ratings remained around 3.0–3.2 since 2010; innovate to drive growth.  
- **Taste Segments**: Three clusters reveal distinct consumer preferences—use for targeted recommendations.  
- **Geo Insights**: Leverage top-rated regions for premium sourcing; fill gaps in under-sampled markets.

## Data Source & Citation

Tatman, R. (2017). *Chocolate Bar Ratings* [Data set]. Kaggle.  
https://www.kaggle.com/datasets/rtatman/chocolate-bar-ratings

## License

This project is released under the [MIT License](LICENSE).



