# 🪐 NASA Exoplanet Data Analysis Project

## Introduction

### What are Exoplanets :-
   An exoplanet is a planet that orbits a star outside of our solar system. There are about 6,000+ such exoplanets discovered currently. This dataset I analysed was publised on july 2023 when only 5,470 were discovered. Eventhough the dataset is published by Nasa,they include all exoplanets ever found around the globe.All discovery methods except pulsar timing uses light and gravity. 

### Why I choose this :-
  **1) High quality real world dataset** :-Since the data is published by NASA, it is extremely reliable and trustworthy. It covers space and astronomy—one of the most relevant and fascinating real-world scientific domains.<br><br>
  **2) Important and Relevent applications** :- Exoplanet research plays a major role in space exploration, identifying potentially habitable planets, understanding the formation of solar systems, and contributing to climate science through comparative planetology. <br><br>
  **3) Rich analysis work** :- This dataset allows a wide range of analytical techniques, including PCA, K-Means clustering, KNN imputation, and various data visualizations such as histograms, sunburst charts, Mollweide projections, and more.<br><br>
  **4) Interesting topic** :- Space, solar systems, and the outer universe have always fascinated me. Working with this dataset helped me explore these concepts in more depth and gain meaningful insights about exoplanets.<br><br>

  
### About Dataset :-

The dataset is “NASA Exoplanet Archive (July 2023)” from Kaggle shows confirmed exoplanets discovered as of July 2023 and its different characters like mass, density, eccentricity etc. All these datasets were recorded by different expeditions at different time period. The dataset contains 5470 rows and 26 subset columns (out of 353). Hence Dimension is:-  5470 X 26.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Abruz-plotz/Nasa-Exoplanet-Project/blob/main/Nasa%20Exoplanets.ipynb)

---
## 



---
##  Tools & Technologies 

### Tools :-

- Python
- Jupyter Notebook / Google Colab
- Pandas, NumPy, Ski-kit learning
- Matplotlib, Seaborn

###  Techniques Used :- 

- Principal Component Analysis (PCA) – for dimensionality reduction
- K-Means Clustering – to identify groups of similar exoplanets

---

##  Project Objectives

- Know more about exoplanets
- Analyze the number of exoplanets discovered using different methods.
- Study discovery trends over the years.
- Visualize relationships between planet mass, orbital period, and discovery method.

---

##  Key Insights

- The solar system with the most planets discovered is KOI-351 with 8 planets similar to our solar system.
- Top 10 nearest exoplanets are within 3.6 light-years from Earth.
- Exoplanet discovery peaked in 2016 with over 1517 planets discovered and was lowest at 1994 with 1 exoplanet being discovered.The exoplanets discoveries peaked at 2016 because massive confirmations happened of dobtful findings from KEPLER in that year.

- Using Scatterplot it is clear most exoplanets are found at about 270 degree radius called **Cygnus Lyra region**. The reason is that most telescopes including the Kepler are focused on that area alone due to **Galactic Bulge**(Abundance of suns). The K-Means from same chart indicates that the planet Cluster 4,8,9 are abundant at Cygnus Lyra region. But a pattern in planet distribution can be confirmed only after more exoplanet discoveries in different region. 
- 3D distribution shows exoplanets at northern sky from earth were mostly discovered in 2016 and exoplantes at southeren sky are mostly discovered after 2018.
- **Transit** is the most widely used method for discovering exoplanets.
- Discovery rates increased significantly after 2010, coinciding with the Kepler mission.

