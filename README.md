# Project 1: An Analysis on Covid-19: Gender, Age, and Health

## Group: rougeSquadron
### Members: J. Forbis, K. St. Germain, J. Freeman, N. Tarver, S.Sweeny


# Background

On December 31st, 2019, China notified the World Health Organization (WHO) about a cluster of pneumonia cases in Wuhan. In a few weeks, WHO identified a novel coronavirus as the cause of this cluster. By the end of January of 2020, the United States reported its first case. In just under two months, the U.S. had exceeded 100,000 cases, becoming the new epicenter of the pandemic. Covid-19’s high infection rate has already led to a nation-wide shut-down; backed by concerns around over populating hospital systems. In addition, there has been large speculation around which demographics (age, gender, ethnicity) are high risk.

Core Question:
Who is most likely to be hospitalized?
To answer this question, we posed three hypotheses’:
·     Hypothesis 1: If males are more susceptible to Covid-19, then more hospitalizations will occur among male patients.
·     Hypothesis 2: If the elderly are more susceptible to Covid-19, then more hospitalizations will occur among elderly patients.
·     Hypothesis 3: If a person has has a pre-existing medical condition and contracts COVID-19, then they are more at risk to be hospitalized.
These three hypotheses should help to identify a person most at risk (being hospitalized) by analyzing their gender, age, and any pre-existing conditions.


# Folders
* In this repository you will find an Images, JupyterScripts, and Resources Folders. In addition, the powerpoint presentation and the group's plan outline can be found in the main directory.  

## Images

   * [BothGendersHosp.png](Images/BothGendersHosp.png): Bar Graph - Hospitalized Covid Males/Females
   * [BothGendersHosp_NoHosp.png](Images/BothGendersHosp_NoHosp.png): Bar Graph - Hospitalized and Non-Hospitalized Covid Males/Female
   * [ConditionsByGender.png](Images/ConditionsByGender.png): Bar Graph - Covid Males/Females with Pre-Existing and Non-Existing Conditions
   * [ConditionsByGenderDF.jpg](Images/ConditionsByGenderDF.jpg): DataFrame - Covid Males/Females with Pre-Existing and Non-Existing Conditions
   * [HospitalizationsByGenderDF.jpg](Images/HospitalizationsByGenderDF.jpg): DataFrame - Hospitalized Covid Males/Females
   * [MaleFemalePreXvsHosp.png](Images/MaleFemalePreXvsHosp.png): Bar Graph - Covid Males/Females Hospitalized with Pre-Existing Conditions
   * [PreExistingConditionHospitalizedDF.jpg](Images/PreExistingConditionHospitalizedDF.jpg): DataFrame - Covid Males/Females Hospitalized with Pre-Existing Conditions

## JupyterScripts

   * [Sidious Graphs.ipynb](JupyterScripts/Sidious Graphs.ipynb): Jupyter Notebook Script Analyzing Covid Males/Females Ages
   * [GendervsHosp.ipynb](JupyterScripts/GendervsHosp.ipynb): Jupyter Notebook Script Analyzing Covid Males/Females and Hospitalizations
   * [StevensCleanData.ipynb](JupyterScripts/StevensCleanData.ipynb): Jupyter Notebook Script cleaning the cleanedCaseSurveillance.csv . 
   * [forbis.ipynb](JupyterScripts/forbis.ipynb): Jupyter Notebook Script analyzing Covid Males/Females with pre-existing conditions. 
    
## Resources

   * [cleanedCaseSurveillance.csv](Resources/cleanedCaseSurveillance.csv): Cleaned CSV file of Covid Cases. Centers for Disease Control and Prevention, COVID-19 Response. COVID-19 Case Surveillance Public Data Access, Summary, and Limitations (version date: December 04, 2020).
   * [ageVsHosp.csv](Resources/ageVsHosp.csv): CSV comes from the main CSV, cleanedCaseSurveillance.csv, only has data for gender, age, and hospitalization. 
   * [genderVsHosp.csv](Resources/genderVsHosp.csv): CSV comes from the main CSV, cleanedCaseSurveillance.csv, only has data for gender and hospitalization. 
   * [preVsHosp.csv](Resources/preVsHosp.csv): CSV comes from the main CSV, cleanedCaseSurveillance.csv, only has data for gender, pre-existing conditions, and hospitalization. 

# Summary

