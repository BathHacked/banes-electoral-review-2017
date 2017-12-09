
# Bath & North East Somerset Electoral Review 2017

## Introduction

[The Local Government Boundary Commission for England (LGBCE)](https://www.lgbce.org.uk/) is carrying out an [electoral review of Bath & North East Somerset Council](https://www.lgbce.org.uk/current-reviews/south-west/somerset/bath-and-north-east-somerset).

At [Bath: Hacked](https://www.bathhacked.org/), our goal is to provide citizens with data to help them make better decisions & to build exciting tools for their community.

Thanks to B&NES council we've been involved with the consultation process from the beginning. The data here represents the next, exciting step forward.

**If you have something to say about what is proposed for your neighbourhood or more generally about the proposals, PLEASE submit your feedback. This an important part of our democracy.**

**[GIVE YOUR FEEDBACK HERE](https://consultation.lgbce.org.uk/node/9913)**

## Context

The last review was carried out in 1998. LGBCE published [their final report](https://www.lgbce.org.uk/__data/assets/pdf_file/0003/8958/somerset-bath-north-east-somerset_6490-6094__e__.pdf) on 31<sup>st</sup> March 1998.

A previous consultation was carried out, from 25<sup>th</sup> July 2017 to 2<sup>nd</sup> October 2017 to decide on the future size of the council. Following the consultation, LGBCE recommended that a new pattern of wards should be created to accommodate 59 councillors - 6 less than previously.

Following on from the review of the council size, a further consultation was carried out, from 25<sup>th</sup> July 2017 to 2<sup>nd</sup> October 2017, to arrive at new warding boundary patterns, to accommodate the new council size. The [proposed boundary changes](https://www.lgbce.org.uk/__data/assets/pdf_file/0017/36521/Bath-and-North-East-Somerset-Draft-Recommendations-Report.pdf), based on that consultation, were published on 5<sup>th</sup> December 2017, beginning a further consultation period ending 19<sup>th</sup> February 2018.

Final recommendations are to be published 8<sup>th</sup> May 2018.

Details of submissions made so far & accompanying documents can be [found on the LGBCE website](https://www.lgbce.org.uk/current-reviews/south-west/somerset/bath-and-north-east-somerset).

## Purpose of this repository

Our aim is to gather together some resources for local stakeholders who are interested in carrying out some geographical analysis of the proposed warding changes.

This repository contains a number of files for use in geographical information systems (GIS).

## GIS files & how to use them

All GIS files are in [GeoJSON](http://geojson.org/) format. This format was chosen for its widespread support both offline & online.

All files use WGS84 coordinate reference system. This is an earth-centered format using latitude & longitude.

You can quickly preview the files by clicking on their links. They can also be embedded into web pages using online tools such as [Carto](https://carto.com/) & [Mapbox](https://www.mapbox.com/) & software packages such as [Leaflet](http://leafletjs.com/) or [OpenLayers](https://openlayers.org/).

For more sophisticated analysis, you can use desktop software packages, such as [QGIS](https://www.qgis.org/en/site/) (Free) & [ArcGIS](https://www.arcgis.com/features/index.html) (Paid).


## File descriptions and usage

All files are [Open Data](https://theodi.org/what-is-open-data) & can be freely used so long as you adhere to restrictions listed below. You must credit the source if attribution is required.

File|Licence & Attribution
---|---|---
[Proposed parish wards](banes_boundary_review_2017_proposed_parish_wards.geojson)|[OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)<br>Data provided by Bath & North Somerset Council (optional)
[Proposed wards](banes_boundary_review_2017_proposed_wards.geojson)|[OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)<br>Data provided by Bath & North Somerset Council (optional)
[2016 polling districts](banes_polling_districts_2016.geojson)|[OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)<br>Data provided by Bath & North Somerset Council (optional)
[Bath City boundary](bath_city_boundary.geojson)|[OS OpenData](http://os.uk/opendata/licence)<br>Contains OS data © Crown copyright [and database right] [year]
[2011 wards](ons_ward_2011.geojson)|[OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) ([OS Open Data](https://www.ordnancesurvey.co.uk/business-and-government/licensing/using-creating-data-with-os-products/os-opendata.html))<br>Contains National Statistics data © Crown copyright and database right [year] Contains OS data © Crown copyright and database right [year]
[Parishes](os_parishes.geojson)|[OS OpenData](http://os.uk/opendata/licence)<br>Contains OS data © Crown copyright [and database right] [year]
