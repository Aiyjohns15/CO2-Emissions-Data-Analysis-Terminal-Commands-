The Scenario: A climate-and-energy nonprofit needs to decide where to
direct community-protection and climate-support efforts.

Dataset Overview: The CO2 emissions 2022 dfataset contains information about population, ceconomic development, and co2 emissions for various countries

| Column | Inferred type | How I can tell |
| --- | --- | ---
| country | string | all text no numbers|
| iso_code | string | all text no numbers |
| year | integer | whole numbers |
| population | integer | whole numbers|
| gdp | integer | whole numbers |
Source: Github repo

Findings: There are several missing values across the datset. There are also repeated values in the column 1 and continents listed where there should be country names. 

Data collection concerns: Was there sampling bias that caused there to be missing datapoints?

Questions: What is the direct correlation between population and co2 emission? What is the relationship between co2 emission and gdp?
