# Athena
Is serverless
Uses SQL to query data in S3. Supported file formats are:
  * CSV
  * JSON
  * ORC
  * Avro
  * Parquet
  * ...more

## Data sources
## Features
### Pros
* Significant cost savings and performance gains by compressing, partitioning, or converting your data to a columnar format
* Highly available
* Uses S3 as its data store
  * All benefits from S3 are assumed
  * Server-side encryption and client-side encryption are supported
* IAM policies can be used to control data access
* Integrates with AWS Glue. 
  * Glue's fully managed ETL capabilities can be used to transform data or convert it to columnar formats
* Federated query 
  * Amazon DynamoDB
  * Amazon Redshift
  * Amazon OpenSearch
  * MySQL
  * PostgreSQL
  * Redis
  * Other popular third-party data stores
* Integrates with SageMaker

### Cons
* In order to avoid scanning large amounts of data partitions should be carefully thought about, similar to how partitions in DynamoDB should be carefully considered

## Pricing


## Todo
* [ ] Create a sample application
  * IAM restriction to data
  * S3 clientside encryption
  * S3 serverside encryption
  * AWS Glue data catalog
  * SageMaker integration
  * Different file formats