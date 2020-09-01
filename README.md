# Geospatial-ERA5-prediction
This project aims around exploring and evaluating the ERA5-Land Hourly Reanalysis Data from CDS API

# Environment Setup
1. To download the dataset copy the .cdsapric file in the location $HOME for Linux users, and C:/Users/<Your name>/ on Windows.
2. To get the cds api, go to https://cds.climate.copernicus.eu and creat yand our account
3. After creating the account, verify it and you can access your UID and access key by clicking on your profile name
4. Insert these values in the .cdsapric file, where url will be https://cds.climate.copernicus.eu/api/v2 and key would be your UID:access key
5. Run the download.py and the dataset will be downloaded. Save it in your current working directory
6. You can chose different daatsets fromt this website and the site will generate the API request.
