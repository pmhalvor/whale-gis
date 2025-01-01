# Whale GIS

Introduction to GIS, combining atomshperic geo-data, to surface-level geo-data. 

# Contents
- Notebooks
    - [GIS intro](notebooks/gis_intro.ipynb): Getting started with geo-data from earthkit, and different visualzation methods using cartopy, folium, and xarray, including both interactive and stiatic plots, along with animations.
    - [Regionmask](notebooks/regionmask.ipynb): Using regionmask to create masks for different regions, and using them to filter out data.
    - Whale migration notebook: _(coming)_ Combining whale observatioons with region masks to build migration dataset. 


# Setup

```
uv venv
uv pip install -r requirements

```

# Resources
- [earthkit ADS API tutorial](https://earthkit-data.readthedocs.io/en/latest/examples/ads.html)
- [Atmospheric data store](https://ads.atmosphere.copernicus.eu/)
- [ECMWF tutorial on GRIB](https://confluence.ecmwf.int/display/CKB/What+are+GRIB+files+and+how+can+I+read+them)
- [Xarray GRIB visualization tutorial](https://docs.xarray.dev/en/stable/examples/ERA5-GRIB-example.html)
- [ROMS Ocean Model Example](https://docs.xarray.dev/en/stable/examples/ROMS_ocean_model.html)
- [Folium docs](https://python-visualization.github.io/folium/latest/reference.html)
- [ArcGIS Blogpost on Whale Migrations](https://storymaps.arcgis.com/stories/19af1858ea074c6bbc2b512d5111ddad)
