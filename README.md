![alt text](https://raw.githubusercontent.com/maptimeLA/mapbox_studio101/master/images/cover.png)

# mapbox_studio101
MaptimeLA Stying Tutorial

###Tutorial Breakdown
1. Maps on the web 
2. Need for exploring re-presentation of maps
3. What are webmaps?
4. Tools for styling maps
5. CartoCSS, coding in style
6. Tool of the day: Mapbox Studio
 * Sign-Up for [Mapbox Account](https://www.mapbox.com/plans/)
 * Download for [Windows](https://www.mapbox.com/mapbox-studio/#win64), [Mac OSX](https://www.mapbox.com/mapbox-studio/#darwin) or [Linux](https://www.mapbox.com/mapbox-studio/#linux)
7. Steps (Working files for each step is contained in the "Steps Folder" and labeled as such)
  * 1 // Loading sources to Mapbox Studio (Loading Shapefiles)
  * 2 // Publishing map to host on Mapbox (Mapbox converts to mbtiles to be uploaded)
  * 3 // Styling your map (Mapbox saves styles as .tm2z file)
  * 4 // Making a simple map with HTML, CSS and Javascript, (only 5 lines of code!)
   * Available text editors:[Sublime](http://www.sublimetext.com/) // [Brackets](http://brackets.io/) // [Atom](https://atom.io/)



###Data
This sample dataset is on the Boyle Heights neighborhood of the City of Los Angeles. Using QGIS, the sample was taken from the Los Angeles County Assessors Parcels -2014 Tax Roll using the boundaries of the Boyle Heights Community Plan. The data in this repo is prepared for use during the Mapbox Studio Tutorial. It is as follows:

* Shapefile: Can be open in any GIS software and Mapbox Studio
* geojson: Can be open in any GIS software and Mapbox Studio
* mbtiles: Can be uploaded and served by Mapbox or your own tileserver
* boyleheights.tm2z: Styling files that can be opened in Mapbox Studio, (Note: Opening this file will load Boyle Heights data from Omar's Mapbox Account. During the tutorial, you will be able to link to your mapbox account.)

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
* Roll_ImpValue – Improvement Value
* Roll_ImpBaseYear - Base year for the improvement value. Proposition 13 limits property value increases so this year sets the base for these amounts.

###Data Sources
[2014 LA County Assessors Parcels](http://egis3.lacounty.gov/dataportal/2015/03/10/assessor-parcel/), from LA County GIS Data Portal

[City of Los Angeles Community Plans](https://data.lacity.org/A-Well-Run-City/Community-Plan-Area/pu8r-72kk), from LA City's Data Website


###Resources
[Intro to Mapbox Studio](http://lyzidiamond.com/mapbox-studio/#0), Slideshow by the Bumblebee, Lyzi Diamond (insert, Wayne's World we're not worthy)

[Video tutorial to Mapbox Studio](https://www.youtube.com/watch?v=ytqw8iMYbog)

[FOSS4G Video on Vector Tiles](https://vimeo.com/106228141)


