# Data Ingestion Interview  
Located at the following urls are 4 csvs:  
https://datainterviews.blob.core.windows.net/interview-data/causal_lookup.csv
https://datainterviews.blob.core.windows.net/interview-data/product_lookup.csv
https://datainterviews.blob.core.windows.net/interview-data/store_lookup.csv
https://datainterviews.blob.core.windows.net/interview-data/transactions.csv

The intention of this exercise is to ingest the data from these CSVs into a Postgres database.

The tables should be as follows:  
causal_lkp  
product_lkp  
store_lkp  
transaction_fct

No column should be nullable.

Please writea sql script to create the structures in the postgres schema and a python script to ingest the data.  Commit both of these files into your fork of this repo and issue a pull request when completed.
