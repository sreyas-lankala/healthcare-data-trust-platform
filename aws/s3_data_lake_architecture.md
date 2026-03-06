# Data Lake Architecture

The Healthcare Data Trust Platform stores raw clinical datasets in an AWS S3 data lake.

The data lake acts as the single source of truth for all upstream datasets entering the platform.

Datasets are stored in their original format and are not modified at this stage of the pipeline.

Example folder structure:

s3://healthcare-data-trust/

raw/
  patients/
  admissions/
  diagnoses/
  procedures/
  labevents/

This design ensures reproducibility and enables downstream transformations
to be rebuilt directly from raw datasets.