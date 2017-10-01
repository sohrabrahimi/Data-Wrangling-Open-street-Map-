# Description
[OpenStreetMap](https://www.openstreetmap.org) is a free, editable map of the whole world that is being built by volunteers largely from scratch and released with an open-content license. The [OpenStreetMap License](https://www.openstreetmap.org/copyright) allows free (or almost free) access to the map images and all of the underlying map data. The project aims to promote new and interesting uses of this data.

In this project I chose Pittsburgh, PA from [https://www.openstreetmap.org](https://www.openstreetmap.org/#map=10/42.4108/-71.1131) and used data munging techniques, such as assessing the quality of the data for validity, accuracy, completeness, consistency and uniformity, to clean the OpenStreetMap data for a part of the world that I cared about the most i.e. Pittsburgh. This project has been conducted via SQL API in Python. This project includes the following steps: 

* Audit map data for validity, accuracy, completeness,consistency and uniformity.
* Fix the problems encountered and export the audited data from XML to CSV format .
* Store the CSV's into an sqlite database (using the selected schema) and use SQL to query and aggregate the stored data.


# Requirements

* Python 2.7
* sqlite
* Pandas
* Usage

# Code
 Please refer to this file: OSM_Wrangling_SR.ipynb
