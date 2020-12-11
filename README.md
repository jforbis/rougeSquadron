# GROUP: rougeSquadron
# PROJECT TITLE: The Relationship of COVID19 on Sex, Age, and Preexisting Medical Conditions. 

# MEMBERS
* John F.
* Kayla S.
* Jay F.
* Neal T.
* Steven S.

# HYPOTHESISES
    1. If males are more susceptible to COVID19, then more hospitalizations will occur amoung COVID19 male patients.
    2. If the elderly are more susceptible to COVID19, then more hospitalizations will occur amoung COVID19 elderly patients.
    3. If a person has COVID19 and pre-existing medical conditions, then they will be hospitalized. 

# TASKS
    1. Clean the CSV File - Due: Thursday-Friday

    2. Create 3 DataFrames to support each hypothesis - Due: Thursday-Friday
        a. patient_sex_df = ['Current Status': ['Lab Confirmed'], 'Sex': ['Male','Female'], 'Hospitalized': ['Yes','No'], 'Age Group']
        b. patient_age_df = ['Current Status': ['Lab Confirmed'], 'Sex': ['Male','Female'], 'Hospitalized': ['Yes','No'], 'Age Group': ['Younger than 50', '50 and Older']]
        c. patient_premed_df = ['Current Status': ['Lab Confirmed'], 'Sex': ['Male','Female'], 'Hospitalized': ['Yes','No'], 'Age Group', 'Pre-Existing Conditions: ['Yes','No']]

    3. Create Plots to Represent the Data - Due: Thursday-Friday
        a. Bar Plot of Male and Female vs. Hospitalizations
        b. Bar Plot of Age vs. Hospitalizations (Both Sexes)
        c. Bar Plot of Age vs. Hospitalizations (Male)
        d. Bar Plot of Age vs. Hospitalizations (Female)
        e. Bar Plot of Pre-Existing and Non-Existing Conditions vs. Hospitalizations (Both Sexes)
        f. Bar Plot of Pre-Existing and Non-Existing Conditions vs. Hospitalizations (Male)
        g. Bar Plot of Pre-Existing and Non-Existing Conditions vs. Hospitalizations (Female)

    4. Outline of Presentation - Due: Saturday

    5. Work on Presentation - Due: Sunday - Monday

    6. Finalize Project and Rehersal - Due: Tuesday

    7. Rehersal - Due: Wednesday

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
