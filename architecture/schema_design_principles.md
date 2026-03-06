# Schema Design Principles

The Healthcare Data Trust Platform follows a schema-on-read architecture for raw datasets stored in the data lake.

Raw clinical datasets are stored in Amazon S3 without enforcing strict schemas during ingestion.

Schemas are applied later when datasets are queried through the Athena staging layer.

This design provides flexibility in handling evolving healthcare data formats and allows ingestion pipelines to remain lightweight and scalable.git add .
git commit -m "Document schema-on-read design for data lake"
git push