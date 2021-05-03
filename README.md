# Cryptocurrencies

## Overview

This repository holds sample analysis on unsupervised learning for the purpose of clients entering the cryptocurrency market. In particular, how to process data, cluster, dimension reduction and reducing principal components, and then visualizations are included in the [attached notebook](crypto_currencies.ipynb). Accountability Accounting (AA) is interested in determining categorizing cryptocurrencies in order to understand them and subsequently create portfolios for investers. Since AA is not sure what output they are looking for, unsupervised machine learning may be used to assist in creation of categories and classifications of the vast cryptocurrency market.

## Resources

Tools used in this analysis include:

* Python
  * Jupyter notebooks
* Plotly
* Sci-kit Learn ([sklearn](https://scikit-learn.org/stable/modules/classes.html))
* HoloViews Plot ([hvPlot](https://hvplot.holoviz.org/index.html)) 

## Results

Due to limitations on displaying plots in the Jupyter Notebook, sections of the notebook that would normally have an image shown beneath them have been depicted below.

The first is the Elbow Curve, used to find the optimal number of clusters for K-Means method.

![ElbowCurve](/Resources/ElbowCurve.png)

The second is the 3D scatter graph, clustered by principle components.

![scatter3d](/Resources/scatter3d.png) ![scatter3dwhover](/Resources/scatter3dwhover.png)

Following that is the table of tradable cryptocurrencies.

![hvplottable](/Resources/hvplottable.png)

Finally, a scatter plot based on scaled values for the coin supply and quantity of coins mined.

![2dscatter](/Resources/2dscatter.png) ![2dscatterwhover](/Resources/2dscatterwhover.png)

## Summary

Accountability Accounting is interested in using the above depictions to create investment portfolios for it's customers. They can put together portfolios that lean towards different objectives and set up the portfolio's based on their customer's desires and what categories or clusters those desires match. The algorithm and proof type of the cryptocurrencies were separated, re-merged and recategorized and clustered to provide four distinct clusters and categories for AA to build into portfolios for their clients. 