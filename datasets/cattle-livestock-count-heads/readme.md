# Number of cattle - Data package

This data package contains the data that powers the chart ["Number of cattle"](https://ourworldindata.org/grapher/cattle-livestock-count-heads?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on December 04, 2024.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Number of cattle – FAO
Last updated: March 14, 2024  
Next update: March 2025  
Date range: 1961–2022  
Unit: animals  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World in Data

#### Full citation
Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World in Data. “Number of cattle – FAO” [dataset]. Food and Agriculture Organization of the United Nations, “Production: Crops and livestock products” [original data].
Source: Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World In Data

### What you should know about this data

### How is this data described by its producer - Food and Agriculture Organization of the United Nations (2023)?
Item: Cattle
Description: Cattle This subclass includes: - cattle, species of Bos, mainly bovis, taurus, indicus, grunniens, gaurus, grontalis and sondaicus, known with many different names: ox, zebu, yak, gaur, gayal, banteng, etc. This subclass does not include: -  buffalo, species of Bubalus, Syncerus and bisons, species of Bison, cf. 02112

Metric: Stocks
Description: This variable indicates the number of animals of the species present in the country at the time of enumeration. It includes animals raised either for draft purposes or for meat, eggs and dairy production or kept for breeding. Live animals in captivity for fur or skin such as foxes, minks etc. are not included in the system although furskin trade is reported. The enumeration to be chosen, when more than one survey is taken, is the closest to the beginning of the calendar year. Livestock data are reported in number of heads (units) except for poultry, rabbits and other rodents which are reported in thousand units. Source: FAO Statistics Division

### Source

#### Food and Agriculture Organization of the United Nations – Production: Crops and livestock products
Retrieved on: 2024-03-14  
Retrieved from: http://www.fao.org/faostat/en/#data/QCL  


    