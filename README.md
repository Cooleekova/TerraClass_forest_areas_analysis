## Geoinformatics student project: 
# Implementing Python automatization to processing of the TerraClass Project geospatial data

The TerraClass Project is developed and executed by the Amazon Regional Center
(CRA) in partnership with the Brazilian Agricultural Research Corporation (Embrapa).
TerraClass is responsible for qualifying deforestation in the Brazilian Legal Amazon
and thus provides important subsidies for a better understanding of land use and
land cover in the Amazon.

## Objective of the work
TerraClass geodata is classified by vegetation type, with one of these types
containing areas covered by primary forest.

Areas of primary forest can be isolated from each other by other land cover types,
and one of the TerraClass initiatives is identifying forest areas that are within a short
distance of each other and can be combined into a single protected forest corridor.
For more effective work on mapping primary forest areas and carrying out work on
the creation of protective territories, there is a need for vector data processing by
analyzing the area of forested areas and the distance between them.
Thus there is a need for software to automate the process of locating closely spaced
forest areas, aggregating them into groups of areas, and obtaining geographic
information about the location of these groups.

## Methodology
In order to automate the processing of geodata can be used a Python project
GeoPandas.
It is based on the Pandas package that provides flexible data structures for doing
data analysis in Python and the Shapely package which is created to perform
manipulations with planar geometric objects in Python.
GeoPandas adds support for geographic data to pandas objects. It implements
GeoSeries and GeoDataFrame types which are subclasses of pandas.Series and
pandas.DataFrame respectively. GeoPandas objects can contain Shapely geometry
objects and perform geometric operations.

## Used data
As a data sample was used the TerraClass data of year 2020 for the municipality of
São Luíz do Norte in the state of Goiás.
