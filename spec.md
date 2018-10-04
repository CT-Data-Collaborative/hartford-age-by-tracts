# Specification #
Source: <https://www.socialexplorer.com/>
Survey: ACS 2015 (5-Year Estimates)
Dataset: Social Explorer Tables: ACS 2015 (5-Year Estimates)
Table: T7-Age

# Process #
1. Navigate to <https://www.socialexplorer.com/>, click on "Start Now"
2. Once redirected to the map screen, click the hamburger menu on the top right, click "Create Report"
3. Survery: ACS 2015 (5-Year Estimate); Topic: Age; Geographies: upload <data/ACS-hartford-tracts.csv> 
4. A new tab will load with a bunch of tables. Click on "Data Download"
5. Check output options: "Output column labels in first row"
6. Download CSV


## Raw Email Contents ##
ACS 2011-2015 (’15, 5 year estimates), per Census tract in Hartford:

 Median Age — should be a single number about 30-40 for each tract
 Young Population (under 18) — should be a number, we care about the percentage. So nominator should be the total number of residents of that tract who are younger than 18, and the denominator should be the total number of residents in that tract. We have the denominator, so don’t worry.
 Elderly Population (65+)
 Prime Working Age (25-54). A bit trickier because it combines several cohorts of people.
 Unemployment. We care about total labor force in each FIPS (tract) to serve as a denominator, but most importantly we need the number of employed (or unemployed) people in each FIPS. We NEED denominator for this one, too.

 For each metrics, we need two separate CSV files: nominator and denominator.
 Two columns:
   Id,y_2011-2015
 090035….,
