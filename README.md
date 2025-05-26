# Python_and_research
Projects where programming tools and machine learning are applied, focused on agricultural research and ecology

# 1. Soil_use_frequencies.
## EXPLORATORY DATA ANALYSIS. Erste Bodenzustandserhebung Landwirtschaft – Kerndatensatz.
In this notebook, we are going to study the frequencies of the types of soils we have in each kind of land use:
Land use at time of sampling (A=cropland, G=grassland since at least 5 years, SO=special permanent crops) Main soil type (German soil classification) following KA5



# 2. TOC_soil_type.
## EXPLORATORY DATA ANALYSIS. Erste Bodenzustandserhebung Landwirtschaft – Kerndatensatz.

To extract data for German soils and analyze their water content, bulk density, TOC (Total Organic Carbon), and TN (Total Nitrogen) using descriptive statistics only, in order to describe them. Workflow:

- Load the SITE and LABORATORY datasets.
- Select the variables PointID, coordinates, land use, main soil type, and specific soil subtype from the SITE dataset.
- Merge this dataframe with the LABORATORY dataframe using the attributes TOC, TN, bulk density, and water content from the LABORATORY dataset.
- Perform Exploratory Data Analysis (EDA): Number of observations of each kind of soil TOC by soil type Scatter plot of TOC within the most common soil according to water content and bulk density (it can be done with each kind of soil). 3D plot of TOC in the most common soil, water content, and bulk density.
- Modeling: Try regression models to predict the amount of TOC in cambisol based on its water content and bulk density.
- GIS Visualization: Map the soil with the highest TOC values.
- Conclusions



# 3. Soil Organic Carbon Prediction

- Apply data analysis and processing techniques to the horizons and laboratory datasets:
    - Data cleaning
    - Data Merging
    - Variable selection
    - Encoding
    - Data balancing 
- Apply regression models to to classify soil texture effectively and reliably using the minimum number of variables possible
    - RandomForestClassifier

    

# 4. TOC_prediction

- Develop a regression model to predict TOC
- Analyze the influence of different factors on TOC content
- Running RandomForestClassifier model to predict TOC content in soil.







