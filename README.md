# D4 Tutorial: Reproducibly Accessing Census Data in R & Python
**Authored By:**
[Tyler Fricker](https://www.ulm.edu/~tfricker/)
[Jessica Godwin](https://csde.washington.edu/staff/godwin-jessica/)
[June Yang](https://csde.washington.edu/staff/yang-june/)

R tutorial contained in *Census-data-in-R.Rmd* and *Census-data-in-R.html* files.
Python tutorial coming soon!

## **R Tutorial Outline**

*  Introduction
   *  Why use U.S. Census data in climate research?
   *  Census geographies and uncertainty
   *  Why access Census data with R or Python?
   *  Tutorial Outline
*  Accessing Census Bureau Data with R Packages
   *  The Census API and censusapi
   *  IPUMS, NHGIS, and ipums
   *  tidycensus and tigris
   *  Getting and managing your Census API key
*  Using tidycensus
   *  Selecting variables and tables
      *  Datasets
      *  Variable & table names
      *  Data Year
      *  Geographic scale
      *  Temporal scale
   *  Querying the Census API
      *  get_decennial()
      *  get_acs()
   *  Dealing with variable labels
*  Getting results
   *  Basic tables
   *  Multi-year results
   *  Aggregating estimates across labels
*  Census Geographic Data
   *  Plotting Geographic Data in R
   *  Working with Census Geometries
   *  Mapping Census and ACS Estimates in R
      *  Map-Making with ggplot2
      *  Map-Making with tmap
*  Areal Interpolation
