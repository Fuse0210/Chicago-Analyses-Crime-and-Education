# Chicago Crime and Education Analysis

This project analyzes the relationship between **crime rates** and **educational quality (public elementary school performance)** across different communities in Chicago.

## Project Objective
The goal is to analyze criminal patterns in Chicago and explore potential correlations between acacemic achievement and local crime incidents using open data, aiming to visualize trends and understand community dynamics.

## Datasets
The analysis is based on the following datasets:
1. **Chicago Crime Data**: Records of reported incidents across the city.
2. **Chicago School Data**: Information regarding public elementary school performance scores and demographics.
3. **Data Processing**: The dataset originally included 462 elementary schools; **451 schools were analyzed** (11 schools were dropped due to missing data).
4. **Metrics**: The percentage of students meeting target levels in Math and Reading (Grades 3-5) was used as an academic achievement metric.
5. **Sampling**: The first 1,000 incidents in the original crime dataset were used to create the maps.

## Tech Stack
* Python 3
* Pandas (Data manipulation)
* NumPy (Numerical computing)
* Matplotlib / Folium (Visualization)
* Jupyter Notebook

## Analysis Workflow
1. **Data Cleaning**: Merging and preprocessing datasets for analysis.
2. **Descriptive Analysis**
3. **Exploratory Data Analysis (EDA)**:
    * Analyzing temporal and spatial trends in crime.
    * Visualizing the distribution of school ratings.
    * Applying the **K-means clustering** method.

## Analysis Results

### Criminal Incidents Analysis
Below is the breakdown of different types of incidents analyzed in this project:

![Types of Incidents Analysis](images/types%20of%20incidents.png)

### School Performance Analysis
I visualized crime data in relation to school performance by comparing low-performing and high-performing schools.

**Low-Performing Schools:**
![Low Performing Schools](images/low%20performing%20schools.png)

*Note: You can click the markers to see the school names:*
![Low Performing Schools Labels](images/low%20performing%20schools%20labels.png)

🔗 **Interactive Map**: [Low-Performing Schools Map](https://nbviewer.org/github/Fuse0210/Chicago-Analyses-Crime-and-Education/blob/main/Crime%20and%20Education%20%28ES%29.ipynb#Locations-of-the-schools-with-the-lowest-scores) (The first map with **blue dots** is the actual map; the others are static images).

**High-Performing Schools:**
![High Performing Schools](images/high%20performing%20schools.png)

*Note: You can click the markers to see the school names:*
![High Performing Schools Labels](images/high%20performing%20schools%20labels.png)

🔗 **Interactive Map**: [High-Performing Schools Map](https://nbviewer.org/github/Fuse0210/Chicago-Analyses-Crime-and-Education/blob/main/Crime%20and%20Education%20%28ES%29.ipynb#Locations-of-the-schools-with-the-highest-scores) (The first map with **green dots** is the actual map; the others are static images).

## Key Findings
1. **The top 3 criminal incidents** in Chicago in 2020 were: **Narcotics**, **Battery**, and **Weapons Violation**.
2. **Four "low-performing" elementary schools** were located in the neighborhood with **the highest crime rate**.
3. "Low-performing schools" were significantly more likely to be located in neighborhoods with higher crime rates.
4. "High-performing schools" tended to be located in safer neighborhoods (indicated by lighter colors on the map).

---

## Notebook Links
Explore the full analysis and interactive visualizations through the links below:

* [Chicago Crime Analysis (Bar Charts)](https://nbviewer.jupyter.org/github/Fuse0210/Chicago-Analyses-Crime-and-Education/blob/main/Chicago%20Crime%20Analysis%20%28Bar%20Charts%29.ipynb)
* [Chicago Crime Analysis (Maps)](https://nbviewer.jupyter.org/github/Fuse0210/Chicago-Analyses-Crime-and-Education/blob/main/Chicago%20Crime%20Analysis%20%28Maps%29.ipynb)
* [Chicago Crime Analysis (Choropleth map)](https://nbviewer.jupyter.org/github/Fuse0210/Chicago-Analyses-Crime-and-Education/blob/main/Chicago%20Crime%20Analysis%20%28Choropleth%20map%29.ipynb)
* [Crime and Education (ES)](https://nbviewer.jupyter.org/github/Fuse0210/Chicago-Analyses-Crime-and-Education/blob/main/Crime%20and%20Education%20%28ES%29.ipynb)


