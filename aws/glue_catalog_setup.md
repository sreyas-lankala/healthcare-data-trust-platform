# AWS Glue Data Catalog

The Healthcare Data Trust Platform uses AWS Glue Data Catalog
to store metadata for datasets located in the S3 data lake.

A database named `healthcare_raw` is created to catalog
raw datasets stored in the raw data lake layer.

This metadata enables query engines such as Amazon Athena
to interpret S3 datasets as structured tables.