# CDK Setup Examples

## Free tier

- VPC
- RDS (Postgres)
- Lambda
  - Database manipulation with `node-pg`
  - Database replication transforms

## TODO

- DMS
  - Logical replication with `pglogical` plugin

## TODO - Not free tieer

- Kinesis Firehose
  - Stream DMS events to transform lambda
  - Consume transformed lambda events and send to S3
