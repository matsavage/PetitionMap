# PetitionMap
Notebook to create choropleth map from UK petitions

This is a simple iPython notebook to determine the proportion of each constituency that has signed a UK government petition, and to generate a map using the [folium](https://github.com/python-visualization/folium) package.

The package reads data from the [UK Government and Parliament Petitions](https://petition.parliament.uk/) website and makes use of other public domain data to create a visualisation.

![](https://github.com/matsavage/PetitionMap/blob/master/map.png?raw=true "PetitionMap")

The [ukpop.csv](https://github.com/matsavage/PetitionMap/blob/master/ukpop.csv) file is sourced from the UK government [statistics](https://public.tableau.com/profile/house.of.commons.library.statistics#!/vizhome/Populationbyage_0/Dataconstituencyincontext).

The [uk.json](https://github.com/matsavage/PetitionMap/blob/master/uk.json) shapefile of the UK is sourced and merged from [martinjc's UK-GeoJSON](https://github.com/martinjc/UK-GeoJSON) package, and simplified using the [mapshaper](https://github.com/mbloch/mapshaper) package.
