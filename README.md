# Coronavirus Disease 2019 (COVID-19 or 2019-nCoV) Cases Tracker

[This web map](https://app.isnew.info/2019-ncov) is an open source version of [the COVID-19 global cases website](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6) by [Johns Hopkins CSSE](https://systems.jhu.edu). It uses their [time series data](https://docs.google.com/spreadsheets/d/1UF2pSkFTURko2OvfHWWlFpDFAr1UxCBA4JLwlSP6KFo/export?format=ods&id=1UF2pSkFTURko2OvfHWWlFpDFAr1UxCBA4JLwlSP6KFo), [REST API](https://services1.arcgis.com/0MSEUqKaxRlEPj5g/ArcGIS/rest/services/ncov_cases/FeatureServer/1/query?where=1%3D1&outFields=*&f=json), and [OpenLayers](https://openlayers.org).

Why reinvent the wheel? Why not!

## Disclaimer

Data that `fetch_data.py` collects from [CSSE's website](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6) is copyrighted by [Johns Hopkins CSSE](https://systems.jhu.edu). Post-processing of the data by the script may introduce errors and the author is not responsible for any damages caused by using the processed data and the web map.

## License

Copyright (C) 2020, Huidae Cho <<https://idea.isnew.info>>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <<https://www.gnu.org/licenses/>>.
