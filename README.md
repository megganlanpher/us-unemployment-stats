## US Local Area Unemployment Statistics

This repository shows how I pulled and cleaned the Local Area Unemployment Statistics data from The Bureau of Labor Statistics' (BLS) Public Data Application Programming Interface (API).

For more information on the API, please visit the official site: https://www.bls.gov/developers/

### Process
- Build a list of the SeriesIDs needed by pulling the area_code for all US cities and towns above 25,000 population (Source: https://download.bls.gov/pub/time.series/la/la.area)
- Pull data from the BLS API, and save to a CSV
- Create a cleaned CSV file that clearly identifies the city and states for all of the pulled data

### Libraries
- `pandas`
- `requests`
- `json`
