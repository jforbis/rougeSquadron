# rougeSquadron
## Project Title: 
•	COVID-19 Impacts: Politics, Population Demographics, & Ethnicity

## Project Members
* John F.
* Kayla S.
* Jay F.
* Neal T.
* Steven S.

## Project Description/Outline
In looking at US data on COVID-19 cases we compared the following by yearly seasons in 2020; Spring, Summer, and Fall.

* Politics - Number of cases in Red vs Blue states
* Population Demographics - number of cases with regard to both gender and age
* Ethnicity – Number of cases in & ethnicity

**Season definition:
* Spring – March-May
* Summer – June-Aug
* Fall – Sept-Nov

## Questions to Answer
* Is there a correlation between number of COVID-19 hospitalizations and overall political stance of state?
* Is there a correlation between a state’s political stance and the impact (hospitalization of ethnicity) of COVID-19 on ethnicity in said state?
* Which ethnicity has been more impacted?
* How has the impact of COVID-19 on ethnicity changed over the course of our three seasons?
* Is it true that only older populations are affected (hospitalized) the most by COVID-19?

## Datasets to be used
* HealthData.gov (https://healthdata.gov/node/3281086/api) (various datasets regarding health data)
* covidtracking.com/data/api

    * CDC

        * https://dev.socrata.com/ (documentation for cdc's platform of 'open data')
        * https://www.cdc.gov/apis.html (link to their api list and documentation)
        * https://data.cdc.gov/resource/vbim-akqf.json (endpoint starts after 'resources/', this specific endpoint is for demographics of hospital beds)
    * US Census
        * https://api.census.gov/data/2019/acs/acs1/spp/variables.html (variables for api calls)
        * example call: https://api.census.gov/data/2019/acs/acs1/spp?get=NAME,group(S0201)&for=us:1&POPGROUP=001&key=API_KEY_GOES_HERE
        
    * Political Data from 2020 election (to achieve ‘red’ and ‘blue’ determination)
    * https://documenter.getpostman.com/view/8854915/SzS8rjHv?version=latest (hospitalization data)

## Rough breakdown of tasks/steps:
* Find correlation of the following:
    * Politics
        * Find red vs blue states
        * Combine this data with hospitalization data
        * Bin day/month into season
        * Run correlation on data
    * Population Demographics (gender/age)
        * Merge census data with hospitalization data 
        * Create hot-spot graphic comparing both gender and age (age would be youth, adult, senior)
        * Run correlation to see which gender and age class is affected the most.
    * Ethnicity Demographics
        * Merge census data with hospitalization data
        * Create visualizations showing impact (hospitalization) on ethnicities (white, african american, asian, hispanic, native american)
        * Run correlation on each ethnicity and see which is more affected
