# Data Partitioning Strategy

Large datasets in the Healthcare Data Trust Platform are partitioned
to improve query performance and reduce compute costs.

Example partition structure:

raw/admissions/
  year=2023/
  year=2024/

Partitioning allows query engines such as Amazon Athena to scan only
relevant partitions rather than the entire dataset.

This significantly improves performance for large-scale analytics workloads.