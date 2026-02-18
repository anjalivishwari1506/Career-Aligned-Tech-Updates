## Bronze Layer
- Raw documents
- Immutable
- Partitioned by ingestion_date

## Silver Layer
- Cleaned text
- Metadata extracted
- Deduplicated using embedding similarity

## Gold Layer
- Ranked updates
- Career-tagged
- Ready for delivery

Partition Strategy:
- publish_date
- role_tag

--------------------------------------------------------------------
