# David J. C. Beach

This web portfolio displays some of my recent work in Data Science and Data Visualization.

## ROAM: A Neighborhood Explorer based on t-SNE

<a href="https://github.com/dbeach24/roam" target="_blank">
  <img src="img/roam.png" alt="Roam Explorer" width="500px"/>(link)<br/>
</a>

Roam is an experiment in visual interaction employing t-SNE scatterplots as a way to overview and select data.  Roam allows the user to change the organization of the overview scatterplot by prioritizing different variable weights.  Selection, highlighting, and coloring are used effectively to communicate the association between scatterplot points and quantitative and qualitative values.  Using Roam, the user receives a overview of the distribution of high-dimensional data and relationships between many variables.

## Streaming t-SNE

<a href="https://github.com/dbeach24/StreamingTSNE" target="_blank">
  <img src="img/streaming_tsne.png" alt="Streaming t-SNE" width="500px"/>(link)<br/>  
</a>

[T-Distributed Stochastic Neighbor Embedding (t-SNE)](https://lvdmaaten.github.io/tsne/) is a widely used technique for embedding data of high dimension into a 2-D or 3-D space, while preserving local relationships in the original data.  Most implementations of this work employ batch processing to compute the 2-D embedding from a set of fixed, high-dimensional points.  [This project](https://github.com/dbeach24/StreamingTSNE) develops a streaming version of the algorithm, which creates and refines the embedding as data arrive.

<iframe width="560" height="315" src="https://www.youtube.com/embed/q3lbmlHWCtg?color=white&theme=light" frameborder="0" allowfullscreen></iframe>

[This video](https://youtu.be/q3lbmlHWCtg) shows how the t-SNE embedding evolves as a sliding window moves over a slowly changing distribution.

## The Missing Migrants

<a href="https://dbeach24.github.io/missing-migrants-vis/" target="_blank">
  <img src="img/migrants.png" alt="The Missing Migrants" width="500px"/>(link)<br/>
</a>

This visualiztion uses the [Missing Migrants](https://www.kaggle.com/jmataya/missingmigrants) dataset on Kaggle, and contains information about people who have gone missing while travelling along migration routes.  The visualization is coded using [D3.js](https://d3js.org/) and features several linked interactions.  This data originates from the [Missing Migrants Project](https://missingmigrants.iom.int/).  The [source code](https://github.com/dbeach24/missing-migrants-vis) is hosted on GitHub.

## The 50 States of US Energy

<a href="https://djbeach.shinyapps.io/usenergy/" target="_blank">
  <img src="img/USEnergy.png" alt="The 50 States of US Energy" width="500px"/>(link)<br/>
</a>

This project combines data from the [US Energy Information Administration (EIA)](https://www.eia.gov/) with other sources to give a dynamic picture of energy production and consumption across the 50 US States.  The data was combined and cleaned [using R](https://www.r-project.org/), and is dynamically displayed using R code with [plotly.js](https://plot.ly/javascript/).

## Monary

<a href="https://bitbucket.org/djcbeach/monary/wiki/Home" target="_blank">
  <img src="img/monary.png" alt="Monary" width="500px"/>(link)<br/>
</a>

[Monary](https://bitbucket.org/djcbeach/monary/wiki/Home) is an open source driver enabling
high performance queries for [MongoDB](https://www.mongodb.com/).

Monary was born out of a desire to improve query performance when accessing
[MongoDB](https://www.mongodb.com/) from dynamic languages like [Python](http://www.python.org),
in support of high-volume tasks such as data analytics.  It attracted internal
attention from MongoDB, Inc., and was enhanced by several MongoDB employees.  Browse
[the documentation](https://monary.readthedocs.io/).  Also these presentations by
[Kyle Suarez and Matt Cotter](https://www.youtube.com/watch?v=oteFpXIKBYg) and
[Anna Herlihy](https://www.youtube.com/watch?v=E70AO8r5sMs).

## Datasci Resources

<a href="https://trello.com/b/Uzcg2I6d/datasci-resources" target="_blank">
  <img src="img/datasci-resources.png" alt="DataSci Resources" width="500px"/>(link)<br/>
</a>

This is a Trello board I maintain which serves as a repository of bookmarks to different
datascience repositories, projects, and tools on the web.

## D3 Visualizations on Blocks.org

<a href="https://bl.ocks.org/dbeach24" target="_blank">
  <img src="img/blocks.png" alt="D3 Visualizations on Blocks.org" width="500px"/>(link)<br/>
</a>

Here's a sample of other visualizations I've created using `D3.js`.

