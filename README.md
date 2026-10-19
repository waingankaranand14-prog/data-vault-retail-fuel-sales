Retail Fuel Sales – Data Vault 1.0 & 2.0

**Overview**
This project demonstrates the design and implementation of Data Vault 1.0 and Data Vault 2.0 for a retail fuel sales analytics use case.

The objective is to demonstrate scalable historical data modeling using Hub, Link and Satellite structures.

**Technology Stack**
AWS S3
AWS EMR
Apache Spark / PySpark
Amazon Redshift
SQL

**Architecture**
Source Systems -> AWS S3 -> AWS EMR / Spark -> Staging Layer -> Raw Data Vault -> Business Vault -> Amazon Redshift -> Analytics / Reporting

**Data Vault Components**
Hubs
HUB_CUSTOMER
HUB_PRODUCT
HUB_STATION
HUB_TRANSACTION

Links
LINK_SALES_TRANSACTION
LINK_CUSTOMER_TRANSACTION

Satellites
SAT_CUSTOMER
SAT_PRODUCT
SAT_STATION
SAT_TRANSACTION

**Data Vault 1.0**
The DV 1.0 implementation demonstrates:

Business Keys
Hub / Link / Satellite architecture
Historical tracking
Load Date
Record Source
Data Vault 2.0

**The DV 2.0 implementation extends the model with:**

Hash Keys
HashDiff
Parallel loading
PIT tables
Scalable ELT processing
Documentation
Detailed architecture and implementation documentation is available under the /docs directory.

**Purpose**
This is a portfolio project created to demonstrate Data Vault architecture and data-modeling concepts.
