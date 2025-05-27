# Python_and_research
Projects where programming tools and machine learning are applied, focused on agricultural research and ecology

# 1. Soil_use_frequencies.
## EXPLORATORY DATA ANALYSIS. Erste Bodenzustandserhebung Landwirtschaft – Kerndatensatz.
In this notebook, we are going to study the frequencies of the types of soils we have in each kind of land use:
Land use at time of sampling (A=cropland, G=grassland since at least 5 years, SO=special permanent crops) Main soil type (German soil classification) following KA5



# 2. TOC_Soil_Type
## Exploratory Data Analysis – Erste Bodenzustandserhebung Landwirtschaft (Core Dataset)

In this notebook, we apply various data analysis techniques to explore the potential relationship between soil types and their Total Organic Carbon (TOC) content. The dataset includes measurements from German agricultural soils, including water content, bulk density, TOC (Total Organic Carbon), and TN (Total Nitrogen).
Workflow

- Load the SITE and LABORATORY datasets.

- From the SITE dataset, select the following variables: PointID, coordinates, land use, main soil type, and specific soil subtype.

- Merge this data with the LABORATORY dataset, using the variables: TOC, TN, bulk density, and water content.

- Perform Exploratory Data Analysis (EDA):

        Count the number of observations for each soil type and their corresponding TOC values.

        Create scatter plots of TOC versus water content and bulk density for the most common soil type (and optionally for other types).

        Generate a 3D plot of TOC, water content, and bulk density for the most common soil type.

- Modeling:

        Apply regression models to predict TOC values in Cambisols using water content and bulk density as predictors.

- GIS Visualization:

        Map the soils with the highest TOC values.

- Conclusions



# 3. Soil texture classifier

- Apply data analysis and processing techniques to the horizons and laboratory datasets:
    - Data cleaning
    - Data Merging
    - Variable selection
    - Encoding
    - Data balancing 
- Apply regression models to to classify soils by its texture effectively and reliably using the minimum number of variables possible
    - RandomForestClassifier

    

# 4. TOC_prediction

- Exploratory data analysis.
- Analyze the influence of different factors on TOC content.
- Running RandomForestClassifier model to predict TOC content in soil.







