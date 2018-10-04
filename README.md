# Statistics about Population age in Hartford by tracts #
Extracts ACS 2015 (5 year estimate) data for Hartford, in terms of median age, young population, elderly population, prime working population

## Specification ##
Source: <https://www.socialexplorer.com/>\
Survey: ACS 2015 (5-Year Estimates)\
Dataset: Social Explorer Tables: ACS 2015 (5-Year Estimates)\
Table: T7-Age

## Process ##
1. Navigate to <https://www.socialexplorer.com/>, click on "Start Now"
2. Once redirected to the map screen, click the hamburger menu on the top right, click "Create Report"
3. Survery: ACS 2015 (5-Year Estimate); Topic: Age; Geographies: upload <data/ACS-hartford-tracts.csv> 
4. A new tab will load with a bunch of tables. Click on "Data Download"
5. Check output options: "Output column labels in first row"
6. Download CSV
7. Run `Rscript data/process.R`
