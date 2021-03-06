# My_Jupyter_Notebook_sandpit
My Jupyter Notebook projects
## GeoCoder

This module uses Google Maps Geocoding API to parse input address into a correct format and find corresponding Lat/Lng coordinates.

There are several notebooks available there:
  1. One uses as a dataset Historical-Settlement-Reports XLSX file for the first half of 2017 from DATA.GOV.AU. The notebook is also available there: https://anaconda.org/alexf/geocoder/notebook
  
  2. Another one uses archived Historical-Settlement-Reports dataset from 2016 from DATA.GOV.AU. The only difference from the first notebook is the capability to open ZIP archive and extract an appropriate file from there.
  
  3. csv2geojson converter. This notebook is helpful to convert CSV files, generated at previous steps, into GeoJSON files which can be used by various visualisation libraries, e.g. ipyleaflet, folium, etc.
  
  4. `lga_visualisation` notebook - visualise results of Historical-Settlement-Reports using Folium.
    For example, the screenshot below demonstrate distribution of settlers in the first half of 2017 across Melbourne suburbs
    <img width="887" alt="Distribution of settlers in the first half of 2017 across Melbourne suburbs" src="https://user-images.githubusercontent.com/19657873/34505358-dc5f14ee-f078-11e7-8ac4-906c2328c3fc.png">


