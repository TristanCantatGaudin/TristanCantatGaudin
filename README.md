I am an astronomer at the Max Planck Institute for Astronomy in Heidelberg. My work aims at identifying and characterising star clusters and stellar structures in the Milky Way, by applying efficient data mining and machine learning methods to large datasets. This in turns allows to to map the current structure of the Milky Way in three dimensions, and to track its evolution through time.

## Cluster mining and Milky-Way mapping

The data collected by the ESA mission Gaia is published as several huge datasets, with the main table having about 2 billion rows and over 100 columns. With efficient methods, we can identify groups of stars with common properties and travelling together through the Galaxy. The projects I have led and participated in use a variety of clustering methods, including `k-means` clustering, `DBSCAN`, `HDBSCAN`, `Gaussian Mixture Models`, and dimensionality reduction techniques such as `t-SNE`, `PCA`, and `UMAP`. Gaia allowed us to discover hundreds of new clusters, some in remote regions of the Milky Way, but many of them in the Solar neighbourhood!

<img src="https://github.com/TristanCantatGaudin/TristanCantatGaudin/blob/main/ocs_mw_xyz_1500.png" width="800" />

## Estimating the ages of star clusters

The age of a stellar cluster can be estimated by looking at the distribution of its stars in a colour-magnitude diagram. A complete modelling of this distribution can provide deep insight into the cluster's properties, but can also be extremely time consuming, potentially requiring hours for a single cluster. In order to be able to quickly process thousands of clusters at once, I have [trained a `Neural Network`](https://ui.adsabs.harvard.edu/abs/2020A%26A...640A...1C/abstract) to return cluster ages, and showed that the young clusters trace a fragmented spiral pattern in the Milky Way.

Studying star clusters also allows us to take a detailed look at stellar evolution. This HR diagram is constructed from [publicly available data](https://vizier.cds.unistra.fr/viz-bin/VizieR?-source=J/A+A/640/A1), using clusters for which I have established the stellar members and the main parameters:

<img src="https://github.com/TristanCantatGaudin/playground/blob/main/img/img_cmd.png" width="350" /> 
(see the code in [this notebook](https://github.com/TristanCantatGaudin/playground/blob/main/composite_Gaia_cmd.ipynb))


### More about my astro work

Click here for an overview of my scientific work in astronomy:
🔭 [TristanCantatGaudin.github.io](https://TristanCantatGaudin.github.io)

and [here](https://ui.adsabs.harvard.edu/search/p_=0&q=%20author%3A%22cantat-gaudin%22&sort=date%20desc%2C%20bibcode%20desc) for a full list of the studies I have authored and co-authored.


The rest of this page lists some of my professional and hobby projects:

---
<img src="https://github.com/TristanCantatGaudin/TristanCantatGaudin/blob/main/gu_banner_800.png" width="400" />

I am currently the lead developer of the Python package [GaiaUnlimited](https://github.com/gaia-unlimited/gaiaunlimited), a package for querying and constructing selection functions for the Gaia survey developed by the GaiaUnlimited collaboration.



---

### [Gaia citations through ADS](https://github.com/TristanCantatGaudin/ADS-Gaia-Citations)

Provides daily updates for the number of citations to the Gaia collaboration papers, using the ADS API. The graph is updated every day through GitHub actions. It is also available as an interactive <a href="https://tristancantatgaudin.github.io/ADS-Gaia-Citations/ads-citations-plotly.html">plotly figure</a>.

<img src="https://github.com/TristanCantatGaudin/ADS-Gaia-Citations/raw/main/citations_per_month.png" width="500" />



---
### [rainbowprint](https://github.com/TristanCantatGaudin/rainbowprint)
A template for a simple Python package. It actually does something: applies colour gradients to strings! It works in the terminal and in Jupyter notebooks.

<img src="https://github.com/TristanCantatGaudin/rainbowprint/raw/main/docs/example1.png" width="500" />

---
### [NBA hexbin](https://github.com/TristanCantatGaudin/nba-hexbin-app)
Streamlit app to display yearly shot volume and efficiency for NBA players. Deployed on Streamlit cloud. Collects data from [BasketBall-Reference](https://www.basketball-reference.com/).

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://nba-hexbin-app.streamlit.app/)

<img src="https://github.com/TristanCantatGaudin/playground/raw/main/nba/hexbin_shot_charts.png" width="800" />

---
### [Playground](https://github.com/TristanCantatGaudin/playground)
This repository hosts Jupyter and Marimo notebooks, with data visualisation projects related to: astronomy, weather, geospatial data (from Flickr, OpenStreetMap, satellite imagery), mathematics and statistics, stock market, sports, deep learning...



<a href="https://github.com/TristanCantatGaudin/playground/blob/main/max_temp_three_cities.ipynb"><img src="https://github.com/TristanCantatGaudin/playground/blob/main/img/max_temp_1950_2024.png" width="500" /></a>

<a href="https://github.com/TristanCantatGaudin/playground/blob/main/geotagged_photos_venezia.ipynb"><img src="https://github.com/TristanCantatGaudin/playground/raw/main/img/img_venezia.png" width="500" /></a>

<a href="https://github.com/TristanCantatGaudin/playground/blob/main/bar_chart_color_rain.ipynb"><img src="https://github.com/TristanCantatGaudin/playground/blob/main/img/rain.png?raw=true" width=500 height=200 /></a>
