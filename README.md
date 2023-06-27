[![Cover](cover.jpg)](https://www.coursera.org/learn/applied-data-science-capstone)

## Introduction
SpaceX is a revolutionary company who has disrupt the space industry by offering a rocket launches specifically Falcon 9 as low as 62 million dollars; while other providers cost upward of 165 million dollar each. Most of this saving thanks to SpaceX astounding idea to reuse the first stage of the launch by re-land the rocket to be used on the next mission. Repeating this process will make the price down even further. As a data scientist of a startup rivaling SpaceX, the goal of this project is to create the machine learning pipeline to predict the landing outcome of the first stage in the future. This project is crucial in identifying the right price to bid against SpaceX for a rocket launch.

<br>

## Project Steps

1. **[Data Collection with API](data-collection-api.ipynb)**
   - Collected rocket launch data from SpaceX API, including launch dates, payloads, and outcomes.

2. **[Data Collection with Web Scraping](data-collection-web-scraping.ipynb)**
   - Scraped Falcon 9 historical launch records from SpaceX table on Wikipedia, capturing details such as mission names, launch sites, and mission outcomes.

3. **[Data Wrangling](data-wrangling.ipynb)**
   - Cleaned and preprocessed collected data, handling missing values, formatting inconsistencies, and merging relevant datasets.

4. **[Exploratory Data Analysis (EDA) with SQL](eda-sql.ipynb)**
   - Analyzed data using SQL queries to gain insights into launch success rates, payload distributions, and other key metrics.

5. **[Exploratory Data Analysis (EDA) with Data Visualization](eda-data-visualization.ipynb)**
   - Explored data through visualizations, including histograms, scatter plots, and pie charts, to uncover trends, correlations, and anomalies.

6. **[Interactive Visual Analytics with Folium](interactive-maps-folium.ipynb)**
   - Created interactive maps and visualizations using the Folium library to examine geographical patterns, launch site locations, and landing outcomes.

7. **[Dashboard Application](spacex_dash_app.py)**
   - Developed an interactive dashboard application using a suitable framework (e.g., Plotly Dash) to present key insights, filter data, and provide an intuitive user interface.

8. **[Predictive Analysis - Machine Learning](machine-learning-prediction.ipynb)**
   - Applied machine learning algorithms, such as logistic regression, k-nearest neighbors (KNN), decision trees, and support vector machines (SVM), to predict successful rocket landings based on features like payload mass, launch site, and mission outcome history.

9. **[Final Presentation](ds-capstone-presentation.pdf)**
   - Presented project findings, insights, and conclusions, highlighting the most significant discoveries and discussing the implications of the analysis.

<br>

## Acknowledgements
© Copyright IBM Corporation 1994, 2023.<br>© Peerapong Charoenkijwattanakul 2023.
