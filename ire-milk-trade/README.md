# Ireland Dairy Trade

The United Nations Comtrade database used to analyse Ireland's imports and exports of milk and cream in 2015:

* How much does Ireland export and import and is the balance positive (more exports than imports)?
* Which are the main trading partners, i.e. from/to which countries does Ireland import/export the most?
* Which are the regular customers, i.e. which countries buy milk from Ireland every month?
* Which countries does Ireland both import from and export to?

# Techie Notes 

The data can be downloaded from Comtrade using the "View API Call" URL, modified in the following ways:

- `max=500` is increased to `max=5000` to make sure all data is loaded,
- `&fmt=csv` is added at the end to obtain the data in CSV format.
- `&r=372` is the ID code for Ireland https://comtrade.un.org/data/cache/reporterAreas.json

Python 3 via Jupyter Notebook

# Questions? 

Email me at iworkwithdata@gmail.com 