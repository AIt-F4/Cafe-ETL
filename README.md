# Cloud Computing: AWS Project
Fully scalable ETL and Data Analytics  pipeline using AWS (IaC via CloudFormation)

A [presentation going over the project](https://docs.google.com/presentation/d/1Hf6a85HR2oBDDlbwiP2fimTFD9-cgouaZJqoo6eqgro/edit?usp=sharing)
## Problem Overview
```
Current Set-Up:
- Branch data is isolated
- Manual upload into standard database
- Time consuming to gather all branch data
- Difficult to identify company wide trends

```
## Solution Overview
```
- Fully scalable ETL pipeline:

    - Sanitise data: Remove PII (Personal Identifiable Information)
    - Normalise data to a set standard
    - Monitor infrastructure metrics
    - Data Analytics

- Capable of handling large data volume

- Store data in central data warehouse

- Enable company wide to branch specific data analytics

```
## Technologies
```
- ETL pipeline:
    - AWS:
        - CloudFormation
        - S3
        - Lambda
        - SQS(FIFO Queue)
        - Redshift
        - IAM
    - Python

- Data Analytics (+ Infrastructure Metrics):
    - AWS:
        - Cloudwatch
        - EC2
    - Docker
    - Grafana

```

