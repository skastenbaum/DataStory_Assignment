# New York’s Housing Crisis Is Worsening
## New residential construction continues to fall for the third year in a row. A new tax abatement program aims to turn that around.

## By Steve Kastenbaum
## New York, May 17, 2025

New York ranks among the most expensive U.S. cities to live in, and the affordable housing crisis shows no signs of letting up. An analysis of building permits data shows that new housing starts continued to contract at the start of 2025.

The most effective way to bring some relief to the market is to build more housing. But new residential construction plummeted over the past three years. New building permits issued by the New York City Department of Buildings during the first quarter of 2025 fell significantly compared to the same period in 2024. This trend began following a peak in new residential construction permits in 2022, when developers raced to start their projects before a popular tax abatement policy expired. Lawmakers have since passed a new tax incentive, but the impact of that policy on the housing market may take years to be realized. In the meantime, comeptition for affordable housing units in New York remains fierce.

Read the full story here: https://skastenbaum.github.io/DataStory_Assignment/

# Methodology

Department of Buildings work permits data is available on NYC Open Data. It dates back over two decades, containing millions of lines of data. NYC Open Data's query functions enabled the filtering of the raw dataset to the years 2022 to 2025. Sixty columns of information was reduced to the relevant information for this analysis - the year a permit was issued, whether it was for a residential development, and some additional informaton including the borough and neighborhood for potential further analysis to drill down further into where new housing construction took place. New residential permits data for 2022 to 2024, and 2025 year to date, were merged using Python with Pandas. The data was then queried and permits for the first quarter of each year were counted, then compared. The resulting analysis is displayed in a bar chart created in Datawrapper. The work was also reproduced in Google Sheets. https://docs.google.com/spreadsheets/d/181r2cKvyfTSnSkNEjgTCldFAaiQujucuF5sNp9f6f5I/edit?gid=1213416083#gid=1213416083 The data is filtered by years and first qarters in individual tabs in the Google Sheet. The findings were included in a story reported on and published on the GitHub hosted website, https://skastenbaum.github.io/DataStory_Assignment/

# Conclusion 
Year over year, there's been a significant reduction in 1st quarter new residential building permits in New York City following a peak of 1964 in 2022. The number dropped to 1293 in Q1 2023, 768 in Q1 2024, and 582 in Q1 2025. 

# Data Source: 
https://data.cityofnewyork.us/Housing-Development/DOB-Permit-Issuance/ipu4-2q9a/data_preview

The story can be reproduced from this GitHub Repository: https://github.com/skastenbaum/DataStory_Assignment