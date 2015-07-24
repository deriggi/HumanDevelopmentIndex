# Dendrogram For the Human Developnent Index
The [HDI Dataset](http://hdr.undp.org/sites/default/files/hdi_series_cartagena.xlsx) from the UNDP creates an index for each country based on four major variables: 
* Gross National Income
* Life Expectancy at Birth
* Expected Years of Schooling
* Mean years of Schooling

Each country is indexed on those variables for every year from 1980 - 2013. The dat is more copmlate as you get closer to 2013. To understand how the countries are distributed by the index we used a clustering function in R called hclust using the "ward" method


![hdidendrogram](/dendrogram_export_3.png "HDI")


