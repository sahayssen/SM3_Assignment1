## Analysis of populations in New York state prisons.

This analysis was conducted as an assignment for CUNY Newmark Journalism School's Data Journalism class as well as the Criminal Justice reporting lab. 

The data analyzed here is part of a larger analysts about health staffing shortages in NY state prisons with a focus on medium and maximum security prisons. 

This repository contains data, analytic code, and findings from an analysis of prison population data sourced from the Correctional Association of New York:
  - `data/UNDER-CUSTODY-EXTRACT.CSV`: Raw data of the New York State prison popoluation across facilities of all security types, sentence-lengths, and crimes, from 2014 to 2026. 

You can find an explanation of the column names in the data dictionary listed here: (https://data.ny.gov/Transparency/Lobbyist-Bi-Monthly-Reports-2025/kn4r-wkd3/about_data)

## Methodology

The notebook [`Assignment1.ipynb`](notebooks/Assigment1.ipynb) performs the following analyses:

##### Part 1: Cleaning the data

- To start, I cleaned the data. I eliminated minimum security prisons and focused exclusively on open prisons in the most recent report, dated 8/1/2026. 

##### Part 2: Sorting the data 
- I sorted grouped the data by security type, facility type and race to get the racial breakdown of each prison. Then I created a new data set the total number of prisoners regardless of race in each facility and merged it with the racial breadown data. Lastly I did the same thing but with security levels and merged it with the original data set to create super data set. 

## Outputs

The notebooks output this spreadsheet which contains: 
- [`output/facility_merged.csv`]

The Google Sheet where I combined the population data with the staffing data. 
- [`output/HEALTH_SERVICES - LAM.xlsx`]

And a document with couple of paragraphs summarizing my methodology and findings: 
- [`output/Assignment 1 - Methodology.pdf`]

In case that doesn't work. Click <a href="https://docs.google.com/document/d/1fkEWC_EUnUIrFbDavn1ETVsfxgylXJIdXzvxxDON2IA/edit?usp=sharing"> here </a> for the Google Drive link. 


## Running the analysis yourself

You can run the analysis yourself. To do so, you'll need the following installed on your computer:

- Python 3
- The Python libraries specified in [`requirements.txt`](requirements.txt)

## Licensing

All code in this repository is available under the [MIT License](https://opensource.org/licenses/MIT). The data file in the output/ directory is available under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

## Feedback / Questions?

Contact SOPHIE HAYSSEN at sophie.hayssen67@journalism.cuny.edu