# mapbox_studio101
Mapbox Studio Tutorial, testing conceptual slideshow approach with reveal.js

###Tutorial Breakdown
[Google Doc](https://docs.google.com/document/d/10jr9v937-H94ze0W-ORp11mKmRYuSY-HHgpy5QnC0yw/edit?usp=sharing)

###Data
This sample dataset is on the Boyle Heights neighborhood of the City of Los Angeles. Using QGIS, the sample was taken from the Los Angeles County Assessors Parcels -2014 Tax Roll using the boundaries of the Boyle Heights Community Plan. The data in this repo is prepared for use during the Mapbox Studio Tutorial. It is as follows:

* Shapefile: Can be open in any GIS software and Mapbox Studio
* geojson: Can be open in any GIS software and Mapbox Studio
* mbtiles: Can be uploaded and served by Mapbox or your own tileserver
* boyleheightsCPStyle.tm2: Styling files that can be opened in Mapbox Studio
* boyle_heightsCP.tm2source: Source files linking to Shapefile or geojson

###Data Attributes
The data contains the following (Please note, for the purpose of this tutorial, the dataset has omitted attributes from the original dataset)
* AIN (= AssessorID without imbedded hyphens)
* SitusConcatenated ( = SitusHouseNo + SitusFraction + SitusDirection + SitusStreet + SitusUnit)
* SitusCity – Property Postal City
* SitusZIP5 ( = first 5 digits SitusZIP)
* UseCode – 4 digit Use Code
* UseCodeDesc ( breakdown of UseCode description … , ex. Residential, Commercial, etc)
* UseCodeD_1 (ex. Single family residence, Office Building)
* UseCodeD_2 (ex. Vacant Land)
* UseCodeD_3 ( … breakdown of UseCode description )
* YearBuilt  (Age of the building built on parcel)
* SQFTmain – Square Footage calculated from the 5 entries of building information maintained by the Assessor.
* Bedrooms – Number of bedrooms
* Bathrooms – Number of bathrooms
* Units – Number of units
* RecordingDate – The last date this information was recorded
* Roll_LandValue – Land Value
* Roll_LandBaseYear – Base year for the land value. Proposition 13 limits property value increases so this year sets the base for these amounts.

###Data Sources
[2014 LA County Assessors Parcels](http://egis3.lacounty.gov/dataportal/2015/03/10/assessor-parcel/), from LA County GIS Data Portal
[City of Los Angeles Community Plans](https://data.lacity.org/A-Well-Run-City/Community-Plan-Area/pu8r-72kk), from LA City's Data Website


###Resources
[Intro to Mapbox Studio](http://lyzidiamond.com/mapbox-studio/#0), by the Bumblebee, Lyzi Diamond (insert, Wayne's World we're not worthy)

[FOSS4G Video on Vector Tiles](https://vimeo.com/106228141)

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

