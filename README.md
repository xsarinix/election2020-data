# election2020-data
Contains raw 2000-2020 county-level vote returns for US presidential elections and selected 2019 American Community Survey tables.

My first data source was a CSV file of the official state county-level returns for presidential elections from 2000 to 2020, as compiled by the MIT Election Data and Science Lab^1^ and published on 2022-11-01. MEDSL collects, analyzes, and shares data in order to advance election science in the United States. It can be downloaded [here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/VOQCHQ).

My secondary data sources were CSV files of the 2019 American Community Survey (ACS) 1-year estimates detailed tables for counties with populations of 65,000+ and were acquired from the [US Census Bureau](https://data.census.gov/table?g=0100000US$0500000&y=2019&d=ACS+1-Year+Estimates+Detailed+Tables)^2^. This data was published in October of 2020 just prior to the election. The following tables were used:

| Table                                                                                                                            | Description                                                        |
|------------------------------------|------------------------------------|
| [B02001](https://data.census.gov/table?g=0100000US$0500000&y=2019&d=ACS+1-Year+Estimates+Detailed+Tables&tid=ACSDT1Y2019.B02001) | Race                                                               |
| [B11012](https://data.census.gov/table?g=0100000US$0500000&y=2019&d=ACS+1-Year+Estimates+Detailed+Tables&tid=ACSDT1Y2019.B11012) | Households by Type                                                 |
| [B15002](https://data.census.gov/table?g=0100000US$0500000&y=2019&d=ACS+1-Year+Estimates+Detailed+Tables&tid=ACSDT1Y2019.B15002) | Sex by Educational Attainment for the Population 25 Years and Over |
