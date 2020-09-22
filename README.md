## US Local Area Unemployment Statistics

This repository shows how I pulled and cleaned the Local Area Unemployment Statistics data from The Bureau of Labor Statistics' (BLS) Public Data Application Programming Interface (API).

For more information on the API, please visit the official site: https://www.bls.gov/developers/

### Process
- Build a list of the SeriesIDs needed by pulling the area_code for all US cities and towns above 25,000 population (Source: https://download.bls.gov/pub/time.series/la/la.area)
- Pull data from the BLS API, and save to a CSV
- Cleaned the data from the CSV file to clearly identify the city and states for all of the pulled data
- Calculated the difference in the Unemployment Rate for each city from February 2020, then saved to a new CSV

### Libraries
- `pandas`
- `requests`
- `json`

### Data Visualizations
Check out my Tableau dashboard: https://public.tableau.com/profile/meggan7833#!/vizhome/us-unemployment/Dashboard1
