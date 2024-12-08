# Quality-Movie-Data-Analysis
➢	Process and ingest only quality movies in Redshift Data Warehouse      
   Tech Stack – S3, Glue Crawler, Glue Catalog, Glue catalog Data Quality, Glue low code ETL, Event Bridge, SNS, Redshift.

●	Developed and deployed a comprehensive data pipeline for efficient ingestion of high-quality movie data into Redshift.
●	Implemented data quality checks to exclude movies that did not meet predefined quality criteria. 
●	Leveraged Event Bridge rules to trigger notifications via SNS, highlighting movie records that failed to transfer into Redshift, subsequently redirecting them to a separate S3 bucket for remedial action.
