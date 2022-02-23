# Seattle-Walkable?

Lukas Guericke

## Summary:

The focus of this project is to evaluate the geospacial factors that make neighborhoods in Seattle walkable neighborhoods. The goal will be to evaluate whether or not Seattle could be considered a walkable city, which neighborhoods are walkable, and which neighborhoods fail to meet the traditional metrics for a walkable neighborhoods? This project will use geospacial data collected from OpenStreetMaps of the City of Seattle for analysis. The methods used for walkability analysis will come from "Measuring Walkability with GIS—Methods Overview and New Approach Proposal" by Telega et al. who applied this method to Krakow, Poland. 

## Background:

Walkable cities and neighborhoods are key pillar of sustainable urban development. Research surrounding walkable cities and neighborhoods has provided evidence that walkable cities and neighborhoods are more livable, better for public health, and better for the enviornment. However, given this, many cities and neighborhoods in the United States are built around the use and ownership of a personal car. Seattle, a rapidly expanding city in terms of population, is not expanding its geographical footprint.  

##Problem Statement:

A rigid boundary, difficult geographical features, and an increased population with personal cars has lead to bad traffic and high accident rates. As the population continues to grow, does Seattle invest in sustainable urban development around the carless or in the infrastructre to keep the personal vehicle the primary choice of transportation for Seattlites? 

# Dataset:

OpenStreetMaps - City of Seattle

##Tools/Packages:

* [geopandas](https://geopandas.org/)
* [rasterio](https://rasterio.readthedocs.io/en/latest/)
* [matplotlib](https://matplotlib.org/stable/index.html)

## Planned Methodology:

The medthodology for this project will come from the methodology outlined by Telega et al. in "Measuring Walkability with GIS—Methods Overview and New Approach Proposal". In this study, they apply a raster analysis method on OpenStreetData for the City of Krakow, Poland. The researchers use different raster bands to indentify different street enviornments such as transport hubs, attractions, parks and playgrounds, shops and services, as well as the accessibility of pavements which are important to a city's walkability. Telega et al. claim that this method should work on most European cities, however, I will see if it works on an American city. I will comapare the results of this method to what I know about neighborhoods in Seattle and perhaps classic walkability metrics such as Walk Score.com. 

## Expected Outcomes:

I expect that we will be able to classify Seattle into different types of neighborhoods. We will have expensive, somewhat dense, attractions, with parks and accessible pavements neighborhoods that lack transit hubs. Examples of these neighborhoods would be Queen Anne, Ballard, Fremont, Beltown. On the other end of the spectrum, I predict we will see that relatively inexpensive area have lots of transit hubs but much fewer attractions, parks, and accessible pavements. Examples of these neighborhoods would be Northgate, Lake City, Crown Hill, and Beacon Hill. 

## References:

* [Measuring Walkability with GIS—Methods Overview and New Approach Proposal](https://www.mdpi.com/2071-1050/13/4/1883)
