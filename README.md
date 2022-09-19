# Mapping_Morocco
As an exploratory project in Geoanalytics, I'll be mapping out the different administrative area in Morocco and then adding general data to those.

## Todo list
    [] 

## Sources
A [list of Morocco's subnational boundaries](https://data.humdata.org/dataset/cod-ab-mar).

GeoAnalyitic information: Mapbox.  If you want to follow along, you'll have to make a Mapbox account and generate an api key.  After that, create a file called 'config.js', save it into the static/js folder, and add:

`API_KEY = YOUR KEY`

[GeoJson of Morocco with regions](https://raw.githubusercontent.com/manalhama/Morocco-geojson/master/maroc.geojson)

D3

Note on data: originally [the data](https://api.worldbank.org/v2/en/country/MAR?downloadformat=csv) had a header that was interferring with pandas, and was removed with v3
