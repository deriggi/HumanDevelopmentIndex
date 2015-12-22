# Dendrogram For the Human Developnent Index
The [HDI Dataset](http://hdr.undp.org/sites/default/files/hdi_series_cartagena.xlsx) from the UNDP creates an index for each country based on four major variables: 
* Gross National Income
* Life Expectancy at Birth
* Expected Years of Schooling
* Mean years of Schooling

Each country is indexed on those variables for every year from 1980 - 2013, with more completeness in years closer to 2013. The end result of the index is simply a numerical value describing the overall strength of the country based on the four variables. This is great because it provides a measurable numerical value on which to guage progress and help focus aid. However, as the recent trend in data visualization has demonstrated, seeing patterns in tabluar data is much more difficult than charts and graphical representations of data.

One high level application of data visualization with this data is to use it to help us understand how the countries are distributed by their index values. Obviously we could sort the data and show rich countries at one end and poor countries at another end. But rankings mask the clusters or bunches of values that are might show a big gap between different tiers of index performance.  

To begin the investigation we are going to use a clustering function in R called hclust using the "ward" method: [hclust](https://stat.ethz.ch/R-manual/R-devel/library/stats/html/hclust.html)

# Dendrograms
Aside

![hdidendrogram](/dendrogram_export_3.png "HDI")


