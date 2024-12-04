# Milk production - Data package

This data package contains the data that powers the chart ["Milk production"](https://ourworldindata.org/grapher/milk-production-tonnes?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on December 04, 2024.

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


## Milk production – FAO
Last updated: March 14, 2024  
Next update: March 2025  
Date range: 1961–2022  
Unit: tonnes  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World in Data

#### Full citation
Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World in Data. “Milk production – FAO” [dataset]. Food and Agriculture Organization of the United Nations, “Production: Crops and livestock products” [original data].
Source: Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World In Data

### What you should know about this data

### How is this data described by its producer - Food and Agriculture Organization of the United Nations (2023)?
Item: Milk
Description: Milk, eggs, honey and beeswax are included as products of live animals. Fibres of animal origin (mainly wool and silk) are included with fibres of vegetal and animal origin. Milk and dairy products. Estimates of milk production as reported by countries refer to one or more of the following three concepts. Gross production is milk production plus milk sucked by young animals. Production available for consumption is net production less milk fed to animals, milk retained by farmers for food and feed, direct sales to consumers and farm waste. The FAO concept relates to net milk production. Data should be reported by kind of milking animal (cow, sheep, goat, etc.) in terms of whole milk and by weight. In most developed countries only 5-10 percent of whole milk is used directly for human consumption. The bulk of milk production is processed before being marketed as liquid milk (e. G. standardized, pasteurized, skimmed, etc.) or is manufactured in to products such as cream, butter, cheese, evaporated and condensed milk, milk powder, casein, yogurt, ice cream, etc. About 70 percent of whole milk is processed into dairy products; the by-products of these processes (e. G. skim milk, buttermilk and whey) are used either for feed or are manufactured into other dairy products, e. G. dry skim milk and low-fat cheese. Processed milk and dairy products are often supplemented with vitamins, mineral and various additives. FAO list 50 milk and dairy product items in the list that follows, of which five are primary products. Some food products containing milk are not listed separately by FAO, e. G. eggnog, sherbet, malted milk, chocolate milk drink and mellorine.

Metric: Production
Description: Amount produced in the year

### Source

#### Food and Agriculture Organization of the United Nations – Production: Crops and livestock products
Retrieved on: 2024-03-14  
Retrieved from: http://www.fao.org/faostat/en/#data/QCL  


    