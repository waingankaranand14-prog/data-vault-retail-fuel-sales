Retail Fuel Sales – Data Vault 1.0 & 2.0

**Overview**
This portfolio project demonstrates the design of a Data Vault-based data warehouse for a fictional Retail Fuel Sales analytics use case.

The project illustrates Data Vault 1.0 and Data Vault 2.0 modelling concepts using Hub, Link and Satellite structures, with a focus on historical data tracking, scalability and auditable data integration.

**Technology Stack**
Amazon S3
AWS EMR
Apache Spark / PySpark
Amazon Redshift
SQL

**Architecture**
Source Systems -> Amazon S3 -> AWS EMR / Spark -> Staging Layer -> Raw Data Vault -> Business Vault -> Amazon Redshift -> Analytics / Reporting

**Data Vault Components**
**Hubs**
HUB_CUSTOMER
HUB_PRODUCT
HUB_STATION
HUB_TRANSACTION
**Links**
LINK_SALES_TRANSACTION
LINK_CUSTOMER_TRANSACTION
**Satellites**
SAT_CUSTOMER
SAT_PRODUCT
SAT_STATION
SAT_TRANSACTION


**Data Vault 1.0**
The Data Vault 1.0 design demonstrates:

Business Keys
Hub, Link and Satellite modelling
Historical tracking
Load Date / Load Timestamp
Record Source
Insert-only historical storage


**Data Vault 2.0**
The Data Vault 2.0 design extends the model with:

Hash Keys
HashDiff-based change detection
Parallel loading concepts
PIT (Point-in-Time) tables
Scalable processing using Spark / PySpark
Raw Vault and Business Vault concepts

**Key Learning Areas Demonstrated**
This project covers:

Identification of business keys
Modelling Hubs, Links and Satellites
Historical data management
Data Vault 1.0 vs Data Vault 2.0
Hash Key generation
HashDiff-based change detection
PIT table concepts
Raw Vault and Business Vault
Integration with an AWS-based data architecture
Transformation toward an analytics/reporting layer

**Project Documentation**
Detailed Data Vault modelling, architecture, loading concepts and implementation examples are available in:
Data_Vault_1_and_2_GitHub_Project_Anand.docx

**Purpose**
This is a self-developed portfolio project created to demonstrate Data Vault modelling and data architecture concepts.

The business scenario and sample datasets used in this project are fictional/synthetic and are intended solely for learning and portfolio demonstration purposes.
