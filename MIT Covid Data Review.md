
# Covid Dataset Review

Request: 
Clean data and get GeoData if possible from:

### Community Health Survey

- Only up to 2018

- SAS or converter required for it to work.

- No zip codes, neighborhood data liste in Codebook but not in file when converted to CSV from sas7bdat. 

- NOTE: For Neighborhood data (borough, community district, etc):
- Available with a Data Use Agreement. 
- Please contact EpiDataRequest@health.nyc.gov

- lots of irrelevant fields (Prison info, etc.)

- Dataset Page https://www1.nyc.gov/site/doh/data/data-sets/community-health-survey-public-use-data.page
- Code book for dataset https://www1.nyc.gov/assets/doh/downloads/pdf/episrv/chs2017-codebook.pdf

- Vital stats pageand other data page https://www1.nyc.gov/site/doh/data/data-sets/vital-statistics-data.page
### NYC Health and Hospitals data-Github https://github.com/nychealth/coronavirus-data

- No zip data on death location, only tests

- Zips not 100% match to Mzcta- 37 do not match

- Successfully made a table that matches the ZCTA to Modzcta

- https://github.com/nychealth/coronavirus-data

- Visualizations exsist made by DOHM https://www1.nyc.gov/site/doh/covid/covid-19-data.page

### Taxi data

- has Taxi zone codes instead of zip codes

- See here for Monthly Breakdowns https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page

- Bit of a nightmare- TLC codes, no clear match to Zip. However, shapre files and such exist

- Factbook exists https://www1.nyc.gov/assets/tlc/downloads/pdf/2018_tlc_factbook.pdf

- Hard to clean, downloading data not recommeneded due to size, (100 million records), need to use Socrata to trim the data





## Community Health Survey

Converted the Community Health Survey to CSV
Using the sas7bdat module for Python

python C:\[path-to-Venv-Scripts]\Scripts\sas7bdat_to_csv "M:\git\chs2018_public.sas7bdat"



```python

```
