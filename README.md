# Airbnb-EDA-Insights
## Dataset Description
The dataset (`airbnb_data.xlsx`) contains Airbnb listings with 26 features, including:
- `id`, `host id`: Unique identifiers for listings and hosts
- `neighbourhood group`, `neighbourhood`: Location details (e.g., Manhattan, Brooklyn)
- `price`, `service fee`: Financial details
- `number of reviews`, `review rate number`: Guest feedback metrics
- `availability 365`: Number of days the listing is available per year
- `host_identity_verified`: Whether the host is verified or unconfirmed

The dataset includes listings from various neighborhoods in the United States, with some missing values (e.g., in `NAME`, `license`).

## Challenges Faced
- **Data Cleaning**: The dataset had missing values (e.g., `NaN` in `NAME` and `license`) and inconsistent formats (e.g., `service fee` with a `$` symbol), which required preprocessing before analysis.
- **File Format**: The original notebook used a CSV file (`airbnb_data.csv`), but the uploaded dataset is in Excel format (`airbnb_data.xlsx`), requiring a code adjustment.
- **Weak Correlations**: The weak correlations between price and other factors made it challenging to draw strong conclusions about pricing drivers.

- ## Future Work
- **Deeper Analysis**: Explore additional factors like `room type` or `minimum nights` to understand their impact on pricing and occupancy.
- **Predictive Modeling**: Build a machine learning model to predict listing prices based on features like location, reviews, and availability.
- **Geospatial Visualization**: Create maps to visualize the distribution of listings and prices across neighborhoods using libraries like Folium or Plotly.
