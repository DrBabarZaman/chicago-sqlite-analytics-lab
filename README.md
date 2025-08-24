# Chicago Open Data → SQLite Analytics (Census, Schools, Crime)

A compact, reproducible analytics lab that:
- Loads three Chicago datasets into **SQLite** tables using **Python/Pandas**
- Runs **SQL** queries to explore socioeconomic indicators, public school performance, and crime records
- Demonstrates an end‑to‑end mini data pipeline suitable for teaching/learning SQL with real data

> **Date completed:** 24 Aug 2025 • **Author:** Dr. Babar Zaman

## Datasets
Subsets prepared for coursework (with column names made DB‑friendly):

1. **Socioeconomic Indicators (2008–2012)**  
   Source: Chicago Data Portal (subset used in this lab)  
   https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2

2. **Chicago Public Schools (2011–2012 School Report Cards)**  
   https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t

3. **Chicago Crime (2001–present; rolling minus 7 days)**  
   https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2

**CSV subsets used here (recommended for this lab):**
- Chicago Census Data:  
  https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoCensusData.csv
- Chicago Public Schools:  
  https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoPublicSchools.csv
- Chicago Crime Data:  
  https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoCrimeData.csv

> **Note:** Use the CSV links above (subsetted & cleaned) rather than raw portal exports for a smoother DB import.

## Tech stack
- **Python 3.10+**: `pandas`, `sqlite3`, `ipython-sql`
- **SQLite**: local file DB (`FinalDB.db`)
- **Jupyter Notebook** (optional) or plain Python script

## Project structure
