# data-sourcing-challenge
# Description
This program imports May 2013 to May 2024 data from the NASA DONKI database via an API connection.  CME and GST data are downloaded individually, merged, and then the time difference between the CME event and the GST event is calculated.  Results are exported as a CSV into working directory. 
# Needed files
- None
# Dependencies
- pandas
- os
- requests
- dotenv
- json
- datetime
- API access and key to NASA DONKI database (https://api.nasa.gov/DONKI/).  Key should be stored in a .env file.
# Python version
- 3.12.7
