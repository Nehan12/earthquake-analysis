Earthquake Data Analysis

This project performs Exploratory Data Analysis (EDA) on a global earthquake dataset. The analysis includes data inspection, visualizations, mapping earthquake locations, and examining temporal trends and correlations.

Project Files:

EDA.ipynb - Jupyter Notebook containing EDA code.
earthquakes.csv - CSV file with earthquake data.
earthquake_map.html - Interactive map of earthquake locations.
Dataset Columns:

magnitude: Earthquake magnitude.
depth: Depth of each earthquake (in km).
latitude and longitude: Geographic coordinates.
place: Text description of the location.
time: Date and time of each event.
Analysis Steps:

Data Loading and Inspection: Using pandas to load, inspect, and check for missing values.
Magnitude Distribution: Visualizes the distribution of earthquake magnitudes.
Depth Distribution: Visualizes the distribution of earthquake depths.
Global Location Plot: Maps earthquake locations with Cartopy.
Interactive Map: Folium map with clickable markers for each earthquake.
Time Trend Analysis: Histogram of earthquake occurrences over time.
Correlation Analysis: Heatmap of correlations between numeric variables.
Requirements:

Libraries: pandas, matplotlib, seaborn, cartopy, folium, numpy
Install with: pip install pandas matplotlib seaborn cartopy folium numpy
Running the Analysis:

Clone the repository: git clone https://github.com/yourusername/earthquake-analysis.git
Navigate to the folder: cd earthquake-analysis
Run the Jupyter Notebook: jupyter notebook EDA.ipynb
Execute each cell in the notebook.
Results and Insights:

Magnitude and depth distributions
Earthquake locations mapped globally
Temporal trends of earthquakes
Correlations between numeric variables
