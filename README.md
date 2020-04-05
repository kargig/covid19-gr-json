# JSON Data for COVID-19 cases in Greece

Daily reports on Coronavirus disease (COVID-19) from [Greek National Public
Health Organization (EODY)](https://eody.gov.gr) converted to json

## Original source

json files have been manually created based on PDF files distributed from
[EODY](https://eody.gr), e.g. https://eody.gov.gr/covid-gr-daily-report-20200323/
All the original pdfs for reports can be found at [EODY Daily reports](https://eody.gov.gr/epidimiologika-statistika-dedomena/imerisies-ektheseis-covid-19/)

## Data inconsistency

Reports from EODY don't have the same data nor the same format each day so
it's impossible to have consistency in the json files as well. That's why
changes in the json format files are to be expected.

Examples of data that doesn't exist in every report:

- Details on hospitalized cases (age, gender)
- Hospitalized patients vs patients in IC
- Details per region
- Greeks vs non-Greeks
