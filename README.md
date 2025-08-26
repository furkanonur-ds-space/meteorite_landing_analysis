# Meteorite Data Analysis

This project is a data analysis of public meteorite landing data from NASA, using Python and Jupyter Notebook. The project aims to clean, analyze, and visualize the data, including plotting meteorite landing locations on an interactive world map.

### Dataset
The "Meteorite Landings" dataset provided by Kaggle was used for this analysis. The dataset contains information about meteorites from around the world, including their name, mass, year of fall, geographical location, and class.

### Analysis & Findings

The following steps were performed, leading to several key findings:

1.  **Data Exploration:** The first 5 rows of the dataset were examined, data types were checked, and a basic statistical summary was generated.
    * The heaviest meteorite in the dataset was found to have a mass of **60,000,000 grams**.
    * The oldest recorded meteorite fall dates back to **301 AD**.

2.  **Data Cleaning & Preparation:** Before the analysis, missing data in the `mass` and geographical columns were handled, and the mass unit was converted from grams to kilograms.

3.  **Data Visualization:**
    * **Mass Distribution:** A histogram was created to show the mass distribution of smaller meteorites.
    * **Location Map:** The `Folium` library was used to visualize meteorite landing locations on an interactive world map. Each point on the map is sized according to the meteorite's mass.

### Tools Used
* **Python:** The primary language for data analysis and processing.
* **Jupyter Notebook:** An interactive environment for step-by-step analysis and reporting.
* **Pandas:** The library used for data manipulation and analysis.
* **Matplotlib:** The library used for data visualization.
* **Folium:** The library used to create the interactive map of meteorite landings.

### Project Files
* `meteorite_landing_analysis.ipynb`: Contains all the project code and the analysis report.
* `data/`: The folder containing the raw and processed data.
    * `meteorite-landings.csv`: The original dataset.
    * `updated_meteorite-landings.csv`: The cleaned and transformed dataset.
* `meteor_map.html`: The interactive map output generated with Folium.
