# D4 Tutorial: Reproducibly Accessing Census Data in R & Python

**Outline**

  *  Text Intro
     *  Why Census data for climate work?
     *  Why R/Python vs. point-and-click?
     *  Organization of rest of tutorial
  *  Accessing Census Bureau Data with R Packages
     *  The Census API and censusapi
     *  IPUMS, NHGIS, and ipumsr
     *  tidycensus
     *  Getting your API key and writing reproducible/collaborative code that does not disclose your API key
  *  Using tidycensus to access variables and tables
     *  Choosing an appropriate Census dataset for your task
     *  Finding variable names by searching concepts and labels
     *  Pulling data and basic cleaning (i.e. dealing with the "!!" in the labels)
  *  Getting results
     *  Combining Census data with other data sources
     *  Aggregating estimates across labels (i.e. getting the standard errors as right as you can)
     *  Creating maps
